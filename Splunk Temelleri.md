## Splunk Temelleri

Splunk, log verilerini toplamak, analiz etmek ve görselleştirmek için kullanılan bir veri analiz ve SIEM platformudur. Özellikle siber güvenlik, sistem yönetimi 
ve operasyon takibi için kullanılır.

**Amaç:**

- Log verilerini merkezi bir yerde toplamak

- Büyük veri setlerini hızlı şekilde analiz etmek

- Güvenlik olaylarını tespit etmek

- Dashboard ve raporlar oluşturmak

## Splunk Nasıl Çalışır?

Splunk birçok kaynaktan veri toplar ve bu verileri arama yapılabilir hale getirir.

**Veri kaynakları:**

- Sunucu logları

- Firewall logları

- Web server logları

- Uygulama logları

- Ağ cihazları

- Veritabanı logları

Bu veriler Splunk içinde indekslenir ve arama yapılabilir hale gelir.

## Splunk Temel Bileşenleri

### 1) Forwarder

Log verilerini Splunk sunucusuna gönderen ajan yazılımdır.

**Görevleri:**

- Logları toplamak

- Splunk sunucusuna göndermek

**İki türü vardır:**

**Universal Forwarder**
  
Hafif ve en çok kullanılan forwarder türüdür.

**Heavy Forwarder**

Veriyi ön işleme tabi tutabilir.

### 2) Indexer

Toplanan verileri depolayan ve indeksleyen bileşendir.

**Görevleri:**

- Logları saklamak

- Veriyi indekslemek

- Arama yapılmasını sağlamak

### 3) Search Head

Kullanıcıların Splunk üzerinde arama yaptığı arayüzdür.

**Görevleri:**

- Log sorguları çalıştırmak

- Dashboard oluşturmak

- Rapor üretmek

## Splunk Veri Yapısı

Splunk verileri belirli alanlara ayırarak saklar.

**Host**

Logun geldiği cihaz

**Source**

Log dosyasının kaynağı

**Source Type**

Log formatı

**Index**

Verinin depolandığı yer

## Splunk Arama Dili (SPL)

Splunk’ta logları analiz etmek için SPL (Search Processing Language) kullanılır.

```index=firewall```

**Firewall loglarını getirir.**


```index=auth failed```

**Başarısız giriş denemelerini gösterir.**

## Splunk Kullanım Alanları

**Güvenlik analizi**

Saldırı tespiti

**Log yönetimi**

Sistem loglarının analizi

**Operasyon izleme**

Sunucu performans takibi

**Uygulama analizi**

Uygulama hatalarının incelenmesi

## SOC Analisti Splunk ile Ne Yapar?

**SOC analistleri Splunk üzerinde şu işlemleri yapar:**

- Log arama

- Alert inceleme

- Saldırı analizi

- Dashboard izleme

- Olay araştırması (investigation)

**Örnek analizler:**

- Brute force saldırısı

- Şüpheli IP bağlantıları

- Malware iletişimi

- Yetkisiz erişim
