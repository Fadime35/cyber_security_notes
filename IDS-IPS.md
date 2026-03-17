## IDS / IPS (Intrusion Detection / Prevention System)

IDS ve IPS, ağ ve sistemlerdeki zararlı aktiviteleri tespit etmek ve engellemek için kullanılan güvenlik sistemleridir.

**IDS:** Intrusion Detection System (Saldırı Tespit Sistemi)

**IPS:** Intrusion Prevention System (Saldırı Önleme Sistemi)

**Amaç:**

- Saldırıları tespit etmek

- Yetkisiz erişimleri belirlemek

- Sistemi korumak

### IDS (Intrusion Detection System)

IDS, ağ trafiğini veya sistem aktivitelerini izler ve şüpheli durumları tespit eder, ancak doğrudan müdahale etmez.

**Özellik:** 

- Sadece izler ve alert üretir

- Trafiği engellemez

**Nasıl çalışır:**

- Logları ve ağ trafiğini analiz eder

- Şüpheli bir durum varsa alarm oluşturur

**Örnek:**

Bir IP sürekli port taraması yapıyorsa IDS bunu tespit eder ve uyarı verir.

### IPS (Intrusion Prevention System)

IPS, IDS’den farklı olarak saldırıları sadece tespit etmekle kalmaz, aynı zamanda engeller.

**Özellik:**

- Aktif koruma sağlar

- Trafiği bloklayabilir

**Nasıl çalışır:**

- Şüpheli trafik tespit edildiğinde bağlantıyı keser veya engeller

**Örnek:**

Bir saldırgan SQL Injection denemesi yaparsa IPS bu isteği engelleyebilir.

##  IDS vs IPS Farkı

### IDS:

- Pasif sistem

- Sadece uyarı verir

- Trafiği engellemez

### IPS:

- Aktif sistem

- Saldırıyı engeller

- Trafiğe müdahale eder

##  IDS / IPS Türleri

### 1) Network-Based (NIDS / NIPS)

Ağ trafiğini analiz eder.

**Örnek:**

- Tüm ağdaki veri paketlerini inceler

### 2) Host-Based (HIDS / HIPS)

Tek bir cihaz üzerinde çalışır.

**Örnek:**

- Dosya değişikliklerini izler

- Sistem aktivitelerini kontrol eder

## Tespit Yöntemleri

### 1) Signature-Based Detection

- Bilinen saldırı imzalarına göre çalışır.

**Özellik:**

- Hızlıdır

- Bilinen saldırıları yakalar

- Yeni saldırıları kaçırabilir

### 2) Anomaly-Based Detection

- Normal davranışı öğrenir ve anormal aktiviteleri tespit eder.

**Özellik:**

- Yeni saldırıları yakalayabilir

- False positive oranı yüksek olabilir
