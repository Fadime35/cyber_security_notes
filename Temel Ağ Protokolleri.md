## Temel Ağ Protokolleri

### 1.IP (Internet Protocol)

- Cihazlar arasında veri paketlerinin iletilmesini sağlar.

- Bağlantısız çalışır.

- Her pakette kaynak ve hedef IP bulunur.

**Sürümler:** IPv4 (32-bit), IPv6 (128-bit)

---

### 2.TCP (Transmission Control Protocol)

- Bağlantı odaklıdır.

- 3-way handshake ile bağlantı kurar.

- Güvenilir veri iletimi sağlar.

- Paket sırasını korur ve hata kontrolü yapar.

**Kullanıldığı servisler:** HTTP, HTTPS, FTP, SMTP

#### 3-way handshake nedir?

3-way handshake, TCP bağlantısı kurarken kullanılan üç adımlı el sıkışma sürecidir.

**Kısaca şöyle işler:**

- SYN (Synchronize) → Bağlantı başlatmak isteyen cihaz, hedefe “Bağlanmak istiyorum” mesajı gönderir.

- SYN-ACK (Synchronize-Acknowledge) → Hedef cihaz, “İstek aldım ve kabul ediyorum” mesajıyla yanıt verir.

- ACK (Acknowledge) → Başlatan cihaz, “Tamam, bağlantı kuruldu” mesajını gönderir.

**Sonuç:** TCP bağlantısı güvenli ve senkron bir şekilde kurulmuş olur.

---

### 3.UDP (User Datagram Protocol)

- Bağlantısızdır.

- Hızlıdır, paket sırası veya güvenilirlik garanti edilmez.

**Kullanıldığı servisler:** DNS, VoIP, Online oyunlar

---

### 4.ICMP (Internet Control Message Protocol)

- Ağ hata mesajları ve durum kontrolü için kullanılır.

- Ping ve traceroute komutları ICMP kullanır.

- SOC açısından aşırı ICMP trafiği saldırı göstergesi olabilir.

