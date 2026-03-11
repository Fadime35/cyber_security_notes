## False Positive

False Positive, güvenlik sisteminin aslında zararsız olan bir olayı saldırı gibi algılamasıdır. Yani sistem alarm üretir fakat gerçek bir güvenlik tehdidi yoktur.

Amaç dışı bir alarmdır ve güvenlik ekipleri için gereksiz inceleme oluşturur.

**Normal bir olay → Sistem bunu saldırı zanneder → Alert oluşturur**

**Sonuç:** False Positive


### 1) Yanlış Şifre Denemeleri

- Bir kullanıcı şifresini birkaç kez yanlış girer.

- Sistem bunu brute force saldırısı gibi algılayabilir.

- Gerçekte ise kullanıcı sadece şifresini hatırlamıyordur.

### 2) Güvenlik Tarama Araçları

- Bir şirketin güvenlik ekibi kendi sistemini tarar.

- Tarama aracı birçok bağlantı denemesi yapar.

- Firewall bunu port scanning saldırısı olarak algılayabilir.

### 3) Yoğun Trafik

- Bir web sitesine aynı anda çok fazla kullanıcı girer.

- Sistem bunu DDoS saldırısı gibi algılayabilir.

- Ama aslında normal kullanıcı trafiğidir.

## False Positive Neden Oluşur?

**Başlıca sebepler:**

- Çok hassas güvenlik kuralları

- Yanlış yapılandırılmış sistemler

- Yetersiz bağlam analizi

- Güncel olmayan saldırı imzaları

## SOC Açısından Sorunları

False positive olayları SOC ekipleri için sorun oluşturabilir.

**Etkileri:**

- Analistlerin zamanını boşa harcar

- Gerçek saldırıların gözden kaçmasına neden olabilir

- Alert sayısını gereksiz artırır

- Bu duruma alert fatigue (alarm yorgunluğu) denir.

## False Positive Nasıl Azaltılır?

- Korelasyon kurallarını iyileştirmek

- Güvenlik politikalarını doğru ayarlamak

- Log analizini geliştirmek

- Whitelist (güvenilir kaynak listesi) oluşturmak

## SOC Analisti Ne Yapar?

**Bir alert geldiğinde analist şu soruyu sorar:**

Bu gerçek bir saldırı mı yoksa false positive mi?

**Bunu anlamak için:**

- Logları inceler

- IP adreslerini kontrol eder

- Kullanıcı davranışlarını analiz eder

- Ağ trafiğini araştırır
