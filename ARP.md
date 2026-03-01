## ARP (Address Resolution Protocol)

ARP, bir ağdaki cihazların birbirlerini IP adresi üzerinden MAC adresiyle tanıyabilmesini sağlayan protokoldür.

**Amaç:**

Ağda veri paketlerinin doğru cihazlara iletilmesi için IP adresini fiziksel (MAC) adrese çevirmek.

**Nasıl çalışır:**

- Bir cihaz (ör. bilgisayar) aynı yerel ağdaki başka bir cihazla iletişim kurmak istediğinde, hedef cihazın MAC adresini bilmez.

- Cihaz bir ARP isteği (ARP Request) yayınlar: “192.168.1.5 IP adresine sahip cihaz kim?”

- Hedef cihaz, kendi MAC adresini içeren ARP cevabı (ARP Reply) gönderir.

- Artık gönderici cihaz, bu IP adresine ait MAC adresini biliyor ve veri paketlerini doğru cihazın ağ kartına iletebilir.

**Örnek:**

- Bilgisayar IP: 192.168.1.2

- Hedef cihaz IP: 192.168.1.5

- ARP çalıştıktan sonra: 192.168.1.5 → MAC: 00:1A:2B:3C:4D:5E

**Not:**

ARP sadece aynı yerel ağda (LAN) çalışır. Farklı ağlardaki cihazlara gönderim için yönlendiriciler (router) kullanılır.
