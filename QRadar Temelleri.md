## QRadar Temelleri

QRadar, güvenlik loglarını ve ağ trafiğini analiz ederek siber saldırıları tespit eden bir SIEM platformudur. Kurumlardaki farklı sistemlerden gelen verileri 
analiz ederek güvenlik olaylarını belirler.

**Amaç:**

- Güvenlik loglarını merkezi olarak toplamak

- Saldırıları tespit etmek

- Güvenlik olaylarını analiz etmek

- SOC ekiplerine uyarı üretmek

## QRadar Nasıl Çalışır?

Bir kurumda birçok cihaz log üretir.

**Örnek veri kaynakları:**

- Firewall

- Sunucular

- Router / Switch

- IDS / IPS

- Endpoint sistemleri

- Web sunucuları

- Veritabanları

QRadar bu verileri toplar, analiz eder ve şüpheli aktiviteleri tespit eder.

## QRadar Temel Kavramları

### Event

Log kaynaklarından gelen olay kayıtlarıdır.

**Örnek:**

- Login işlemleri

- Firewall bağlantıları

- Sistem hataları

### Flow

Ağ trafiği ile ilgili bilgilerdir.

**İçerdiği bilgiler:**

- Kaynak IP

- Hedef IP

- Port

- Protokol

- Veri miktarı

Flow verileri ağ davranışını analiz etmek için kullanılır.

### Offense

QRadar tarafından tespit edilen güvenlik olaylarıdır.

Bir saldırı veya şüpheli durum oluştuğunda QRadar bir offense oluşturur.

**Örnek:**

- Brute force saldırısı

- Port scanning

- Malware iletişimi

## QRadar Bileşenleri

### Event Collector

Logları toplar.

**Görevleri:**

- Log verilerini almak

- QRadar sistemine iletmek

### Event Processor

Log verilerini analiz eder.

**Görevleri:**

-  Logları işlemek

- Korelasyon kurallarını çalıştırmak

### Flow Collector

Ağ trafiği verilerini toplar.

**Görevleri:** 

- Flow verilerini almak

- Trafik analizine göndermek

### Console

QRadar’ın yönetim arayüzüdür.

**Buradan:**

- Offense görüntülenir

- Log araması yapılır

- Kurallar yönetilir

- Raporlar oluşturulur

## QRadar Korelasyon Mantığı

QRadar farklı logları ilişkilendirerek saldırıları tespit eder.

**Örnek:**

- Bir IP çok sayıda login denemesi yapıyor

- Aynı IP daha sonra sisteme giriş yapıyor

QRadar bu iki olayı birleştirerek saldırı tespit edebilir.

## QRadar’da Kullanılan Temel Kavramlar

**Log Source**

Log gönderen cihaz

**Rule**

Saldırı tespit kuralları

**Offense**

Tespit edilen güvenlik olayı

**Magnitude**

Olayın risk seviyesi

## SOC Analisti QRadar ile Ne Yapar?

SOC analistleri QRadar üzerinde şu işlemleri yapar:

- Offense inceleme

- Log analizi

- Ağ trafiği inceleme

- Saldırı araştırması

- Olay müdahalesi
