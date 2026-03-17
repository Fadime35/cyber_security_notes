## Proxy Nedir?

Proxy, istemci (client) ile sunucu (server) arasında aracı görevi gören bir sistemdir. Kullanıcı doğrudan hedef sunucuya bağlanmak yerine proxy üzerinden
iletişim kurar.

**Amaç:**

- Güvenliği artırmak

- Anonimlik sağlamak

- Trafiği kontrol etmek

- İçerik filtreleme yapmak

## Proxy Nasıl Çalışır?

**Genel mantık:**

İstemci → Proxy → Sunucu → Proxy → İstemci

- Kullanıcı isteği proxy’ye gönderir

- Proxy isteği hedef sunucuya iletir

- Sunucu cevabı proxy’ye gönderir

- Proxy cevabı kullanıcıya iletir

## Proxy Türleri

### 1) Forward Proxy

Kullanıcı tarafında bulunur.

**Özellik:**

- İstemci adına internete istek gönderir

- Kullanıcının IP adresini gizler

**Kullanım:**

- Kurum ağları

- İnternet erişim kontrolü

### 2) Reverse Proxy

Sunucu tarafında bulunur.

**Özellik:**

- Sunucuları gizler

- Gelen istekleri uygun sunucuya yönlendirir

**Kullanım:**

- Web siteleri

- Yük dengeleme (load balancing)

- Güvenlik

### 3) Transparent Proxy

Kullanıcı farkında olmadan çalışır.

**Özellik:**

- Ek ayar gerektirmez

- Trafiği otomatik yönlendirir

**Kullanım:**

- Okul / şirket ağları

### 4) Anonymous Proxy

Kullanıcının kimliğini gizler.

**Özellik:**

- IP adresini saklar

- Anonim erişim sağlar

### 5) High Anonymity Proxy (Elite Proxy)

En yüksek gizlilik seviyesini sağlar.

**Özellik:**

- Proxy kullanıldığı anlaşılmaz

- Maksimum anonimlik sağlar

## Proxy Kullanım Amaçları

- Güvenlik

- Zararlı sitelere erişimi engeller

- Anonimlik

- Kullanıcının IP adresini gizler

- Erişim kontrolü

- Belirli sitelere erişimi sınırlar

- Cache (önbellekleme)

- Sık kullanılan verileri saklayarak hız sağlar

## Proxy ve Firewall Farkı

### Proxy:

- Trafiği yönlendirir

- Uygulama katmanında çalışır

### Firewall:

- Trafiği kontrol eder

- İzin/ver engelle kararları verir
