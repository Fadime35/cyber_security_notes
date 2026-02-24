## Ağ Servis Protokolleri

### 1.ARP (Address Resolution Protocol)

- IP adreslerini cihazların fiziksel MAC adreslerine çevirir.

- Sadece yerel ağda çalışır.

- SOC açısından önemli çünkü ARP spoofing saldırıları ile saldırganlar ağ trafiğini ele geçirebilir veya yönlendirebilir.

---

### 2.DNS (Domain Name System)

Domain adlarını IP adreslerine çevirir; örneğin example.com → 93.184.216.34.

- **Port:** 53 (UDP/TCP)

**SOC açısından kritik noktalar:**

- **DNS tunneling:** Normal DNS trafiği içinde veri gizleme veya dışarı sızdırma işlemi.

- **Şüpheli domain sorguları:** Kullanıcının veya sistemin normalde erişmediği veya zararlı domainlere yaptığı sürekli sorgular, malware veya C2 sunucusu iletişimini gösterebilir.

---

### 3.DHCP (Dynamic Host Configuration Protocol)

- Ağdaki cihazlara otomatik IP adresi, subnet mask, gateway ve DNS bilgisi atar.

- Loglar sayesinde ağdaki yeni cihazlar tespit edilebilir ve anormal cihaz hareketleri izlenebilir.
