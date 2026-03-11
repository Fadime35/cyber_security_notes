## ELK Stack

ELK Stack, log verilerini toplamak, analiz etmek ve görselleştirmek için kullanılan açık kaynaklı bir log yönetim ve veri analiz platformudur.

**ELK kelimesi üç teknolojinin baş harflerinden oluşur:**

- Elasticsearch

- Logstash

- Kibana

Bu üç araç birlikte çalışarak log verilerini analiz etmeyi sağlar.

**Amaç:**

- Log verilerini merkezi olarak toplamak

- Büyük veri üzerinde hızlı arama yapmak

- Verileri analiz etmek ve görselleştirmek

## ELK Stack Bileşenleri

### 1) Elasticsearch

Verilerin depolandığı ve arama yapıldığı veri tabanıdır.

**Görevleri:**

- Log verilerini depolamak

- Verileri indekslemek

- Hızlı arama yapmak

**Özellikleri:**

- Dağıtık yapı

- Büyük veri analizi

- Gerçek zamanlı arama

### 2) Logstash

Log verilerini toplayan ve işleyen veri işleme aracıdır.

**Görevleri:**

- Logları farklı kaynaklardan almak

- Veriyi filtrelemek

- Veriyi Elasticsearch’e göndermek

**Logstash veri işleme süreci:**

Input → Filter → Output

**Input**

Log verisinin alındığı yer

**Filter**

Verinin düzenlendiği ve analiz edildiği bölüm

**Output**

Verinin gönderildiği yer

### 3) Kibana

Verilerin görselleştirildiği arayüzdür.

**Görevleri:**

- Dashboard oluşturmak

- Log araması yapmak

- Grafik ve rapor oluşturmak

Kullanıcılar Kibana üzerinden log analizini kolayca yapabilir.

## ELK Veri Akışı

ELK sisteminde veri şu şekilde ilerler:

**Log kaynakları → Logstash → Elasticsearch → Kibana**

**Örnek:**

Firewall logları
→ Logstash veriyi alır
→ Elasticsearch depolar
→ Kibana üzerinden analiz edilir

## ELK Stack Kullanım Alanları

### Log yönetimi

Sistem loglarını analiz etmek

### Güvenlik analizi

Siber saldırıları tespit etmek

### Uygulama izleme

Uygulama performansını takip etmek

### Operasyon izleme

Sunucu ve sistem aktivitelerini izlemek

---

### SOC Analisti Açısından Önemi

**SOC analistleri ELK Stack kullanarak:**

- Log araması yapar

- Şüpheli aktiviteleri analiz eder

- Dashboard üzerinden sistem davranışını izler

- Güvenlik olaylarını araştırır

ELK Stack özellikle açık kaynak SIEM çözümlerinde yaygın kullanılır.
