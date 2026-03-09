## MITRE ATT&CK Framework

MITRE ATT&CK, siber saldırganların kullandığı gerçek saldırı tekniklerini ve taktiklerini sınıflandıran bir bilgi tabanıdır. Güvenlik ekipleri saldırıları
anlamak, analiz etmek ve savunma stratejileri geliştirmek için bu frameworkü kullanır.

ATT&CK kelimesi şu ifadenin kısaltmasıdır:
**Adversarial Tactics, Techniques, and Common Knowledge**

**Amaç:**

- Saldırgan davranışlarını analiz etmek

- Güvenlik ekiplerine standart bir referans sağlamak

- Tehdit tespiti ve savunma stratejilerini geliştirmek

### MITRE ATT&CK Yapısı

Framework üç temel kavramdan oluşur:

**1) Tactics (Taktikler)**

Saldırganın amacını ifade eder.
Yani saldırganın o aşamada ne yapmak istediğini gösterir.

**Örnek taktikler:**

- Initial Access

- Execution

- Persistence

- Privilege Escalation

- Defense Evasion

- Credential Access

- Discovery

- Lateral Movement

- Collection

- Command and Control

- Exfiltration

- Impact

**2) Techniques (Teknikler)**

Saldırganın amacına ulaşmak için kullandığı yöntemlerdir.

**Örnek:**

Credential Access taktiği altında:

- Brute Force

- Credential Dumping

- Keylogging

Her teknik saldırganın hedefe ulaşmak için kullandığı yöntemi açıklar.

**3) Sub-techniques (Alt Teknikler)**

Bir tekniğin daha detaylı alt yöntemleridir.

**Örnek:**

Credential Dumping tekniğinin alt teknikleri:

- LSASS Memory

- SAM Database

- Security Account Manager

Bu yapı saldırı davranışlarını daha detaylı analiz etmeyi sağlar.

### MITRE ATT&CK Matris

ATT&CK genellikle bir matris şeklinde gösterilir.

**Matris yapısı:**

**Üst satır:** Tactics (saldırganın amacı)

**Alt satırlar:** Techniques (kullanılan yöntemler)

Bu matris, saldırının hangi aşamada olduğunu anlamayı kolaylaştırır.

### MITRE ATT&CK Kullanım Alanları

**Tehdit Analizi**

Saldırgan davranışlarını analiz etmek için kullanılır.

**SOC Operasyonları**

Log analizinde saldırının hangi teknikle yapıldığını belirlemek için kullanılır.

**Tehdit Avcılığı (Threat Hunting)**

Sistemde gizli saldırı aktivitelerini araştırmak için kullanılır.

**Güvenlik Testleri**

Red Team ve penetration test çalışmalarında referans olarak kullanılır.
