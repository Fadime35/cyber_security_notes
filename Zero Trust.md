## Zero Trust

Zero Trust, hiçbir kullanıcıya veya cihaza varsayılan olarak güvenmeyen bir güvenlik modelidir. Sistem içinde veya dışında olsun, her erişim isteği doğrulanmalıdır.

Temel prensip:
**Asla güvenme, her zaman doğrula.**

Geleneksel güvenlik modelinde, ağ içine giren kullanıcıya güvenilir kabul edilir. Zero Trust modelinde ise ağ içinde olsa bile her erişim tekrar doğrulanır.

## Zero Trust Temel İlkeleri

### 1) Verify Explicitly (Her erişimi doğrula)

Her kullanıcı ve cihaz erişim isteği sırasında doğrulanır.

**Kontrol edilen bilgiler:**

- Kullanıcı kimliği

- Cihaz güvenliği

- Konum bilgisi

- Erişim zamanı

- Risk seviyesi

**Amaç:** Yetkisiz erişimleri engellemek.

### 2) Least Privilege Access (En Az Yetki Prensibi)

Kullanıcılara sadece işlerini yapmaları için gerekli minimum yetki verilir.

**Örnek:**

- Bir çalışan sadece kendi departmanına ait verilere erişebilir.

- Admin yetkileri sınırlı tutulur.

**Amaç:** Olası bir saldırının etkisini azaltmak.

### 3) Assume Breach (İhlal Olmuş Gibi Davran)

Sistem içinde saldırgan olabileceği varsayılır.

**Bu nedenle:**

- Ağ sürekli izlenir

- Anormal davranışlar tespit edilir

- Erişimler sürekli kontrol edilir

**Amaç:** Saldırıyı erken tespit etmek.


## Zero Trust Nasıl Uygulanır?

Zero Trust modelinde çeşitli güvenlik mekanizmaları kullanılır:

**Kimlik doğrulama:**

- Çok faktörlü kimlik doğrulama (MFA)

**Erişim kontrolü:**

- Rol tabanlı erişim kontrolü (RBAC)

**Ağ güvenliği:**

- Mikro segmentasyon

**Cihaz güvenliği:**

- Endpoint güvenlik kontrolleri

**İzleme:**

- Sürekli log ve trafik analizi

## Geleneksel Güvenlik Modeli vs Zero Trust

**Geleneksel Model:**

- Ağ içi güvenilir kabul edilir

- Güvenlik sınırı firewall’dır

**Zero Trust Model:**

- Ağ içi ve dışı ayrımı yoktur

- Her erişim doğrulanır

- Sürekli izleme yapılır

