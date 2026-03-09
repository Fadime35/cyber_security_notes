## OWASP Top 10

OWASP Top 10, web uygulamalarında en kritik ve en yaygın görülen güvenlik açıklarını listeleyen bir güvenlik standardıdır. Web geliştiriciler ve güvenlik uzmanları
bu listeyi uygulama güvenliğini artırmak için kullanır.

Liste, **OWASP (Open Web Application Security Project)** tarafından hazırlanır ve belirli aralıklarla güncellenir.

**Amaç:**

- Web uygulamalarındaki en önemli güvenlik risklerini belirlemek

- Geliştiricilere güvenlik rehberi sunmak

- Güvenli yazılım geliştirmeyi teşvik etmek

## OWASP Top 10 (2021)

### 1) Broken Access Control (Erişim Kontrolü Hataları)

Kullanıcıların yetkisi olmayan verilere veya işlemlere erişebilmesidir.

**Örnek:**

- Normal kullanıcının admin sayfasına erişebilmesi

- Başka bir kullanıcının verisini görüntüleyebilmek

### 2) Cryptographic Failures (Kriptografik Hatalar)

Hassas verilerin yeterince güçlü şekilde korunmamasıdır.

**Örnek:**

- Parolaların düz metin olarak saklanması

- Şifreleme kullanılmaması

- Zayıf şifreleme algoritmaları

### 3) Injection

Kötü amaçlı kodların uygulamaya gönderilmesiyle gerçekleşir.

**En yaygın tür:**

- SQL Injection

**Örnek:**

- Saldırgan veritabanına komut göndererek veri okuyabilir veya değiştirebilir.

### 4) Insecure Design (Güvensiz Tasarım)

Uygulamanın güvenlik düşünülmeden tasarlanmasıdır.

**Örnek:**

- Rate limit olmaması

- Güvenlik kontrollerinin eksik olması

### 5) Security Misconfiguration (Yanlış Güvenlik Yapılandırması)

Sistem veya uygulamanın yanlış yapılandırılmasıdır.

**Örnek:**

- Varsayılan şifrelerin değiştirilmemesi

- Gereksiz servislerin açık olması

- Debug modunun açık kalması

### 6) Vulnerable and Outdated Components

Eski ve güvenlik açığı olan yazılım bileşenlerinin kullanılmasıdır.

**Örnek:**

- Güncellenmemiş framework

- Eski kütüphaneler

### 7) Identification and Authentication Failures

Kimlik doğrulama ve oturum yönetimi hatalarıdır.

**Örnek:**

- Zayıf parola politikası

- Oturum süresinin kontrol edilmemesi

- MFA kullanılmaması

### 8) Software and Data Integrity Failures

Yazılım ve veri bütünlüğünün korunamamasıdır.

**Örnek:**

- Güvenilmeyen güncellemeler

- İmzalanmamış yazılım paketleri

### 9) Security Logging and Monitoring Failures

Güvenlik olaylarının yeterince kaydedilmemesi veya izlenmemesidir.

**Örnek:**

- Log tutulmaması

- Şüpheli aktivitelerin tespit edilememesi

### 10) Server-Side Request Forgery (SSRF)

Sunucunun saldırgan tarafından başka sistemlere istek göndermeye zorlanmasıdır.

**Örnek:**

- İç ağdaki servislere erişim sağlamak

- Gizli verilere ulaşmak

