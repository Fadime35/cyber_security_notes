## Snort Nedir?

Snort, açık kaynaklı bir IDS/IPS (saldırı tespit ve önleme sistemi) aracıdır. Ağ trafiğini analiz ederek zararlı aktiviteleri tespit eder ve kurallara göre
uyarı üretir veya trafiği engeller.

**Amaç**:

- Ağ trafiğini izlemek

- Saldırıları tespit etmek

- Güvenlik uyarıları üretmek

## Snort Nasıl Çalışır?

Snort, ağ üzerinden geçen paketleri analiz eder ve tanımlı kurallarla karşılaştırır.

**Genel mantık:**

Ağ trafiği → Paket analizi → Kural eşleşmesi → Alert / Engelleme

## Snort Çalışma Modları

### 1) Sniffer Mode

Ağ trafiğini sadece izler ve ekrana yazar.

**Amaç:** 

- Trafiği gözlemlemek

### 2) Packet Logger Mode

Ağ paketlerini kaydeder.

**Amaç:**

- Trafik kayıtlarını incelemek

### 3) NIDS Mode (Network IDS)

En yaygın kullanılan moddur.

**Amaç:**

- Trafiği analiz etmek

- Kurallara göre saldırı tespit etmek

- Alert üretmek

## Snort Kural Yapısı

Snort kuralları belirli bir formatta yazılır.

**Temel yapı:**

Action Protocol Source_IP Source_Port → Destination_IP Destination_Port (Options)

**Örnek Snort Kuralı** 

``` alert tcp any any -> 192.168.1.10 80 (msg:"HTTP saldırı denemesi"; sid:1001;) ```

**alert** → Alarm üret

**tcp** → TCP protokolü

**any any** → Herhangi bir IP ve port

**192.168.1.10 80** → Hedef IP ve port

**msg** → Alarm mesajı

**sid** → Kural ID

## Snort Kural Bileşenleri

### 1) Action

- Ne yapılacağını belirler (alert, log, drop)

### 2) Protocol

- TCP, UDP, ICMP

### 3) Source / Destination

- Kaynak ve hedef IP adresleri

### 4) Port

- Hangi portların kontrol edileceği

### 5) Options

- Detaylı kontrol ve mesaj bilgileri

## Snort Tespit Yöntemleri

### 1) Signature-Based

- Bilinen saldırı imzalarına göre çalışır.

**Örnek:**

- SQL Injection

- XSS saldırıları

### Anomaly-Based

- Normal dışı davranışları tespit eder.

## Snort Kullanım Alanları

- Ağ güvenliği

- Saldırı tespiti

- Trafik analizi

- Penetration test ortamları
