## Firewall Türleri

Firewall (güvenlik duvarı), ağ trafiğini kontrol ederek yetkisiz erişimleri engelleyen bir güvenlik sistemidir. Farklı çalışma mantıklarına göre çeşitli türleri
vardır.

### 1) Packet Filtering Firewall

En temel firewall türüdür.

**Nasıl çalışır:**

- Paketlerin başlık bilgilerini kontrol eder

- IP adresi, port ve protokole göre karar verir

**Özellik:**

- Hızlıdır

- Basit kurallar ile çalışır

- İçeriği analiz etmez

**Dezavantaj:**

- Gelişmiş saldırıları tespit edemez

### 2) Stateful Inspection Firewall

Bağlantı durumunu takip eden firewall türüdür.

**Nasıl çalışır:**

- Aktif bağlantıları izler

- Gelen paketin mevcut bir bağlantıya ait olup olmadığını kontrol eder

**Özellik:**

- Daha güvenlidir

- Dinamik karar verebilir

### 3) Stateless Firewall

Bağlantı durumunu takip etmez.

**Nasıl çalışır:**

- Her paketi bağımsız değerlendirir.

**Özellik:**

- Hızlıdır

- Daha az güvenlidir

**Not:**

Packet filtering firewall genellikle stateless olarak çalışır.

### 4) Proxy Firewall (Application Layer Firewall)

Uygulama katmanında çalışan firewall türüdür.

**Nasıl çalışır:**

- İstemci ile sunucu arasında aracı olur.

- Trafiği detaylı inceler.

**Özellik:**

- İçeriği analiz eder

- Daha güvenlidir

**Dezavantaj:**

- Performans düşebilir

### 5) Next Generation Firewall (NGFW)

Gelişmiş firewall türüdür.

**Nasıl çalışır:**

- Paket + içerik + uygulama analizi yapar.

**Özellik:**

- Deep Packet Inspection (DPI)

- Uygulama kontrolü

- IDS/IPS entegrasyonu

**Avantaj:**

- Modern saldırılara karşı güçlüdür

### 6) Web Application Firewall (WAF)

Web uygulamalarını korumak için kullanılan firewall türüdür.

**Nasıl çalışır:**

- HTTP/HTTPS trafiğini analiz eder

**Koruduğu saldırılar:**

- SQL Injection

- XSS

- CSRF

### 7) Hardware Firewall

Fiziksel cihaz olarak çalışan firewall’dur.

**Özellik:**

- Kurum ağlarında kullanılır

- Yüksek performans sağlar

### 8) Software Firewall

Yazılım olarak çalışan firewall’dur.

**Özellik:**

- Bilgisayara kurulur

- Bireysel kullanım için uygundur
