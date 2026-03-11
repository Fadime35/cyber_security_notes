## Alert Mantığı (Siber Güvenlikte Alarm Sistemi)

Alert, güvenlik sistemlerinin şüpheli veya tehlikeli bir olay tespit ettiğinde oluşturduğu uyarıdır. Bu uyarılar genellikle SIEM, IDS/IPS, firewall veya endpoint
güvenlik sistemleri tarafından üretilir.

**Amaç:**

- Olası saldırıları erken tespit etmek

- Güvenlik ekiplerini bilgilendirmek

- Olay müdahalesini başlatmak

Alertler genellikle SOC ekipleri tarafından incelenir.

## Alert Nasıl Oluşur?

Bir sistem belirlenen kurallara göre logları analiz eder. Eğer belirli bir şüpheli durum oluşursa sistem alarm üretir.

**Genel mantık:**

Log verisi → Analiz → Kural eşleşmesi → Alert

**Örnek:**

- 10 başarısız login denemesi

- Aynı IP adresinden gelmesi

- 5 dakika içinde gerçekleşmesi

Bu koşullar gerçekleştiğinde sistem brute force saldırısı için alert oluşturur.

## Alert Kaynakları

Alertler farklı güvenlik sistemlerinden gelebilir.

### Firewall

Şüpheli ağ trafiğini tespit eder

### IDS / IPS

Saldırı imzalarını algılar

### Endpoint Security

Bilgisayarda zararlı aktiviteleri tespit eder

### SIEM

Farklı logları analiz ederek alarm üretir

### Web Application Firewall (WAF)

Web saldırılarını tespit eder

## Alert Türleri

### True Positive

Gerçek bir saldırı veya güvenlik olayının doğru şekilde tespit edilmesidir.

**Örnek:**

Gerçek bir brute force saldırısı tespit edilmesi.

### False Positive

Aslında zararsız bir olayın saldırı gibi algılanmasıdır.

**Örnek:**

Bir kullanıcının yanlış şifreyi birkaç kez girmesi.

### False Negative

Gerçek saldırının sistem tarafından tespit edilememesidir.

Bu en tehlikeli durumdur.

### True Negative

Normal bir olayın doğru şekilde saldırı olarak algılanmamasıdır.

## Alert Analizi (SOC Süreci)

**Bir SOC analisti alert geldiğinde şu adımları izler:**

- Alert detaylarını inceler

- Log kayıtlarını analiz eder

- Olayın gerçek olup olmadığını belirler

- Gerekirse incident response başlatır

## Alert İçeriğinde Bulunan Bilgiler

**Bir alert genellikle şu bilgileri içerir:**

- Zaman bilgisi

- Kaynak IP adresi

- Hedef IP adresi

- Kullanıcı bilgisi

- Olay türü

- Risk seviyesi (low, medium, high)

## Alert Öncelik Seviyeleri

Alertler genellikle risk seviyesine göre sınıflandırılır.

**Low**

Düşük riskli olaylar

**Medium**

Şüpheli aktiviteler

**High**

Olası saldırılar

**Critical**

Acil müdahale gerektiren olaylar

---

### SOC Analisti Açısından Önemi

SOC analistlerinin temel işi gelen alertleri analiz etmektir.

**Bu analiz sayesinde:**

- Siber saldırılar tespit edilir

- Sistemler korunur

- Olay müdahalesi yapılır
