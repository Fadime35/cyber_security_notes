## Kullanıcı ve Yetki Yönetimi 

### 1. Kullanıcı Nedir?

Kullanıcı, bir sistemi (işletim sistemi, uygulama, veritabanı vb.) kullanma yetkisine sahip kimliklendirilmiş varlıktır.

Her kullanıcının genellikle:

- Kullanıcı adı (username)

- Şifre (password)

- Kullanıcı kimliği (ID)

- Yetkileri (permissions)

bulunur.

**Örnek:**

- Windows kullanıcısı

- Linux kullanıcısı

- Veritabanı kullanıcısı

- Web uygulaması kullanıcısı

### 2. Yetki (Permission) Nedir?

Yetki, bir kullanıcının sistem üzerinde hangi işlemleri yapabileceğini belirleyen izinlerdir.

**Temel yetkiler:**

- Okuma (Read)

- Yazma (Write)

- Çalıştırma (Execute)

- Silme (Delete)

- Kullanıcı oluşturma

- Yetki verme veya değiştirme

### 3. Kimlik Doğrulama (Authentication)

Kullanıcının gerçekten iddia ettiği kişi olup olmadığını doğrulama işlemidir.

**Kimlik doğrulama yöntemleri:**

- Şifre

- SMS doğrulama

- E-posta kodu

- Biyometrik doğrulama

- Çok faktörlü kimlik doğrulama (MFA)

**Önemli nokta:**


Kimlik doğrulama, sisteme giriş aşamasıdır.

### 4. Yetkilendirme (Authorization)

Kimliği doğrulanan kullanıcının sistem üzerinde hangi işlemleri yapabileceğinin belirlenmesidir.

**Örnek:**

- Normal kullanıcı program yükleyemez.

- Yönetici kullanıcı sistem ayarlarını değiştirebilir.

**Önemli fark:*
Authentication, “Kim olduğunu doğrular.”
Authorization, “Ne yapabileceğini belirler.”

### 5. Kullanıcı Türleri

**Standart Kullanıcı**

- Sınırlı yetkilere sahiptir.

-  Sistem ayarlarını değiştiremez.

**Yönetici (Administrator)**

- Geniş yetkilere sahiptir.

- Kullanıcı ekleyebilir, silebilir ve yetki verebilir.

**Root (Linux)**

- Linux sistemlerde en yüksek yetkili kullanıcıdır.

- Tüm sistem üzerinde tam kontrole sahiptir.

### 6. Yetki Modelleri

**1. DAC (Discretionary Access Control)**

- Kaynak sahibi yetki verir.

* Esnektir ancak güvenlik riski oluşturabilir.

**2. MAC (Mandatory Access Control)**

- Yetkiler merkezi bir sistem tarafından belirlenir.

- Genellikle yüksek güvenlik gerektiren ortamlarda kullanılır.

**3. RBAC (Role Based Access Control)**

- Yetkiler roller üzerinden atanır.

- Kurumsal yapılarda en yaygın kullanılan modeldir.

**Örnek roller:**

- Muhasebe

- İnsan Kaynakları

- IT

- Yönetici

### 7. En Az Yetki Prensibi (Principle of Least Privilege)

Bir kullanıcıya yalnızca işini yapması için gerekli olan minimum yetki verilmelidir.

**Amaç:**

- Güvenlik riskini azaltmak

- İç tehditleri sınırlandırmak

- Yetki kötüye kullanımını önlemek

### 8. Yetki Yükseltme (Privilege Escalation)

Bir kullanıcının sahip olmadığı daha yüksek yetkilere ulaşması durumudur.

**Türleri:**

- **Dikey yetki yükseltme:** Standart kullanıcıdan yöneticiye geçiş

- **Yatay yetki yükseltme:** Aynı seviyedeki başka bir kullanıcının yetkilerini ele geçirme


### 9. Kullanıcı Hesap Güvenliği

**Dikkat edilmesi gereken güvenlik önlemleri:**

- Güçlü şifre politikası

- Hesap kilitleme politikası

- Çok faktörlü kimlik doğrulama kullanımı

- Varsayılan yönetici hesaplarının kontrolü

- Kullanılmayan hesapların silinmesi

- Log kayıtlarının düzenli incelenmesi

### 10. Loglama ve İzleme

Kullanıcı işlemleri kayıt altına alınmalıdır.

**Örnek loglar:**

- Başarısız giriş denemeleri

- Yetki değişiklikleri

- Yönetici işlemleri



  
