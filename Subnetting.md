## Subnetting Nedir?

Subnetting, büyük bir IP ağını daha küçük ve yönetilebilir alt ağlara (subnet) bölme işlemidir.

Büyük bir ağı küçük parçalara ayırarak:
- Yönetimi kolaylaştırır.
- Güvenliği artırır.
- IP adreslerini verimli kullanmayı sağlar.

---

## Subnetting Neden Kullanılır?

**1️.Ağ Yönetimini Kolaylaştırmak**

Büyük ağlar yönetimi zorlaştırır. Ağ departmanlara göre bölünebilir:

- Muhasebe → 1 alt ağ
- IT → 1 alt ağ
- İnsan Kaynakları → 1 alt ağ

Bu sayede:
- Trafik kontrolü kolaylaşır.
- Broadcast trafiği azalır.
- Sorun tespiti hızlanır.

**2️.IP Adresi İsrafını Önlemek**

Her ağa gereğinden fazla IP vermek adres kaybına neden olur.

Subnetting sayesinde:
- İhtiyaç kadar IP verilir.
- IP adresleri verimli kullanılır.

---

## CIDR Notasyonu

IP adresinin sonunda bulunan `/24`, `/25` gibi ifadelerdir.

**Örnek:**

192.168.1.0/24

**Anlamı:**
- İlk 24 bit → Network kısmı
- Kalan bitler → Host kısmı

---

## Subnet Mask

Network ve host kısmını ayırır.

| CIDR | Subnet Mask |
|------|------------|
| /24  | 255.255.255.0 |
| /25  | 255.255.255.128 |
| /26  | 255.255.255.192 |
| /27  | 255.255.255.224 |

---

## Örnek: 192.168.1.0/24 Ağını 2’ye Bölmek

**1.Başlangıç Durumu**

Ağımız:

192.168.1.0/24

/24 demek:
- 24 bit network
- 8 bit host

Host için 8 bit varsa:

2⁸ = 256 IP

Ancak:
- 1 IP → Network adresi
- 1 IP → Broadcast adresi

Bu yüzden:

256 - 2 = 254 kullanılabilir IP

---

**2️.Ağı 2’ye Bölmek**

Bir ağı 2’ye bölmek demek:

Host kısmından 1 bit ödünç almak demektir.

Yani:

/24 → /25

Artık:
- 25 bit network
- 7 bit host

---

**3️.Yeni Host Sayısı**

Host için 7 bit kaldı:

2⁷ = 128 IP

Kullanılabilir host sayısı:

128 - 2 = 126 host

Yani her alt ağda 126 cihaz olabilir.

---

**4.Blok Mantığı**

/25 subnet maskesi:

255.255.255.128

Son oktette artış miktarı:

256 - 128 = 128

Yani alt ağlar 128’er artarak oluşur.

---

**5️.Oluşan Alt Ağlar**

- **1. Alt Ağ**

IP aralığı: 192.168.1.0 – 192.168.1.127  
Network: 192.168.1.0  
Kullanılabilir IP: 192.168.1.1 – 192.168.1.126  
Broadcast: 192.168.1.127  



- **2. Alt Ağ**

IP aralığı: 192.168.1.128 – 192.168.1.255  
Network: 192.168.1.128  
Kullanılabilir IP: 192.168.1.129 – 192.168.1.254  
Broadcast: 192.168.1.255  

---

## CIDR Artarsa Ne Olur?

CIDR değeri arttıkça:
- Network sayısı artar.
- Her subnet içindeki host sayısı azalır.

| CIDR | Toplam IP | Kullanılabilir Host |
| ---- | --------- | ------------------- |
| /24  | 256       | 254                 |
| /25  | 128       | 126                 |
| /26  | 64        | 62                  |
| /27  | 32        | 30                  |

---

## Network ve Broadcast Nedir?

## Network Adresi
- Alt ağı temsil eder.
- İlk IP adresidir.
- Hostlara atanmaz.

## Broadcast Adresi
- O alt ağdaki tüm cihazlara veri gönderir.
- Son IP adresidir.
- Hostlara atanmaz.

---

Subnetting:
- Büyük bir IP ağını küçük alt ağlara böler.
- Yönetimi kolaylaştırır.
- Güvenliği artırır.
- Broadcast trafiğini azaltır.
- IP adreslerini verimli kullanır.
  
