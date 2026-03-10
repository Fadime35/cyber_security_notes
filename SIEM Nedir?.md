## SIEM Nedir?

SIEM, farklı sistemlerden gelen güvenlik loglarını toplayan, analiz eden ve şüpheli aktiviteleri tespit eden güvenlik yönetim sistemidir.

**SIEM kelimesi şu iki kavramın birleşimidir:**

- Security Information

- Event Management

**Amaç:**

- Güvenlik olaylarını merkezi bir sistemde toplamak

- Saldırıları erken tespit etmek

- Güvenlik ekiplerine uyarı (alert) üretmek

SIEM sistemleri özellikle SOC ekipleri tarafından kullanılır.

## SIEM Nasıl Çalışır?

Bir kurumda birçok cihaz log üretir. SIEM bu logları tek bir yerde toplar.

**Log gelen kaynaklar:**

- Sunucular

- Firewall

- IDS / IPS sistemleri

- Web sunucuları

- Veritabanları

- Uygulamalar

- Ağ cihazları

SIEM bu logları analiz eder ve şüpheli durumları tespit eder.

## SIEM Çalışma Aşamaları

### 1) Log Toplama

Farklı sistemlerden log verileri toplanır.

**Örnek kaynaklar:**

- Firewall logları

- Windows event logları

- Linux sistem logları

- Web server logları

### 2) Log Normalizasyonu

Farklı formatlardaki loglar standart bir formata dönüştürülür.

**Amaç:**

Verilerin kolay analiz edilmesi

### 3) Korelasyon (Correlation)

SIEM farklı logları birleştirerek anlamlı olaylar oluşturur.

**Örnek:**

- Bir IP çok sayıda login denemesi yapıyor

- Aynı IP kısa süre sonra başarılı giriş yapıyor

- Bu durumda sistem brute force saldırısı tespit edebilir.

### 4) Alert (Uyarı)

Şüpheli bir durum tespit edildiğinde güvenlik ekibine uyarı gönderilir.

**Örnek:**

- Çok sayıda başarısız login

- Şüpheli veri transferi

- Yetkisiz erişim

### 5) Raporlama

SIEM sistemleri güvenlik raporları oluşturur.

**Örnek raporlar:**

- Günlük saldırı raporları

- Güvenlik ihlali raporları

- Kullanıcı aktiviteleri


## SIEM Sistemlerinin Avantajları

- Tüm logları merkezi olarak toplar

- Saldırıları erken tespit eder

- Güvenlik olaylarını analiz etmeyi kolaylaştırır

- Uyumluluk raporları üretir (compliance)

---

### SOC Analisti Açısından Önemi

SOC analistleri SIEM üzerinden çalışır.

**Analistlerin yaptığı işlemler:**

- Gelen alarmları incelemek

- Log analizleri yapmak

- Şüpheli aktiviteleri araştırmak

- Olay müdahalesi yapmak

SIEM sistemi olmadan büyük bir ağdaki güvenlik olaylarını takip etmek çok zor olur.

### Örnek SIEM Araçları

**En yaygın SIEM araçları:**

- Splunk

- IBM QRadar

- Elastic SIEM

- LogRhythm

- ArcSight
  
