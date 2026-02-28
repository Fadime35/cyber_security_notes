## IPv4 ve IPv6

- IP (Internet Protocol), ağdaki cihazların birbirini tanıyabilmesi ve veri gönderebilmesi için kullanılan adresleme sistemidir.
- Her cihazın ağda benzersiz (unique) bir IP adresi vardır.

### IPv4 (Internet Protocol Version 4)

- 32 bitlik adres yapısına sahiptir.

- Noktalı ondalık formatta yazılır.

**Örnek:** 192.168.1.1

**Yapısı:**

- 4 oktetten oluşur.

- Her oktet 0–255 arasında değer alır.

- **Toplam adres sayısı:** yaklaşık 4.3 milyar

**Özellikleri:**

- Günümüzde hâlâ yaygın olarak kullanılır.

- Adres sayısı sınırlı olduğu için IP tükenme sorunu oluşmuştur.

- NAT (Network Address Translation) ile IP tasarrufu sağlanır.

**IPv4 Adres Türleri:**

- **Public IP:** İnternette benzersizdir.

- **Private IP:** Yerel ağlarda kullanılır.

10.0.0.0 – 10.255.255.255

172.16.0.0 – 172.31.255.255

192.168.0.0 – 192.168.255.255

### IPv6 (Internet Protocol Version 6)

- 128 bitlik adres yapısına sahiptir.

- Onaltılık (hexadecimal) formatta yazılır.

**Örnek:** 2001:0db8:85a3:0000:0000:8a2e:0370:7334

**Kısaltılmış gösterim:** 2001:db8::1

**Yapısı:**

- 8 bloktan oluşur.

- Her blok 16 bittir.

**Özellikleri:**

- IPv4 adres yetersizliği sorununu çözer.

- NAT’e ihtiyaç duymaz.

- Daha gelişmiş güvenlik ve otomatik yapılandırma desteği vardır.

- Daha verimli yönlendirme sağlar.

**IPv6 Adres Türleri:**

- **Global Unicast:** İnternette benzersiz

- **Link-Local:** Yerel ağ içi (FE80:: ile başlar)

- **Multicast:** Birden fazla cihaza gönderim

## IPv4 ve IPv6 Karşılaştırması

| Özellik       | IPv4        | IPv6               |
| ------------- | ----------- | ------------------ |
| Bit Sayısı    | 32 bit      | 128 bit            |
| Adres Formatı | Ondalık     | Hexadecimal        |
| Adres Sayısı  | ~4.3 milyar | Neredeyse sınırsız |
| NAT           | Gerekli     | Gerekmez           |
| Güvenlik      | Opsiyonel   | IPsec yerleşik     |
| Yaygınlık     | Çok yaygın  | Giderek artıyor    |


## IP Adresinin Amacı

- Ağdaki her cihazın kimliğini belirlemek

- Veri paketlerinin doğru hedefe ulaşmasını sağlamak

- Router’ların paketleri doğru ağa yönlendirmesine imkan vermek

**Veri Gönderme Örneği**

- Bilgisayarınız bir web sitesine bağlanmak ister.

- DNS alan adını IP adresine çevirir.

- Router, IP adresine göre paketi yönlendirir.

- Hedef IP’ye ulaşan veri işlenir ve cevap geri gönderilir.

**Özetle:**

- IPv4 adres sayısı sınırlıdır ve tükenmiştir.

- IPv6 geleceğin adresleme sistemidir ve adres sorunu yoktur.

- Her iki sistemin amacı, cihazların ağda benzersiz şekilde tanınmasını sağlamaktır.


  
