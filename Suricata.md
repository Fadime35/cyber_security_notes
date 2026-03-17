## Suricata Nedir?

Suricata, açık kaynaklı bir IDS/IPS ve ağ güvenliği izleme aracıdır. Ağ trafiğini analiz ederek saldırıları tespit eder ve gerekirse engeller.

**Amaç:**

- Ağ trafiğini izlemek

- Saldırıları tespit etmek

- Güvenlik uyarıları üretmek

- Gelişmiş analiz yapmak

## Suricata Nasıl Çalışır?

Suricata, ağ üzerinden geçen paketleri analiz eder ve kurallar ile karşılaştırır.

**Genel mantık:**

- Ağ trafiği → Paket analizi → Kural eşleşmesi → Alert / Engelleme

- Snort’a benzer şekilde çalışır ancak daha gelişmiş özelliklere sahiptir.

## Suricata Özellikleri

- Çok çekirdek (multi-thread) desteği

- Yüksek performans

- Gerçek zamanlı analiz

- Protokol farkındalığı (HTTP, DNS, TLS vb.)

- Hem IDS hem IPS olarak çalışabilir

## Çalışma Modları

### 1) IDS Mode

Saldırıları tespit eder ve alert üretir.

**Özellik:**

- Trafiği engellemez

- Pasif izleme yapar

### 2) IPS Mode

Saldırıları tespit eder ve engeller.

**Özellik:**

- Trafiğe müdahale eder

- Zararlı paketleri düşürür (drop)

## Suricata Kural Yapısı

Suricata, Snort ile benzer kural yapısını kullanır.

**Temel yapı:**

Action Protocol Source_IP Source_Port → Destination_IP Destination_Port (Options) 

**Örnek Suricata Kuralı**

``` alert http any any -> any any (msg:"Şüpheli HTTP isteği"; sid:1002;) ``` 

**alert** → Alarm üret

**http** → HTTP trafiği

**any any** → Herhangi kaynak

**any any** → Herhangi hedef

**msg** → Alarm mesajı

**sid** → Kural ID

## Suricata Tespit Yöntemleri

### 1) Signature-Based Detection

- Bilinen saldırı imzalarına göre çalışır.

### 2) Anomaly-Based Detection

- Normal dışı davranışları tespit eder.

## Suricata vs Snort

### Suricata:

- Daha hızlı (multi-thread)

- Daha fazla protokol analizi

- Modern mimari

### Snort:

- Daha eski ve yaygın

- Daha fazla dokümantasyon
  

