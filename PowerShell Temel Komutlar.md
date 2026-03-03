## PowerShell Temel Komutlar

### PowerShell Nedir?

- Windows’un gelişmiş komut satırı ortamıdır.
- CMD’den daha güçlüdür.
- Nesne tabanlı çalışır (text değil, object döndürür).
- Sistem yönetimi ve siber güvenlikte çok kullanılır.


### Temel Komut Yapısı

PowerShell komutları genelde şu yapıdadır:

```powershell
Verb-Noun
```

**Örnekler:**

```powershell
Get-Process
Get-Service
Get-Help
```


### Yardım Komutları

**Komut hakkında bilgi almak:**

```powershell
Get-Help Get-Process
```

**Detaylı yardım:**

```powershell
Get-Help Get-Process -Full
```

**Örnekleri görmek:**

```powershell
Get-Help Get-Process -Examples
```

### Dosya ve Klasör Komutları

**Bulunduğun dizini görmek:**

```powershell
Get-Location
```

**Klasör içeriğini listelemek:**

```powershell
Get-ChildItem
```

Kısayollar:

```powershell
ls
dir
```

**Klasör değiştirmek:**

```powershell
Set-Location C:\Users
```

Kısayol:

```powershell
cd
```

**Yeni klasör oluşturmak:**

```powershell
New-Item -ItemType Directory klasorAdi
```

**Dosya oluşturmak:**

```powershell
New-Item dosya.txt
```

**Dosya silmek:**

```powershell
Remove-Item dosya.txt
```

### Sistem Bilgisi Komutları

**Çalışan işlemleri görmek:**

```powershell
Get-Process
```

**Belirli bir işlemi görmek:**

```powershell
Get-Process chrome
```

**İşlem sonlandırmak:**

```powershell
Stop-Process -Name chrome
```

**Servisleri listelemek:**

```powershell
Get-Service
```

**Çalışan servisleri filtrelemek:**

```powershell
Get-Service | Where-Object {$_.Status -eq "Running"}
```


### Ağ Komutları

**IP bilgisi:**

```powershell
ipconfig
```

**Detaylı IP bilgisi:**

```powershell
ipconfig /all
```

**Ağ bağlantılarını görmek:**

```powershell
netstat -an
```

**DNS sorgusu:**

```powershell
nslookup google.com
```


### Filtreleme (Where-Object)

PowerShell’de filtreleme çok önemlidir.

```powershell
Get-Process | Where-Object {$_.CPU -gt 100}
```
 
CPU kullanımı 100’den büyük işlemleri gösterir.


### Çıktıyı Dosyaya Yazma

**Dosyaya yazmak:**

```powershell
Get-Process > processes.txt
```

**Dosyaya ekleme yapmak:**

```powershell
Get-Process >> processes.txt
```


### Değişken Tanımlama

```powershell
$isim = "Fadime"
```

**Kullanımı:**

```powershell
Write-Output $isim
```

### Komutları Listelemek

**Tüm komutları görmek:**

```powershell
Get-Command
```

**“process” içeren komutları görmek:**

```powershell
Get-Command *process*
```

