## SOC Analyst Rolü 

SOC (Security Operations Center), güvenlik olaylarını izleyen ve müdahale eden birimdir.

### SOC Analyst Görevleri

#### 1) SIEM Üzerinden Log Takibi

- Firewall, sunucu, endpoint ve AD loglarını izler.
- **Amaç:** Anormal davranışları erken tespit etmek.

#### 2) Şüpheli Aktivite Analizi

- Gelen alarmların gerçek tehdit olup olmadığını inceler.
- IP, kullanıcı, saat ve davranış kontrol edilir.

#### 3) Incident Oluşturma & Eskalasyon

- Gerçek tehdit varsa ticket açılır.
- Kritik durumlarda L2/L3 ekibe eskale edilir.

#### 4) False Positive Ayıklama

- Gerçek saldırı olmayan alarmlar kapatılır.
- SIEM kuralları gerekirse iyileştirilir.

#### 5) IOC Analizi

- Şüpheli IP, hash, domain gibi saldırı izleri loglarda aranır.
- **Amaç:** Yayılım var mı kontrol etmek.

#### 6) Raporlama

- Olayın özeti, etkisi ve alınan aksiyonlar yazılır.

---

#### SIEM

Log toplama ve korelasyon sistemidir.

#### Log

Sistemlerin oluşturduğu kayıt verileridir.

#### Incident

Gerçekleşmiş güvenlik olayı.

#### Alert

Şüpheli aktivite bildirimi.

#### False Positive

Gerçek tehdit olmayan alarm.
