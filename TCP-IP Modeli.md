## TCP/IP Modeli

- TCP/IP modeli, OSI’ye göre daha pratik ve yaygın olarak kullanılan 4 katmanlı bir modeldir.

- OSI’nin 7 katmanı TCP/IP’de 4 katmanda birleştirilmiştir.

## Katmanlar:

### 1.Network Interface (Link)

- OSI’nin Physical + Data Link katmanlarını kapsar.

**İşlev:** Donanım bağlantısı, MAC adresi ve veri iletimi.

**Örnek:** Ethernet, Wi-Fi, ağ kartı

### 2.Internet

- OSI’nin Network katmanına denk gelir.

**İşlev:** IP adresleme ve paketlerin doğru hedefe yönlendirilmesi.

**Protokoller:** IPv4, IPv6, ICMP

**Örnek:** Router’lar arası veri iletimi

### 3.Transport

- OSI’nin Transport katmanına denk gelir.

**İşlev:** Verinin güvenli iletimi, paketlerin sıralanması, kaybolan paketlerin tekrar gönderilmesi.

**Protokoller:** TCP (güvenli), UDP (hızlı)

**Örnek:** Web tarayıcısı TCP ile veri alır, DNS sorguları UDP ile yapılabilir.

### 4.Application

- OSI’nin Session + Presentation + Application katmanlarını kapsar.

**İşlev:** Kullanıcı uygulamaları için veri iletimi ve protokoller.

**Protokoller:** HTTP, HTTPS, FTP, DNS, SMTP

**Örnek:** Web tarayıcınız HTTP/HTTPS ile sunucudan veri çeker, e-posta istemcisi SMTP ile mesaj gönderir.
