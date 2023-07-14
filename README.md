<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>Bug Bounty Kontrol Listesi</h1>
  
  <h2><span class="checkmark">&#10003;</span>Wildcard Alanı Hakkında Keşif</h2>
  <ul>
    <li>Amass çalıştır</li>
    <li>Subfinder çalıştır</li>
    <li>Assetfinder çalıştır</li>
    <li>Dnsgen çalıştır</li>
    <li>Massdns çalıştır</li>
    <li>Httprobe kullan</li>
    <li>Aquatone çalıştır (canlı ana sayfa ekran görüntüsü)</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Tek Alan</h2>
  <h3>Tarama</h3>
  <ul>
    <li>Nmap taraması</li>
    <li>Burp crawler</li>
    <li>ffuf (dizin ve dosya fuzzing'i)</li>
    <li>hakrawler/gau/paramspider</li>
    <li>Linkfinder</li>
    <li>Android uygulamasıyla ilişkili URL</li>
  </ul>
  
  <h3>Elle Kontrol Etme</h3>
  <ul>
    <li>Shodan</li>
    <li>Censys</li>
    <li>Google dorks</li>
    <li>Pastebin</li>
    <li>Github</li>
    <li>OSINT</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Bilgi Toplama</h2>
  <ul>
    <li>Siteyi el ile keşfetme</li>
    <li>Gözden kaçan veya gizli içeriği için örümcek/gezinme</li>
    <li>Robots.txt, sitemap.xml, .DS_Store gibi içeriği ifşa eden dosyaları kontrol etme</li>
    <li>Ana arama motorlarının önbelleğini kamu erişilebilir siteler için kontrol etme</li>
    <li>Kullanıcı Aracı'na dayalı içerik farklılıklarını kontrol etme (örneğin, Mobil siteler, Arama motoru tarayıcısı olarak erişim)</li>
    <li>Web Uygulaması Parmak İzi Alma</li>
    <li>Kullanılan teknolojileri belirleme</li>
    <li>Kullanıcı rollerini belirleme</li>
    <li>Uygulama giriş noktalarını belirleme</li>
    <li>İstemci tarafı kodunu belirleme</li>
    <li>Birden çok sürüm/kanalı belirleme (örneğin, web, mobil web, mobil uygulama, web hizmetleri)</li>
    <li>Birlikte barındırılan ve ilgili uygulamaları belirleme</li>
    <li>Tüm ana bilgisayar adlarını ve portları belirleme</li>
    <li>Üçüncü taraf barındırılan içeriği belirleme</li>
    <li>Hata ayıklama parametrelerini belirleme</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Yapılandırma Yönetimi</h2>
  <ul>
    <li>Sık kullanılan uygulama ve yönetici URL'lerini kontrol etme</li>
    <li>Eski, yedek ve başvurulmayan dosyaları kontrol etme</li>
    <li>Desteklenen HTTP yöntemlerini ve Cross Site Tracing (XST) 'yi kontrol etme</li>
    <li>Dosya uzantılarının işlenmesini test etme</li>
    <li>Güvenlik HTTP başlıklarını (örneğin, CSP, X-Frame-Options, HSTS) kontrol etme</li>
    <li>Politikaları kontrol etme (örneğin, Flash, Silverlight, robots)</li>
    <li>Canlı ortamda duyarlı olmayan veri ve bunun tam tersini kontrol etme</li>
    <li>İstemci tarafında hassas veri kontrolü (örneğin, API anahtarları, kimlik bilgileri)</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Güvenli İletişim</h2>
  <ul>
    <li>SSL Sürümünü, Algoritmalarını, Anahtar uzunluğunu kontrol etme</li>
    <li>Dijital Sertifika Geçerliliğini kontrol etme (Süre, İmza ve CN)</li>
    <li>Kimlik bilgilerinin sadece HTTPS üzerinden iletilmesini kontrol etme</li>
    <li>Oturum açma formunun HTTPS üzerinden iletilmesini kontrol etme</li>
    <li>Oturum belirteçlerinin sadece HTTPS üzerinden iletilmesini kontrol etme</li>
    <li>HTTP Strict Transport Security (HSTS) kullanımını kontrol etme</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Kimlik Doğrulama</h2>
  <ul>
    <li>Kullanıcı numaralandırmasını test etme</li>
    <li>Kimlik doğrulama bypass'ını test etme</li>
    <li>Bruteforce korumasını test etme</li>
    <li>Parola kalite kurallarını test etme</li>
    <li>Beni hatırla işlevselliğini test etme</li>
    <li>Parola formlarında/alanlarında otomatik tamamlamayı test etme</li>
    <li>Parola sıfırlama ve/veya kurtarma işlemini test etme</li>
    <li>Parola değiştirme sürecini test etme</li>
    <li>CAPTCHA'yı test etme</li>
    <li>Çok faktörlü kimlik doğrulamayı test etme</li>
    <li>Oturumu kapatma işlevselliğinin varlığını test etme</li>
    <li>HTTP üzerinde önbellek yönetimini test etme (örn. Pragma, Expires, Max-age)</li>
    <li>Varsayılan girişleri test etme</li>
    <li>Kullanıcı erişilebilir kimlik doğrulama geçmişini test etme</li>
    <li>Hesap kilitlenmeleri ve başarılı parola değişikliklerinin dış kanal bildirimini test etme</li>
    <li>Paylaşılan kimlik doğrulama şeması/SSO ile birden çok uygulama arasında tutarlı kimlik doğrulamayı test etme</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Oturum Yönetimi</h2>
  <ul>
    <li>Oturum yönetiminin nasıl ele alındığını belirleme (örneğin, çerezlerde belirteçler, URL'de belirteç)</li>
    <li>Oturum belirteçlerini çerez bayrakları (httpOnly ve secure) açısından kontrol etme</li>
    <li>Oturum çerezi kapsamını kontrol etme (yol ve etki alanı)</li>
    <li>Oturum çerezi süresini kontrol etme (sona erme ve max-age)</li>
    <li>Maksimum ömür süresinden sonra oturumu sonlandırma kontrolü</li>
    <li>İlişkisel zaman aşımından sonra oturumu sonlandırma kontrolü</li>
    <li>Oturumu kapatmadan sonra oturumu sonlandırma kontrolü</li>
    <li>Kullanıcıların eşzamanlı olarak birden fazla oturuma sahip olup olamayacağını test etme</li>
    <li>Oturum çerezlerini rastgeleliğe göre test etme</li>
    <li>Yeni oturum belirteçlerinin verildiğini doğrulama (oturum açma, rol değişikliği, oturum kapatma)</li>
    <li>Paylaşılan oturum yönetimi olan uygulamalar arasında tutarlı oturum yönetimini test etme</li>
    <li>Oturum bulmacasını test etme</li>
    <li>CSRF ve clickjacking için test etme</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Yetkilendirme</h2>
  <ul>
    <li>Yol geçişini test etme</li>
    <li>Yetkilendirme şemasını atlatma testi</li>
    <li>Dikey Erişim kontrol sorunlarını test etme (aynı ayrıcalık düzeyine sahip iki kullanıcı arasında)</li>
    <li>Eksik yetkilendirme kontrolü</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Data Doğrulama</h2>
  <ul>
    <li>Yansıtılan XSS (Cross Site Scripting) testi</li>
    <li>Depolanan XSS (Cross Site Scripting) testi</li>
    <li>DOM tabanlı XSS (Cross Site Scripting) testi</li>
    <li>Cross Site Flashing testi</li>
    <li>HTML Injection testi</li>
    <li>SQL Injection testi</li>
    <li>LDAP Injection testi</li>
    <li>ORM Injection testi</li>
    <li>XML Injection testi</li>
    <li>XXE Injection testi</li>
    <li>SSI Injection testi</li>
    <li>XPath Injection testi</li>
    <li>XQuery Injection testi</li>
    <li>IMAP/SMTP Injection testi</li>
    <li>Kod Enjeksiyonu testi</li>
    <li>Expression Language Injection testi</li>
    <li>Komut Enjeksiyonu testi</li>
    <li>Taşma (Stack, Heap ve Tamsayı) testi</li>
    <li>Format String testi</li>
    <li>İncübiltebulguların testi</li>
    <li>HTTP Splitting/Smuggling testi</li>
    <li>HTTP Verb Tampering testi</li>
    <li>Açık Yönlendirme testi</li>
    <li>Yerel Dosya Ekleme testi</li>
    <li>Uzaktan Dosya Ekleme testi</li>
    <li>Kişisel veri doğrulama kurallarını karşılaştırma</li>
    <li>NoSQL enjeksiyonu testi</li>
    <li>HTTP parametre kirliliği testi</li>
    <li>Otomatik bağlama testi</li>
    <li>Toplu atama testi</li>
    <li>NULL/Geçersiz Oturum Çerezi testi</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Hizmet Reddi (DoS)</h2>
  <ul>
    <li>Anti-otomasyon testi</li>
    <li>Hesap kilitlenmesi testi</li>
    <li>HTTP protokol DoS testi</li>
    <li>SQL joker karakter DoS testi</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>İş Mantığı</h2>
  <ul>
    <li>Özellik kötüye kullanımı testi</li>
    <li>Yalanlama olmaması testi</li>
    <li>Güven ilişkileri testi</li>
    <li>Verinin bütünlüğü testi</li>
    <li>Görevlerin ayrımı testi</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Kriptografi</h2>
  <ul>
    <li>Verilerin şifrelenmesi gerekip gerekmediğini kontrol etme</li>
    <li>Kontekste bağlı olarak yanlış algoritma kullanımını kontrol etme</li>
    <li>Zayıf algoritma kullanımını kontrol etme</li>
    <li>Tuzlama işleminin doğru kullanımını kontrol etme</li>
    <li>Rastgelelik fonksiyonlarını kontrol etme</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Riskli İşlevsellik - Dosya Yüklemeleri</h2>
  <ul>
    <li>Kabul edilebilir dosya türlerinin beyaz liste olarak belirlendiğini kontrol etme</li>
    <li>Dosya boyutu sınırlarının, yükleme sıklığı ve toplam dosya sayısının tanımlandığını ve uygulandığını kontrol etme</li>
    <li>Dosya içeriğinin belirlenen dosya türüyle eşleştiğini kontrol etme</li>
    <li>Tüm dosya yüklemelerinde Anti-Virüs taramasının yapıldığını kontrol etme</li>
    <li>Güvensiz dosya adlarının düzgün bir şekilde temizlendiğini kontrol etme</li>
    <li>Yüklenen dosyaların doğrudan web kökünde erişilemez olduğunu kontrol etme</li>
    <li>Yüklenen dosyaların aynı ana bilgisayarda/aynı portta sunulmadığını kontrol etme</li>
    <li>Dosyaların ve diğer ortamların kimlik doğrulama ve yetkilendirme şemalarıyla entegre olduğunu kontrol etme</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>Riskli İşlevsellik - Kart Ödemeleri</h2>
  <ul>
    <li>Web Sunucusu ve Web Uygulamasında bilinen zayıflıkları ve yapılandırma sorunlarını kontrol etme</li>
    <li>Varsayılan veya tahmin edilebilir parolaları kontrol etme</li>
    <li>Canlı ortamda duyarlı olmayan veri ve bunun tam tersini kontrol etme</li>
    <li>Enjeksiyon zafiyetleri için test etme</li>
    <li>Tampon Taşmaları için test etme</li>
    <li>Güvenli Olmayan Kriptografik Saklama için test etme</li>
    <li>Yetersiz Taşıma Katmanı Koruması için test etme</li>
    <li>Hatalı Hata İşleme için test etme</li>
    <li>CVSS v2 skoru > 4.0 olan tüm zafiyetler için test etme</li>
    <li>Kimlik doğrulama ve yetkilendirme sorunları için test etme</li>
    <li>CSRF için test etme</li>
  </ul>
  
  <h2><span class="checkmark">&#10003;</span>HTML 5</h2>
  <ul>
    <li>Web Mesajlaşmasını test etme</li>
    <li>Web Depolama SQL enjeksiyonu için test etme</li>
    <li>CORS uygulamasını kontrol etme</li>
    <li>Çevrimdışı Web Uygulaması kontrolü</li>
  </ul>

</body>
</html>
