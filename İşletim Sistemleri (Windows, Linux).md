## İşletim Sistemi Nedir?

İşletim sistemi (Operating System – OS), bilgisayar donanımı ile kullanıcı ve yazılım arasında köprü görevi gören yazılımdır.

**İşlevleri:**

- Donanımı yönetmek

- Yazılımların çalışmasını sağlamak

- Kullanıcıya arayüz sunmak

- Dosya ve veri yönetimi yapmak

## İşletim Sistemi Bileşenleri

### 1. Çekirdek (Kernel)

- OS’in merkezi parçasıdır.

**İşlevleri:**

- İşlemci ve bellek yönetimi

- Donanım aygıtları ile iletişim

- İşlem yönetimi (process scheduling)

**Çekirdek türleri:**

- Monolitik Kernel: Tek parça, yüksek performans (Linux)

- Mikro Kernel: Minimal ve modüler (bazı Linux dağıtımları, özel OS’ler)

### 2. Dosya Sistemi

- Verilerin diskte düzenli şekilde saklanmasını sağlar.

**Örnekler:**

- **Windows:** NTFS, FAT32

- **Linux:** ext4, XFS, Btrfs

**İşlevleri:**

- Dosya oluşturma, silme, kopyalama

- İzin ve güvenlik yönetimi

### 3. İşlem Yönetimi

- Bilgisayarda çalışan tüm programların CPU zamanını ve kaynak kullanımını yönetir.

**İşlevleri:**

- Çoklu görev (Multitasking) sağlar.

- İşlem önceliklerini belirler.

- İşlem durumlarını (çalışıyor, beklemede, durdu) takip eder.

### 4. Bellek Yönetimi

- RAM’in verimli kullanımını sağlar.

**İşlevleri:**

- Boş alanları takip eder.

- Programlara gerekli RAM’i tahsis eder.

- Sanal bellek (virtual memory) kullanarak RAM yetersizse disk alanını geçici bellek olarak kullanır.

### 5. Aygıt ve Sürücü Yönetimi

- Donanım bileşenlerinin OS ile iletişimini sağlar.

**Örnekler:**

- Yazıcı, fare, ekran kartı sürücüleri

**İşlev:**

- Donanım ile programlar arasında veri aktarımı

### 6. Kullanıcı Arayüzü (UI)

- Kullanıcının OS ile etkileşim kurmasını sağlar.

**Türleri:**

- **GUI (Graphical User Interface):** Windows, Ubuntu (masaüstü ikon ve pencereler)

- **CLI (Command Line Interface):** Linux terminal, PowerShell

## Windows İşletim Sistemi

- Microsoft tarafından geliştirilmiştir.

- Yaygın sürümleri: Windows 10, Windows 11

**Özellikler:**

- GUI odaklı, kullanıcı dostu

- Yazılım uyumluluğu yüksek

- Dosya sistemi NTFS

**Kullanım alanları:**

- Ofis, oyun, yazılım geliştirme, günlük kullanım

## Linux İşletim Sistemi

- Açık kaynak kodludur, ücretsizdir.

- Dağıtımları (distribution) vardır: Ubuntu, Debian, Fedora, CentOS

**Özellikler:**

- Stabil ve güvenli

- Sunucularda yaygın kullanılır

- Dosya sistemi: ext4, XFS

- CLI odaklı kullanım imkanı

**Kullanım alanları:**

- Sunucular, ağ yönetimi, yazılım geliştirme, siber güvenlik


## Windows ve Linux Karşılaştırması

| Özellik            | Windows        | Linux                         |
| ------------------ | -------------- | ----------------------------- |
| Lisans             | Ücretli        | Açık kaynak, ücretsiz         |
| Arayüz             | GUI odaklı     | GUI ve CLI destekli           |
| Güvenlik           | Orta           | Yüksek                        |
| Yazılım Uyumluluğu | Çok yüksek     | Orta, bazı yazılımlar sınırlı |
| Kullanım Alanı     | Masaüstü, oyun | Sunucu, ağ, geliştirme        |

