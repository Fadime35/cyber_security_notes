## OSI Modeli (Open Systems Interconnection)

- OSI modeli, ağ iletişimini 7 katman halinde açıklayan teorik bir modeldir. Her katman farklı bir görev üstlenir.

**Amaç:** Ağdaki verinin nasıl iletildiğini ve hangi katmanın hangi işlevi yaptığını net olarak göstermek.

## Katmanlar:

### 1.Physical (Fiziksel Katman)

**İşlev:** Veri iletimini fiziksel olarak gerçekleştirir. Sinyaller, kablolar, fiber optik, Wi-Fi, donanım bağlantıları bu katmanda bulunur.

**Örnek:** Ethernet kablosu üzerinden veri akışı, elektrik sinyalleri veya radyo dalgaları.

### 2.Data Link (Veri Bağlantı Katmanı)

**İşlev:** Veriyi paketler hâline getirir, hata kontrolü yapar, cihazları MAC adresi ile tanır.

**Örnek:** Switch cihazı, ağ kartı. Paket kaybı veya hatalı veri tespit edilir ve düzeltilir.

### 3.Network (Ağ Katmanı)

**İşlev:** Veriyi bir ağdan diğerine yönlendirir, IP adreslerini kullanır.

**Örnek:** Router cihazı IP adresine göre veri paketlerini doğru ağa iletir.

**Protokoller:** IP (IPv4/IPv6), ICMP

### 4.Transport (Taşıma Katmanı)

**İşlev:** Verinin doğru şekilde ve bütün olarak ulaşmasını sağlar. Paketleri sıralar ve kaybolan paketleri tekrar ister.

**Örnek:** Web tarayıcınız bir web sitesini açarken TCP kullanır.

**Protokoller:** TCP (güvenilir veri iletimi), UDP (daha hızlı ama kontrolsüz)

### 5.Session (Oturum Katmanı)

**İşlev:** İki cihaz arasındaki oturum ve bağlantıyı yönetir.

**Örnek:** Bir sunucuya bağlandığınızda oturum başlatılır ve bitene kadar devam eder.

### 6.Presentation (Sunum Katmanı)

**İşlev:** Verinin formatlanması, şifrelenmesi veya sıkıştırılması ile ilgilenir.

**Örnek:** Web sayfasındaki HTML verisinin tarayıcıda görüntülenmesi, HTTPS şifreleme işlemi.

### 7.Application (Uygulama Katmanı)

**İşlev:** Kullanıcının doğrudan etkileşimde bulunduğu katmandır. Uygulamalar bu katmanda çalışır.

**Örnek:** Web tarayıcısı, e-posta istemcisi.

**Protokoller:** HTTP, HTTPS, FTP, SMTP, DNS
