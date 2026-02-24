## OSI ve TCP/IP Modelleri

OSI ve TCP/IP modelleri, ağ iletişiminin nasıl gerçekleştiğini anlamak için geliştirilmiş katmanlı yapılardır. Bu modeller sayesinde veri iletimi adım adım incelenebilir ve oluşan hatalar daha kolay
tespit edilebilir.

### OSI Modeli (7 Katman)

OSI modeli teorik ve eğitim amaçlı geliştirilmiş, detaylı bir referans modeldir. Toplam 7 katmandan oluşur ve her katmanın belirli bir görevi vardır.

#### 1.Physical (Fiziksel Katman)
Bu katman, verinin kablo, elektrik sinyali veya fiber optik üzerinden fiziksel olarak iletilmesini sağlar.

#### 2.Data Link (Veri Bağlantı Katmanı)
Cihazlar arası veri iletimini MAC adresleri üzerinden gerçekleştirir. Switch cihazları bu katmanda çalışır.

#### 3.Network (Ağ Katmanı)
IP adresleme ve yönlendirme işlemlerini yapar. Router cihazları bu katmanda görev alır.

#### 4.Transport (Taşıma Katmanı)
Verinin doğru ve eksiksiz iletilmesini sağlar. TCP ve UDP protokolleri bu katmanda bulunur ve port numaraları burada kullanılır.

#### 5.Session (Oturum Katmanı)
İki sistem arasındaki bağlantının başlatılması, yönetilmesi ve sonlandırılmasını sağlar.

#### 6.Presentation (Sunum Katmanı)
Verinin formatını düzenler ve şifreleme işlemlerini gerçekleştirir.

#### 7.Application (Uygulama Katmanı)
Kullanıcının doğrudan etkileşimde bulunduğu katmandır. HTTP, FTP ve DNS gibi protokoller burada çalışır.

**OSI modelinin amacı, iletişimi standartlaştırmak ve teknik sorunların hangi katmanda oluştuğunu tespit etmeyi kolaylaştırmaktır.**

---

### TCP/IP Modeli (4 Katman)

TCP/IP modeli, günümüzde internetin çalışmasını sağlayan pratik modeldir. Dört katmandan oluşur.

#### 1.Network Interface Katmanı
Fiziksel iletim ve yerel ağ iletişimini kapsar. OSI modelindeki Physical ve Data Link katmanlarına karşılık gelir.

#### 2.Internet Katmanı
IP adresleme ve yönlendirme işlemlerini gerçekleştirir. OSI modelindeki Network katmanına karşılık gelir.

#### 3.Transport Katmanı
TCP ve UDP protokolleri aracılığıyla veri iletimini düzenler.

#### 4.Application Katmanı
Kullanıcının kullandığı uygulama protokollerini içerir. OSI modelindeki Session, Presentation ve Application katmanlarının birleşmiş halidir.

---

### OSI ve TCP/IP Arasındaki Fark

- OSI modeli daha detaylı ve teorik bir modeldir. Eğitim ve analiz amacıyla kullanılır.

- TCP/IP modeli ise daha sade ve pratiktir. Gerçek ağ iletişiminde ve internet altyapısında kullanılan modeldir.

**Özetle, OSI modeli konuyu anlamak için; TCP/IP modeli ise gerçek dünyadaki ağ iletişimini açıklamak için kullanılır.**
