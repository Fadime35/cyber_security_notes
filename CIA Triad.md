## CIA Triad

Bilgi güvenliğinin temel modelidir.

### 1.Confidentiality (Gizlilik)

Bilginin yalnızca yetkili kişiler tarafından erişilebilir olması.

#### Örnek:

- **Encryption (Şifreleme):** Veri okunamaz hale getirilir, sadece anahtarı olan kişi görebilir.

- **Access Control:** Kimlerin hangi veriye erişebileceği sınırlandırılır.

- **MFA (Multi-Factor Authentication):** Ek doğrulama katmanı ekleyerek yetkisiz giriş riskini azaltır.

### 2.Integrity (Bütünlük)

Bilginin değiştirilmemesini veya değiştiyse fark edilmesini sağlamak.

#### Örnek:

- **Hashing:** Verinin parmak izi alınır, değişiklik olursa hash değeri değişir.

- **Digital Signatures:** Verinin kim tarafından gönderildiğini ve değiştirilmediğini doğrular.

- **Log Monitoring:** Şüpheli değişiklikler ve müdahaleler tespit edilir.

### 3.Availability (Erişilebilirlik)

Bilginin ve sistemlerin ihtiyaç duyulduğunda erişilebilir olması.

#### Örnek:

- **Yedekleme (Backup):** Veri kaybı durumunda geri yükleme yapılır.

- **Redundancy:** Sistem çökse bile alternatif sistem devreye girer

- **DDoS Koruması:** Sistemin aşırı trafik nedeniyle çökmesini engeller.

