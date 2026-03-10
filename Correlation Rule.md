## Correlation Rule (Korelasyon Kuralı)

Correlation Rule, SIEM sistemlerinde farklı kaynaklardan gelen logları birleştirerek şüpheli aktiviteleri tespit eden kurallardır. Tek bir log genellikle 
saldırıyı anlamak için yeterli değildir. Korelasyon kuralları birden fazla olayı ilişkilendirerek anlamlı güvenlik uyarıları üretir.

**Amaç:**

- Farklı logları ilişkilendirmek

- Şüpheli davranışları tespit etmek

- Otomatik güvenlik uyarıları oluşturmak

## Correlation Rule Nasıl Çalışır?

**Bir sistemde farklı cihazlar log üretir:**

- Firewall

- Sunucular

- Web uygulamaları

- Kimlik doğrulama sistemleri

SIEM bu logları analiz eder ve belirli koşullar oluştuğunda alarm üretir.

**Basit mantık:**

Birden fazla olay + belirli zaman aralığı + belirli koşullar = güvenlik uyarısı

## Örnek Correlation Rule Senaryoları

### 1) Brute Force Tespiti

**Koşul:**

- Aynı IP adresinden

- 5 dakika içinde

- 10 başarısız giriş denemesi

**Sonuç:**

Brute force saldırısı uyarısı oluşturulur.

### 2) Başarısız Giriş + Başarılı Giriş

**Koşul:**

- Çok sayıda başarısız login

- Hemen ardından başarılı login

**Sonuç:**

Hesap ele geçirilmiş olabilir.

### 3) Farklı Lokasyonlardan Giriş

**Koşul:**

- Aynı kullanıcı hesabı

- Kısa süre içinde

- Farklı ülkelerden giriş

**Sonuç:**

Şüpheli hesap kullanımı.

### 4) Malware İletişimi

**Koşul:**

- Endpoint sistemi

- Şüpheli bir IP adresi ile bağlantı kuruyor

- Aynı IP daha önce zararlı olarak işaretlenmiş

**Sonuç:**

Malware Command and Control iletişimi.

## Correlation Rule Bileşenleri

Bir korelasyon kuralı genellikle şu bilgilerden oluşur:

**Event Source**

Logun geldiği sistem

**Condition**

Kontrol edilen koşullar

**Time Window**

Olayların gerçekleştiği zaman aralığı

**Threshold**

Belirlenen olay sayısı

**Action**

Oluşturulacak alarm veya işlem

---

### SOC Analisti Açısından Önemi

SOC ekipleri SIEM üzerinde gelen alarmların çoğunu korelasyon kuralları sayesinde görür.

**Bu kurallar sayesinde:**

- Brute force saldırıları

- Yetkisiz erişimler

- Veri sızıntıları

- Malware aktiviteleri

erken aşamada tespit edilir.
