## Log Dosyaları

Linux sistemlerinde olaylar, hatalar ve sistem aktiviteleri log dosyalarında saklanır. Genellikle /var/log dizininde bulunurlar.

### Önemli Log Dosyaları

| Dosya               | Açıklama                                                     |
| ------------------- | ------------------------------------------------------------ |
| `/var/log/auth.log` | Kullanıcı giriş/çıkış ve yetkilendirme kayıtları (SSH, sudo) |
| `/var/log/syslog`   | Genel sistem mesajları, hata ve uyarılar                     |
| `/var/log/kern.log` | Kernel (çekirdek) ile ilgili mesajlar                        |
| `/var/log/dmesg`    | Sistem açılış mesajları                                      |
| `/var/log/boot.log` | Önyükleme süreci kayıtları                                   |

### Log Dosyaları ile Çalışmak

- Son 10 satırı görmek:

tail /var/log/auth.log
tail -f /var/log/syslog   (Gerçek zamanlı takip)

- Belirli bir kelimeyi aramak:

grep "error" /var/log/syslog

- Logları filtrelemek:

  cat /var/log/auth.log | grep "sshd"

  ---

- Linux’ta her şey dosyadır: cihazlar, dizinler, süreçler.

- sudo komutu yönetici yetkisi gerektiren işlemler için kullanılır.

- Log dosyaları, sistem sorunlarını çözmek ve güvenlik olaylarını takip etmek için çok önemlidir.

- man komutu ile her komutun detayına bakabilir:

  man ls
