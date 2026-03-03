## Active Directory (AD) Temelleri

### Active Directory Nedir?

- Active Directory (AD), Microsoft tarafından geliştirilen merkezi kimlik ve yetki yönetim sistemidir.

- Kurum içindeki kullanıcıları, bilgisayarları ve erişim yetkilerini merkezi olarak yönetmeyi sağlar.


### Active Directory Ne İşe Yarar?

- Kullanıcı hesabı oluşturma
- Şifre politikası belirleme
- Dosya ve kaynak erişim kontrolü
- Bilgisayarları merkezi yönetme
- Güvenlik politikalarını uygulama


### Active Directory Nasıl Çalışır?

**1. Domain (Etki Alanı)**

Aynı güvenlik sınırı içinde bulunan kullanıcı ve bilgisayarların oluşturduğu yapıdır.

**Örnek domain adı:**

```
company.local
```

**2. Domain Controller (DC)**

Active Directory veritabanını tutan ve kimlik doğrulama yapan sunucudur.

**Görevleri:**

- Authentication (Kimlik Doğrulama)
- Authorization (Yetkilendirme)
- Politika uygulama

Kullanıcı giriş yaparken sistem Domain Controller’a doğrulama isteği gönderir.


**3. LDAP**

LDAP (Lightweight Directory Access Protocol), dizin bilgilerini sorgulamak için kullanılan protokoldür.

Kullanıcı, grup ve bilgisayar bilgileri LDAP üzerinden sorgulanır.


**4. Kerberos**

Kerberos, Active Directory’de kullanılan kimlik doğrulama protokolüdür.

**Çalışma mantığı:**

1. Kullanıcı giriş yapar.
2. Ticket alır.
3. Bu ticket ile diğer sistemlere erişir.


### Active Directory Nesneleri

Active Directory içindeki her yapı bir "object"tir.

**1.User**

Kullanıcı hesabı

**2.Computer**

Domain’e bağlı bilgisayar

**3.Group**

Kullanıcıları gruplamak için kullanılır.

**Örnek:**

```
IT_Group
HR_Group
Domain Admins
```


**4.Organizational Unit (OU)**

OU, mantıksal klasör yapısıdır. Departmanlara göre ayrım yapılmasını sağlar.

**Örnek:**

```
Company
 ├── IT
 ├── HR
 └── Finance
```

Politikalar OU bazlı uygulanabilir.



**5.Group Policy (GPO)**

Merkezi güvenlik politikası yönetim sistemidir.

**Örnek kullanım alanları:**

- Minimum şifre uzunluğu belirleme
- USB kullanımını engelleme
- Firewall zorunlu kılma
- Ekran kilidi süresi ayarlama



**6.DNS ve Active Directory İlişkisi**

- Active Directory düzgün çalışabilmek için DNS’e ihtiyaç duyar.

- DNS, domain isim çözümlemesini sağlar.

- DNS olmadan Active Directory sağlıklı çalışmaz.

---

Active Directory, kurumsal ağların merkezidir.

**Saldırı senaryosu genelde şu şekilde ilerler:**

1. Bir kullanıcı hesabı ele geçirilir
2. Yetki yükseltilir
3. Domain Admin yetkisi alınır
4. Tüm sistem kontrol altına alınır

Bu nedenle AD güvenliği kritik öneme sahiptir.


