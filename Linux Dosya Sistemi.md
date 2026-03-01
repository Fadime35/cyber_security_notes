## Linux Dosya Sistemi

Linux’ta dosya sistemi hiyerarşik bir yapıdadır. Her şey root (/) dizininden başlar ve dallanan bir ağaç yapısı oluşturur.

### Önemli Dizinler

| Dizin   | Açıklama                                               |
| ------- | ------------------------------------------------------ |
| `/`     | Root dizini, tüm dosya sisteminin başlangıcı           |
| `/bin`  | Temel kullanıcı komutları (`ls`, `cp`, `mv`)           |
| `/sbin` | Sistem yönetimi için komutlar (`ifconfig`, `shutdown`) |
| `/home` | Kullanıcıların ev dizinleri (`/home/fadime`)           |
| `/root` | Root kullanıcısının ev dizini                          |
| `/etc`  | Sistem yapılandırma dosyaları (`passwd`, `hosts`)      |
| `/var`  | Değişken veriler (log dosyaları, mail, cache)          |
| `/tmp`  | Geçici dosyalar                                        |
| `/usr`  | Kullanıcı uygulamaları ve kütüphaneleri                |
| `/dev`  | Donanım cihazları (`/dev/sda`, `/dev/null`)            |
| `/proc` | Çalışan süreçler ve sistem bilgisi (`/proc/cpuinfo`)   |
| `/boot` | Önyükleme ile ilgili dosyalar (kernel, grub)           |


### Dosya Tipleri

**1. Düz dosya (Regular file)**

- Bunlar bildiğimiz normal dosyalardır.

- İçinde metin, resim, video veya herhangi bir veri olabilir.

**Örnek:** notlar.txt, resim.jpg, program.py

**2. Dizin (Directory)**

- Diğer dosyaları veya dizinleri içinde tutan klasörlerdir.

- Dizinler, dosyaları düzenlemek için kullanılır.

**Örnek:** Belgeler/, Müzikler/

**3. Sembolik link (Symbolic link)**

- Bir dosyaya veya dizine “kısayol” gibi işaret eder.

- Orijinal dosya silinirse link çalışmaz.

**Örnek:** Masaüstündeki bir dosya kısayolu.

**4. Cihaz dosyaları (Device files)**

- Bilgisayarın donanımını temsil eden dosyalardır.

- Örneğin klavye, fare, hard disk veya yazıcı gibi donanımlara erişim sağlar.

- Genellikle /dev dizininde bulunur.

**Örnek:** /dev/sda (hard disk), /dev/tty (terminal)

**5. Socket & Pipe**

- Bunlar programlar arasında veri iletmek için kullanılan “iletişim kanalları”dır.

- **Pipe (Borular):**  Aynı bilgisayardaki programlar arasında veri akışı sağlar.

**Örnek:** ls | grep "txt" komutu pipe kullanır.

- **Socket (Soketler):** Ağ üzerinden veya aynı makinede çalışan programlar arasında veri iletir.

**Örnek:** Web tarayıcı bir sunucuya bağlandığında socket kullanır.
