## PowerShell Nedir?

- Windows’un gelişmiş komut satırı ve script ortamıdır.

- CMD’den daha güçlüdür.

- Komutlar Noun-Verb (Fiil-İsim) mantığıyla yazılır.

**Örn:** Get-Process, Set-Location

### Dosya ve Klasör İşlemleri

**Bulunduğun dizini öğrenme**

```
Get-Location
```
**Klasör içeriğini listeleme**

```
Get-ChildItem
```

Kısayol:

```
ls
dir
```

**Klasör değiştirme**

```
Set-Location C:\Users
```

Kısayol:

```
cd C:\Users
```

**Yeni klasör oluşturma**

```
New-Item -ItemType Directory klasorAdi
```

**Yeni dosya oluşturma**

```
New-Item dosya.txt
```

**Dosya silme**

```
Remove-Item dosya.txt
```

**Klasör silme**

```
Remove-Item klasorAdi -Recurse
```

### Dosya İçeriği İşlemleri

**Dosya içeriğini görüntüleme**

```
Get-Content dosya.txt
```

**Dosyaya yazı ekleme**

```
Add-Content dosya.txt "Merhaba"
```

**Dosyayı tamamen yeniden yazma**

```
Set-Content dosya.txt "Yeni içerik"
```

### Sistem ve İşlem (Process) Komutları

**Çalışan işlemleri listeleme**

```
Get-Process
```

**Belirli bir işlemi arama**

```
Get-Process chrome
```

**İşlem sonlandırma**

```
Stop-Process -Name chrome
```

### Ağ (Network) Komutları

**IP bilgisi görüntüleme**

```
ipconfig
```

```
Get-NetIPAddress
```

**Ping atma**

```
Test-Connection google.com
```

**Açık portları görüntüleme**

```
netstat -an
```

### Kullanıcı ve Sistem Bilgisi

**Bilgisayar adı**

```
hostname
```

**Kullanıcı bilgisi**

```
whoami
```

**Sistem bilgileri**

```
Get-ComputerInfo
```

### Filtreleme

PowerShell’in en güçlü tarafı filtrelemedir.

**Where-Object kullanımı**

```
Get-Process | Where-Object {$_.CPU -gt 100}
```

CPU değeri 100’den büyük olan işlemleri gösterir.


### Pipe (|) Mantığı

Pipe (|) = Bir komutun çıktısını diğerine gönderir.

**Örnek:**

```
Get-Process | Sort-Object CPU -Descending
```

CPU kullanımına göre sıralar.


### Yardım Komutları

**Komut hakkında bilgi**

```
Get-Help Get-Process
```

**Örneklerle yardım**

```
Get-Help Get-Process -Examples
```

**Komut arama**

```
Get-Command *process*
```
