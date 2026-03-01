## Portlar ve Protokoller

**Port:** Bir cihazda hangi uygulamanın veriyi alacağını belirten sayıdır. Her uygulamanın farklı bir portu vardır ve bu portlar 0 ile 65535 arasında değişir.

**Protokoller:** Verilerin ağ üzerinden nasıl iletileceğini belirleyen kurallardır. Örneğin verinin nasıl paketleneceği, gönderileceği ve alınacağı protokollerle 
belirlenir.

| Protokol                                         | Port  | Açıklama                                                                                                                           |
| ------------------------------------------------ | ----- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **HTTP (Hypertext Transfer Protocol)**           | 80    | Web sayfalarının kullanıcı tarayıcılarına iletilmesi için kullanılır. Şifreleme yoktur; veri metin olarak gönderilir.              |
| **HTTPS (HTTP Secure)**                          | 443   | HTTP’nin şifreli versiyonu. SSL/TLS ile veri güvenliği sağlar. Banka ve e-ticaret sitelerinde kullanılır.                          |
| **FTP (File Transfer Protocol)**                 | 21    | Dosya aktarımı için kullanılır. Veri şifrelenmez; güvenli versiyonları **FTPS (990)** ve **SFTP (SSH üzerinden 22)** ile sağlanır. |
| **SSH (Secure Shell)**                           | 22    | Güvenli uzak sunucu bağlantısı sağlar. Komut çalıştırma ve sistem yönetimi için tercih edilir.                                     |
| **SMTP (Simple Mail Transfer Protocol)**         | 25    | E-posta gönderimi için kullanılır. Güvenli versiyonu **SMTPS (465)** SSL/TLS üzerinden çalışır.                                    |
| **POP3 (Post Office Protocol v3)**               | 110   | E-postaları sunucudan çekmek için kullanılır. Kullanıcı bilgisayarına indirir. Güvenli versiyonu **POP3S (995)**.                  |
| **IMAP (Internet Message Access Protocol)**      | 143   | E-postaları sunucuda tutar ve senkronizasyon sağlar. Şifreli versiyonu **IMAPS (993)**.                                            |
| **SNMP (Simple Network Management Protocol)**    | 161   | Ağ cihazlarının yönetimi ve izlenmesi için kullanılır. SNMPv3 ile güvenli sürümü vardır.                                           |
| **DNS (Domain Name System)**                     | 53    | Alan adlarını IP adreslerine çevirir. UDP ile hızlı sorgulama, TCP ile zone transferi yapılır.                                     |
| **Telnet**                                       | 23    | Uzak sistemlere bağlantı için kullanılır. Şifrelenmemiştir; güvenlik riski yüksektir.                                              |
| **RDP (Remote Desktop Protocol)**                | 3389  | Windows sistemlerde uzak masaüstü bağlantısı sağlar.                                                                               |
| **LDAP (Lightweight Directory Access Protocol)** | 389   | Dizin servisleri ile iletişim kurmak için kullanılır. Güvenli versiyonu **LDAPS (636)** SSL/TLS ile çalışır.                       |
| **TFTP (Trivial File Transfer Protocol)**        | 69    | Basit dosya transfer protokolüdür. Ağ cihazları arasında firmware ve konfigürasyon aktarmak için kullanılır. Şifreleme yoktur.     |
| **NTP (Network Time Protocol)**                  | 123   | Sistem saatlerinin senkronizasyonu için kullanılır.                                                                                |
| **MySQL**                                        | 3306  | MySQL veritabanına bağlanmak için kullanılır.                                                                                      |
| **PostgreSQL**                                   | 5432  | PostgreSQL veritabanına bağlanmak için kullanılır.                                                                                 |
| **MSSQL (SQL Server)**                           | 1433  | Microsoft SQL Server veritabanına bağlanmak için kullanılır.                                                                       |
| **DHCP (Dynamic Host Configuration Protocol)**   | 67/68 | IP adreslerini otomatik dağıtmak için kullanılır. Sunucu 67, istemci 68 portunu kullanır.                                          |
| **Kerberos**                                     | 88    | Ağ üzerinde kimlik doğrulama için kullanılır.                                                                                      |
| **SMB (Server Message Block)**                   | 445   | Dosya ve yazıcı paylaşımı için Windows ağlarında kullanılır.                                                                       |
| **IRC (Internet Relay Chat)**                    | 194   | Chat sunucularına bağlanmak için kullanılan protokol.                                                                              |

