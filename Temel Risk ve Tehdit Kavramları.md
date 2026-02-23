## Temel Risk ve Tehdit Kavramları

- **Asset (Varlık)**

Korunması gereken değer (veri, sistem, itibar).

- **Threat (Tehdit)**

Bir varlığa zarar verme potansiyeli olan durum.

- **Vulnerability (Zafiyet)**

Sistemdeki güvenlik açığı.

- **Risk**

Tehditin bir zafiyeti kullanarak varlığa zarar verme olasılığı.

**Risk ≈ Threat × Vulnerability × Impact**

---
## Saldırı Türleri

### 1.Phishing (Oltalama)

Kullanıcıyı sahte e-posta, SMS veya web sitesi ile kandırarak bilgi çalma saldırısıdır.

#### Nasıl çalışır?

- Sahte banka/mail bildirimi gönderilir.

- Kullanıcı sahte siteye girer.

- Şifre veya kart bilgisi çalınır.

#### Hedef:

- Şifreler

- Kurumsal hesaplar

- Finansal bilgiler

#### Alt türleri:

- Spear phishing (hedefli)

- Smishing (SMS ile)

- Vishing (telefon ile)

### 2.Ransomware

Sisteme sızar, dosyaları şifreler ve fidye ister.

#### Nasıl bulaşır?

- Phishing mail eki

- Güvenlik açığı

- Zayıf RDP bağlantısı

#### Etkileri:

- Sistem kilitlenir.

- Operasyon durur.

- Büyük finansal zarar oluşur.

### 3.DDoS (Distributed Denial of Service)

Sunucuya aşırı trafik göndererek sistemi çökertme saldırısıdır.

#### Nasıl yapılır?

- Botnet kullanılır.

- Aynı anda binlerce cihaz istek gönderir.

#### Amaç:

- Hizmeti durdurmak

- Şirketi maddi zarara uğratmak

### 4.Brute Force Attack

Şifreyi deneme-yanılma ile tahmin etme saldırısıdır.

#### Hedef:

- Zayıf parolalar

- Admin panelleri

- SSH / RDP servisleri

#### Savunma:

- Güçlü parola

- MFA

- Hesap kilitleme politikası

### 5.SQL Injection

Web uygulamasındaki güvenlik açığını kullanarak veritabanına sızma saldırısıdır.

#### Nasıl çalışır?

- Giriş formuna zararlı SQL kodu yazılır.

- Veritabanı sorgusu manipüle edilir.

#### Sonuç:

- Kullanıcı bilgileri çalınır

- Admin erişimi alınabilir

### 6.Man-in-the-Middle (MITM)

İki kişi arasındaki iletişime gizlice girme saldırısıdır.

#### Nerede olur?

Güvensiz Wi-Fi ağlarında

#### Amaç:

- Trafiği dinlemek

- Veriyi değiştirmek

### 7.Malware (Genel Zararlı Yazılım)

Sisteme zarar vermek veya veri çalmak için yazılmış yazılımlardır.

#### Türleri:

- Virus

- Worm

- Trojan

- Spyware

- Keylogger

### 8.Social Engineering

Teknik değil, psikolojik manipülasyon saldırısıdır.

#### Örnek:

- “IT’den arıyorum şifrenizi doğrular mısınız?”

- Sahte CEO maili
