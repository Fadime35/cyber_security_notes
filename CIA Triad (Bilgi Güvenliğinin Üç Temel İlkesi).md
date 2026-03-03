## CIA Triad (Bilgi Güvenliğinin Üç Temel İlkesi)

CIA Triad, bilgi güvenliğinin temelini oluşturan üç ana kavramdan oluşur: Confidentiality (Gizlilik), Integrity (Bütünlük), Availability (Erişilebilirlik). 
Bir sistemin güvenli kabul edilebilmesi için bu üç özelliği de sağlaması gerekir.

### 1) Confidentiality (Gizlilik)

Bilginin yalnızca yetkili kişiler tarafından erişilebilir olmasını ifade eder. Yetkisiz kişilerin veriye erişmesi gizlilik ihlalidir.

**Amaç:**

- Veriyi yetkisiz erişimden korumak

- Kişisel, finansal veya kurumsal bilgilerin sızmasını önlemek

**Nasıl sağlanır:**

- Kimlik doğrulama (authentication)

- Yetkilendirme (authorization)

- Şifreleme (encryption)

- Güçlü parola politikaları

- Çok faktörlü kimlik doğrulama (MFA)

**Örnek:**

Bir hastane sisteminde hasta bilgilerine sadece doktorların erişebilmesi gizlilik ilkesine örnektir.

### 2) Integrity (Bütünlük)

Verinin doğruluğunu ve değiştirilmemiş olmasını ifade eder. Veri, yetkisiz şekilde değiştirilmemeli veya bozulmamalıdır.

**Amaç:**

- Verinin doğru ve güvenilir kalmasını sağlamak

- Yetkisiz değişiklikleri tespit etmek

**Nasıl sağlanır:**

- Hash algoritmaları 

- Dijital imza

- Erişim kontrol mekanizmaları

- Log (kayıt) sistemleri

- Versiyon kontrolü

**Örnek:**

Bir bankada hesap bakiyesinin izinsiz değiştirilmemesi bütünlük ilkesidir.

### 3) Availability (Erişilebilirlik)

Bilginin ihtiyaç duyulduğu anda erişilebilir olmasını ifade eder. Sistemlerin çalışır durumda olması gerekir.

**Amaç:**

- Hizmet kesintilerini önlemek

- Sistem sürekliliğini sağlamak

**Nasıl sağlanır:**

- Yedekleme (backup)

- Yük dengeleme (load balancing)

- Felaket kurtarma planları (disaster recovery)

- DDoS koruma sistemleri

- Sunucu ve ağ altyapısının güçlü olması

**Örnek:**

Bir e-ticaret sitesinin 7/24 çalışır durumda olması erişilebilirlik ilkesidir.

### CIA Triad’ın Önemi

- Bilgi güvenliği politikalarının temelini oluşturur.

- Risk analizi yapılırken bu üç başlık dikkate alınır.

- Güvenlik açıkları genellikle bu üç ilkeden birinin ihlal edilmesiyle ortaya çıkar.

**Özet:**

- **Gizlilik:** Kimler erişebilir?

- **Bütünlük:** Veri doğru mu, değiştirildi mi?

- **Erişilebilirlik:** İhtiyaç anında sistem çalışıyor mu?

Bu üç ilke birlikte değerlendirildiğinde güçlü bir bilgi güvenliği yapısı oluşturulur.
