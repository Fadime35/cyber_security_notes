## Bash Temel Komutlar

Bash, Linux’ta en yaygın kullanılan komut satırı kabuğudur.

### Dosya ve Dizin İşlemleri

| Komut   | Açıklama                                  | Örnek                    |
| ------- | ----------------------------------------- | ------------------------ |
| `ls`    | Dizin içeriğini listeler                  | `ls -l` (detaylı liste)  |
| `cd`    | Dizin değiştirir                          | `cd /home/fadime`        |
| `pwd`   | Mevcut dizini gösterir                    | `pwd`                    |
| `mkdir` | Yeni dizin oluşturur                      | `mkdir yeni_klasor`      |
| `rmdir` | Boş dizini siler                          | `rmdir eski_klasor`      |
| `touch` | Boş dosya oluşturur                       | `touch dosya.txt`        |
| `cp`    | Dosya/dizin kopyalar                      | `cp dosya.txt yedek.txt` |
| `mv`    | Dosya/dizin taşır veya yeniden adlandırır | `mv eski.txt yeni.txt`   |
| `rm`    | Dosya/dizin siler                         | `rm dosya.txt`           |

### Dosya Görüntüleme

| Komut  | Açıklama                                | Örnek                  |
| ------ | --------------------------------------- | ---------------------- |
| `cat`  | Dosya içeriğini gösterir                | `cat dosya.txt`        |
| `less` | Büyük dosyalarda kaydırmalı görüntüleme | `less dosya.txt`       |
| `head` | Dosyanın başını gösterir                | `head -n 10 dosya.txt` |
| `tail` | Dosyanın sonunu gösterir                | `tail -n 10 dosya.txt` |
| `grep` | Dosya içinde arama yapar                | `grep "error" syslog`  |

### Sistem Bilgisi

| Komut      | Açıklama                   |
| ---------- | -------------------------- |
| `whoami`   | Aktif kullanıcıyı gösterir |
| `uname -a` | Sistem bilgisi gösterir    |
| `df -h`    | Disk kullanımını gösterir  |
| `du -sh`   | Dizin boyutunu gösterir    |
