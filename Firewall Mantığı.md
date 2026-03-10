## Firewall Mantığı

Firewall, bir ağ ile başka bir ağ arasındaki trafiği kontrol eden güvenlik sistemidir. Gelen ve giden ağ trafiğini belirlenen güvenlik kurallarına göre 
izin verir veya engeller.

**Temel amaç:**

- Yetkisiz erişimi engellemek

- Ağı dış tehditlerden korumak

- Ağ trafiğini kontrol etmek

Firewall genellikle **internet ile iç ağ arasında** bulunur.

### Firewall Nasıl Çalışır?

Firewall, ağ üzerinden geçen veri paketlerini kontrol eder ve kurallara göre karar verir.

**Kontrol edilen bilgiler:**

- Kaynak IP adresi

- Hedef IP adresi

- Port numarası

- Protokol (TCP, UDP, ICMP)

- Paket içeriği (bazı firewall türlerinde)

**Bu bilgilere bakarak trafik için şu kararlardan biri verilir:**

- Allow (İzin ver)

- Deny / Block (Engelle)

## Firewall Kuralları (Rules)

Firewall belirli kurallara göre çalışır. Bu kurallar sistem yöneticisi tarafından belirlenir.

**Örnek kural:**

**Kaynak IP:** Herhangi biri
**Hedef IP:** Web sunucusu
**Port:** 80 (HTTP)
**İşlem:** Allow

Bu kural web trafiğine izin verir.

**Başka bir örnek:**

**Kaynak IP:** İnternet
**Hedef Port:** 22 (SSH)
**İşlem:** Deny

Bu kural dışarıdan SSH erişimini engeller.

## Firewall Türleri

### Packet Filtering Firewall

En temel firewall türüdür.

Veri paketlerini IP, port ve protokol bilgisine göre kontrol eder.

**Özellik:**

- Hızlıdır

- Paket içeriğini incelemez

### Stateful Inspection Firewall

Bağlantı durumunu takip eder.

**Özellik:**

- Bağlantının başlangıcını ve devamını izler

- Daha güvenlidir

**Örnek:**

Bir bağlantı içeriden başlatıldıysa dönüş paketlerine izin verir.

### Application Layer Firewall

Uygulama seviyesinde kontrol yapar.

**Örnek:**

- HTTP

- FTP

- DNS trafiği

**Özellik:**

- Trafiğin içeriğini analiz eder

- Daha detaylı güvenlik sağlar

### Next Generation Firewall (NGFW)

Modern firewall türüdür.

**Özellikleri:**

- Deep packet inspection

- Uygulama kontrolü

- IDS / IPS entegrasyonu

- Malware tespiti

## Firewall Nerelerde Kullanılır?

- Kurumsal ağlarda

- Veri merkezlerinde

- Ev ağlarında

- Bulut ortamlarında

Firewall hem donanım cihazı hem de yazılım olarak kullanılabilir.
