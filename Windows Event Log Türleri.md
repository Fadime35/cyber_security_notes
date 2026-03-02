## Windows Event Log Türleri

Windows işletim sisteminde tüm sistem, uygulama ve güvenlik olayları Event Log’larda (Olay Günlükleri) kaydedilir. Bu loglar, sistemin durumu, hatalar, kullanıcı
hareketleri ve güvenlik olayları hakkında bilgi verir.

### 1. Application Log (Uygulama Günlüğü)

**Ne için kullanılır?**

Uygulama kaynaklı hatalar ve olaylar için tutulur.

**Kaynak:** Windows uygulamaları ve yazılımlar (ör. Microsoft Office, SQL Server, özel uygulamalar)

**Örnek olaylar:**

- Programın çökmesi

- Yazılım hatası

- Uygulama başlatma veya durdurma

**Önem:** SOC analistleri genellikle uygulama hatalarını ve anormal uygulama davranışlarını tespit etmek için kullanır.

### 2. System Log (Sistem Günlüğü)

**Ne için kullanılır?**

Windows işletim sistemi bileşenlerinden gelen olayları kaydeder.

**Kaynak:** Windows servisleri ve işletim sistemi bileşenleri

**Örnek olaylar:**

- Sürücü hataları

- Servis durması veya başlatılması

- Donanım hataları

**Önem:** Sistem sorunlarını ve olası güvenlik zafiyetlerini tespit etmek için kritik loglar içerir.

### 3. Security Log (Güvenlik Günlüğü)

**Ne için kullanılır?**

- Kullanıcı ve güvenlik ile ilgili olayları kaydeder.

**Kaynak:** Windows güvenlik denetimleri (Audit)

**Örnek olaylar:**

- Başarılı veya başarısız oturum açma

- Dosya erişim izinleri ihlalleri

- Hesap değişiklikleri (parola değişimi, hesap kilitleme)

**Önem:** SOC ve siber güvenlik analistleri için en kritik loglardan biridir. Yetkisiz erişim ve saldırı tespiti burada görülür.

### 4. Setup Log (Kurulum Günlüğü)

**Ne için kullanılır?**

- Windows kurulumu ve güncellemeleri sırasında oluşan olayları kaydeder.

**Kaynak:** Windows kurulum ve güncelleme süreçleri

**Örnek olaylar:**

- Windows güncellemeleri

- Yazılım kurulumu

**Önem:** Sistem yapılandırması ve güncellemelerin doğruluğunu kontrol etmek için kullanılır.

### 5. Forwarded Events (İletilen Olaylar)

**Ne için kullanılır?**

- Ağdaki diğer Windows makinelerinden iletilen olayları toplar.

**Kaynak:** Diğer bilgisayarlar veya sunucular

**Örnek olaylar:**

- Merkezi log toplama

- Ağ üzerinde toplu analiz

**Önem:** Büyük ağlarda merkezi log yönetimi ve SOC için çok kullanışlıdır.
