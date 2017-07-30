### Özgür Yazılım Felsefesi'ne Giriş


### Komut Satırı (Kabuk) ve Temel Komutlar


### GNU/Linux İşletim Sisteminin Yapısı



### Açılış Sistemi


### Kullanıcı Yönetimi


### Paket Yönetim Sistemi


### Zamanlanmış Görevler


### Sistem Kayıtları


### Temel TCP/IP Bilgisi ve Ağ Yönetimi


### DNS Teknolojisine Giriş

* DNS sisteminin çalışması
 * Ağaç yapısı (tr -> org -> linux -> kamp)
 * Alan adı çözümleme (nsswitch, /etc/hosts, /etc/resolv.conf)
* dig, nslookup
* DNS kayıtlarının incelenmesi (A, MX, CNAME, NS, AAAA)
* Birincil (master) ve ikincil (slave) DNS kavramı
 * Yetkili (authorative)
 * Özyinelemeli (recursive) sorgu
* SOA kaydı (TTL, Refresh, Retry, Expire, Minimum)

### Güvenli Uzaktan Erişim

* SSH'a Giriş
 * Doğrulama yöntemleri (parola, anahtar, vs)
 * Şifreleme yöntemleri (simetrik, asimetrik, vs)
* sshd servisi ve ayarları
* Parolasız güvenli erişim
* ssh uzaktan komut çalıştırma
* scp ile dosyaların güvenli bir şekilde kopyalanması
* sftp ile güvenli FTP benzeri dosya aktarma erişimi
* ssh ile SOCKS vekil (proxy) sunucu
* ssh ile tünelleme ve ters tünelleme
* ssh-agent ile anahtar taşıma
* ssh ile X11 tünelleme
* ssh istemcisinin ~/.config dosyasının yapılandırılması

### Yedekleme ve Arşivleme

* rsync (ssh üzerinden) ile dizin eşitlenmesi
* tar ile arşivleme
* gzip, xz, bzip2 ve benzeri sıkıştırma yöntemleri
* Yedekleme yazılımlarının tantılması (Bacula, rdiff-backup, vs)

### Web Teknolojisine Giriş

* HTTP Protokolü ve World-Wide-Web (WWW)
* İstemci (Firefox, Chromium, vs) ve Sunucu (Apache, Nginx, vs) Yazılımları
* İstemcide (HTML, CSS; JS, vs) ve Sunucuda (PHP, Java EE, Ruby on Rails, vs) Çalışan Teknolojiler
* Uygulama Sunucuları ve Web ile Bağlantılı Diğer Servisler
* Bir Web Sayfasının Görüntülenmesi
* İstemcinin ve Sunucunun Kısıtlamaları
* GET, POST, Cookie ile Değişken Aktarımı
* SSL ile Güvenli HTTP (TLS/SSL) ve SSL Sertifikası
* HTTP Doğrulama
* HTTP Durum Kodları

### Veritabanı Servislerine Giriş

* İlişkisel veritabanı modeli
 * Veritabanı, tablo, kolon, satır kavramı
 * Birincil anahtar, yabancı anahtar
 * Örnek uygulama veritabanı tasarımı (5-6 tabloyu aşmayacak)
* SQL'e Giriş (SELECT, INSERT, UPDATE, DELETE sorguları)
* İlişkisel olmayan veritabanları tanıtımı

### Apache/PHP/MySQL Kurulumu ve Örnek Bir Uygulamanın Koşturulması

* Apache/PHP/MySQL'in paket yöneticisinden kurulumu
* phpMyAdmin web arayüzünün kurulumu
* Wordpress'in meşhur 5 dakikada kurulumu
 * MySQL'de kullanıcı oluşturulması
 * Apache'de gerekli ayarların düzenlenmesi (AllowOverride, vs)
* Kendi sunucunuza kurabileceğiniz yaygın uygulamalar (https://github.com/Kickball/awesome-selfhosted)

### Bash Betik (Script) Yazımına Giriş

* Değişken (global / yerel)
* Temel kontrol yapıları (if, for, while, ve case) ve karşılaştırma operatörleri
* Komut satırından parametre alınması
* Betik dönüş (return) kodları ve ona göre işlem yapılması
* Sık kullanılan çevresel değişkenler (tarih, kullanıcı, vs)
