## Temel Ağ Protokolleri

### 1. IP (Internet Protocol)

- Cihazlar arasında veri paketlerinin iletilmesini sağlar.

- Bağlantısız çalışır.

- Her pakette kaynak ve hedef IP bulunur.
  
**Sürümler:** IPv4 (32-bit), IPv6 (128-bit)
**Port:** Yok (katman 3 protokolü)

---

### 2. TCP (Transmission Control Protocol)

- Bağlantı odaklıdır.

- 3-way handshake ile bağlantı kurar.

- Güvenilir veri iletimi sağlar, paket sırasını korur ve hata kontrolü yapar.

**Kullanıldığı servisler:** HTTP (80), HTTPS (443), FTP (21), SMTP (25)

---

### 3. UDP (User Datagram Protocol)

- Bağlantısızdır.

- Hızlıdır, paket sırası veya güvenilirlik garanti edilmez.

**Kullanıldığı servisler:** DNS (53), VoIP (5060), Online oyunlar (değişken)

---

### 4. ICMP (Internet Control Message Protocol)

- Ağ hata mesajları ve durum kontrolü için kullanılır.

- Ping ve traceroute komutları ICMP kullanır.

- SOC açısından aşırı ICMP trafiği saldırı göstergesi olabilir.

**Port:** Yok (katman 3 protokolü)

---

### 5. ARP (Address Resolution Protocol)

- IP adreslerini fiziksel MAC adreslerine çevirir.

- Yerel ağ içi iletişimde kullanılır.

- Bağlantısız ve hızlıdır, ARP spoofing gibi saldırılara açık olabilir.

**Port:** Yok (katman 2 protokolü)

---

### 6. DHCP (Dynamic Host Configuration Protocol)

- Ağ cihazlarına otomatik olarak IP, subnet ve gateway atar.

- Ağ yönetimini kolaylaştırır.

**Port:** 67 (sunucu), 68 (istemci)

---

### 7. DNS (Domain Name System)

- Alan adlarını IP adreslerine çevirir.

- İnternetin “telefon rehberi” görevini görür.

- DNS spoofing ve DDoS saldırılarına hedef olabilir.

**Port:** 53 (TCP/UDP)

---

### 8. HTTP (Hypertext Transfer Protocol)

- Web sayfalarının istemci ve sunucu arasında iletilmesini sağlar.

**Port:** 80 (TCP)

---

### 9. HTTPS (Hypertext Transfer Protocol Secure)

- HTTP’nin şifreli versiyonudur.

- TLS/SSL ile veri güvenliği sağlar.

**Port:** 443 (TCP)

---

### 10. FTP (File Transfer Protocol)

- Dosya transferi için kullanılır.

- TCP tabanlıdır, şifreleme yok.

- Güvenli versiyonları: SFTP, FTPS

**Port:** 21 (TCP)

---

### 11. SMTP (Simple Mail Transfer Protocol)

- E-posta iletimi için kullanılır.

- TCP tabanlıdır.

**Port:** 25, 587 (TCP)

---

### 12. POP3 (Post Office Protocol 3)

- E-postaları sunucudan indirip lokal cihaza kaydeder.

- Sunucuda genellikle posta saklamaz.

**Port:** 110 (TCP)

---

### 13. IMAP (Internet Message Access Protocol)

- E-postaları sunucuda tutar ve senkronize eder.

- Birden fazla cihazdan erişime uygundur.

**Port:** 143, 993 (TCP)

---

### 14. SMB (Server Message Block)

- Dosya, yazıcı ve diğer kaynakların paylaşımını sağlar.

- Windows tabanlı ağlarda sık kullanılır.

**Port:** 445 (TCP)

---

### 15. NTP (Network Time Protocol)

- Ağ cihazlarının saatlerini senkronize eder.

- TCP/UDP üzerinden çalışabilir, genellikle UDP kullanılır.

**Port:** 123 (UDP)

---

### 16. SNMP (Simple Network Management Protocol)

- Ağ cihazlarını izlemek ve yönetmek için kullanılır.

- Güvensiz sürümleri saldırılara açıktır.

**Port:** 161 (UDP), 162 (UDP, trap)

---

### 17. Telnet

- Uzak cihazları metin tabanlı kontrol etmek için kullanılır.

- Şifrelenmemiş olduğu için güvenli değildir.

**Port:** 23 (TCP)

---

### 18. SSH (Secure Shell)

- Telnet’in güvenli versiyonudur.

- Uzak cihazlara şifreli erişim sağlar.

**Port:** 22 (TCP)

