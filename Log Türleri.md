## Log Türleri

Log, bir sistemde gerçekleşen olayların kaydedildiği kayıt dosyalarıdır. Sistemler, ağ cihazları ve uygulamalar yapılan işlemleri log olarak saklar. Bu kayıtlar 
güvenlik analizi, hata tespiti ve olay inceleme için kullanılır.

**Amaç:**

- Sistem aktivitelerini izlemek

- Güvenlik olaylarını tespit etmek

- Olay incelemesi (incident response) yapmak

### 1) System Logs (Sistem Logları)

İşletim sistemi tarafından oluşturulan loglardır.

**İçerdiği bilgiler:**

- Sistem başlatma ve kapanma

- Donanım hataları

- Servis çalışmaları

- Sistem değişiklikleri

**Örnek:**

Sunucunun yeniden başlatılması sistem loglarında görülür.

### 2) Authentication Logs (Kimlik Doğrulama Logları)

Kullanıcıların giriş ve çıkış işlemlerini kaydeder.

**İçerdiği bilgiler:**

- Login denemeleri

- Başarılı girişler

- Başarısız girişler

- Yetki yükseltme işlemleri

**Örnek:**

Bir kullanıcının yanlış şifre ile birçok kez giriş denemesi.

### 3) Network Logs (Ağ Logları)

Ağ cihazları tarafından oluşturulan loglardır.

**İçerdiği bilgiler:**

- IP adresleri

- Port numaraları

- Ağ trafiği

- Bağlantı denemeleri

**Kaynaklar:**

- Firewall

- Router

- Switch

### 4) Firewall Logs

Firewall tarafından kaydedilen ağ trafiği loglarıdır.

**İçerdiği bilgiler:**

- Engellenen bağlantılar

- İzin verilen trafik

- Kaynak ve hedef IP

- Kullanılan port

**Örnek:**

Bir IP adresinin sürekli kapalı portlara erişmeye çalışması.

### 5) Application Logs (Uygulama Logları)

Bir uygulama tarafından oluşturulan loglardır.

**İçerdiği bilgiler:**

- Uygulama hataları

- Kullanıcı işlemleri

- Veri erişimleri

**Örnek:**

Bir kullanıcının web uygulamasında yaptığı işlem.

### 6) Security Logs

Güvenlikle ilgili olayları kaydeder.

**İçerdiği bilgiler:**

- Yetkisiz erişim girişimleri

- Güvenlik politikası ihlalleri

- Hesap kilitlenmeleri

Bu loglar güvenlik analizi için çok önemlidir.

### 7) Web Server Logs

Web sunucularının tuttuğu loglardır.

**İçerdiği bilgiler:**

- Ziyaret edilen sayfalar

- Kullanıcı IP adresleri

- HTTP istekleri

- Hata kodları

**Örnek log bilgileri:**

- GET /index.html

- HTTP 404 hata kodu

### 8) Database Logs

Veritabanında yapılan işlemleri kaydeder.

**İçerdiği bilgiler:**

- SQL sorguları

- Veri ekleme / silme işlemleri

- Yetkisiz erişim denemeleri

**Örnek:**

Bir kullanıcının veritabanından veri çekmesi.

### 9) IDS / IPS Logs

Saldırı tespit sistemleri tarafından oluşturulan loglardır.

**İçerdiği bilgiler:**

- Tespit edilen saldırılar

- Zararlı trafik

- Şüpheli aktiviteler

**Örnek:**

SQL Injection saldırı denemesi.

---

### SOC Analisti Açısından Önemi

SOC analistleri logları inceleyerek şunları tespit eder:

- Brute force saldırıları

- Port taramaları

- Şüpheli kullanıcı aktiviteleri

- Malware iletişimi

- Veri sızıntısı

Log analizi, güvenlik operasyonlarının en önemli parçalarından biridir.


