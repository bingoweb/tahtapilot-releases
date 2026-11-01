<p align="center">
  <img src="assets/tahtapilot-simge.png" width="110" alt="TahtaPilot">
</p>

<h1 align="center">TahtaPilot</h1>

<p align="center">Telefonundaki dosyayı akıllı tahtada aç.</p>

<!-- AUTO:LATEST -->
<p align="center"><b>Son sürüm: 0.114 (Taylan)</b> · 1 Kasım 2026 · <a href="../../releases/latest">İndir</a></p>
<!-- /AUTO:LATEST -->

## Nereden çıktı?

Merhaba, ben Taylan. Şahin Sevin İlkokulu'nda öğretmenim.

Derse hazırlandığım çalışma kâğıdı, sunum ya da kısa bir video çoğu zaman telefonumda oluyor. Ama ders tahtada işleniyor. Dosyayı tahtaya geçirmek için ya USB belleğe atıyordum ya tahtada bir hesaba giriş yapıyordum ya da dosyayı kendime e-postayla gönderiyordum. Her seferinde dersin ilk birkaç dakikası buna gidiyordu.

TahtaPilot'u bu yüzden yazmaya başladım. İstediğim şey basitti: telefondaki dosyayı seçeyim, birkaç saniye sonra tahtada açılsın.

## Nasıl kullanılıyor?

İlk seferde telefonu tahtaya bir kez tanıtıyorsun. Tahtanın kenarındaki küçük menüden "Telefonla bağlan"a dokunuyorsun, ekrana gelen kodu telefonun kamerasıyla okutuyorsun ve tahtada "Onayla"ya basıyorsun. Bu kadar.

Sonrasında telefonda "Dosya gönder"e dokunup dosyanı seçiyorsun, dosya tahtada kendiliğinden açılıyor. Sayfayı çevirmek, yakınlaştırmak, videoyu durdurmak ya da kapatmak için tahtanın yanına gitmen gerekmiyor, hepsini telefondan yapabiliyorsun.

Ertesi gün tahtadaki kodu okutman yetiyor, telefon hatırlanıyor ve tekrar onay istenmiyor.

Bunları yaparken:

- herhangi bir hesap açmıyorsun, şifre girmiyorsun,
- telefona uygulama kurmuyorsun, her şey tarayıcıda çalışıyor (Android ve iPhone),
- okulun kablosuz ağına bağlanmıyorsun, telefonun kendi internetini kullanıyorsun,
- tahtada da bir ayar yapmıyorsun, paketi bir kez kurman yeterli.

Fotoğraflar gönderilmeden önce telefonda küçültülüyor, aynı dosyayı aynı gün tekrar gönderirsen yeniden yüklenmiyor. Yani mobil veriyi de idareli kullanıyor.

## Ne gönderebiliyorum?

PDF, Word, PowerPoint ve Excel dosyaları, fotoğraflar ve resimler, video ve ses dosyaları. Bir web adresini de gönderebiliyorsun, tahtanın tarayıcısında açılıyor. Word, PowerPoint ve Excel dosyaları tahtada sayfa sayfa gösteriliyor.

## Şu an ne durumda?

Proje hâlâ geliştirme aşamasında. Kendi sınıfımdaki tahtada deneyerek ilerliyorum.

<!-- AUTO:STATUS -->
Bitenler:

- tahtanın güvenli şekilde sunucuya bağlanması,
- okul logosunun ve okula özel görünümün tahtada ve telefonda gösterilmesi,
- telefonu tahtaya QR kodla bir kez tanıtma; telefonun ertesi gün de hatırlanması,
- tahtayı telefondan yönetme (sayfa çevirme, yakınlaştırma, videoyu durdurma),
- tahtanın yeni sürümleri kendi kendine, şifre sormadan kurması,
- PDF, Word, PowerPoint, Excel, fotoğraf, video ve ses dosyalarının tahtada açılması.

Üzerinde çalıştıklarım:

- telefondaki "Dosya gönder", "Web adresi gönder" ve "Fotoğraf çek" düğmeleri,
- web adresini tahtada açma.

İlk sürümle gelecekler:

- Android telefonlarda başka bir uygulamada açık olan dosyayı "Paylaş" menüsünden doğrudan tahtaya gönderme.
<!-- /AUTO:STATUS -->

Sonrası için aklımda olanlar: derste gönderdiğin dosyaları tek dokunuşla yeniden açabileceğin bir "çanta", sayaç ve "Bana bakın" ekranı gibi küçük sınıf araçları, okuldaki tahtaları tek yerden görebileceğin bir yönetim ekranı.

## Ekran görüntüleri

Arayüzler bittikçe buraya ekleyeceğim.

<!-- AUTO:SCREENSHOTS -->
<!-- /AUTO:SCREENSHOTS -->

## Gizlilik

Öğrencilere ait hiçbir bilgi (ad, numara, fotoğraf, not) saklanmıyor, tahtanın dışına da çıkmıyor. Gönderdiğin dosyalar aktarım için en fazla 8 saat tutulup siliniyor, tahtada da 7 gün sonra kendiliğinden siliniyor. Dosya adları hiçbir yerde tutulmuyor. Hesap olmadığı için senden kişisel bir bilgi de istenmiyor.

## Kurulum

İlk sürüm çıktığında [Sürümler](../../releases) bölümünden son `.deb` dosyasını indirip tahtada çift tıklaman yeterli olacak. Pardus Paket Yükleyici gerekli her şeyi kendisi kuruyor, sadece yönetici parolası soruyor.

Sonraki güncellemeleri tahta kendisi kuruyor. Yeni bir sürüm çıktığında tahta bunu birkaç saniye içinde fark ediyor ve kimseye bir şey sormadan, şifre istemeden kendini güncelliyor.

## Sürümler

<!-- AUTO:HISTORY -->
| Sürüm | Tarih | Yenilikler |
| --- | --- | --- |
| 0.112 | 1 Kasım 2026 | Tahta, telefonla yönetilmediği zamanlarda Pardus güncellemelerini de sessizce kendisi kuruyor. |
| 0.111 | 1 Kasım 2026 | Yeni sürümler yayımlandığı anda bütün tahtalara kuruluyor. |
| 0.110 | 1 Kasım 2026 | Bir güncelleme kurulamazsa tahta kendiliğinden önceki sürüme dönüyor. |
| 0.109 | 1 Kasım 2026 | Bağlantı koptuğunda başarısız sayılan bir komut, bağlantı geri gelince artık kendiliğinden çalışmıyor. |
| 0.107 | 1 Kasım 2026 | Bir telefon iki tahtayla eşleştiyse, en son kodunu okuttuğun tahtaya bağlanıyor. |
| 0.103 | 1 Kasım 2026 | Bir videodan başka bir dosyaya hızlıca geçince yeni dosya artık kendiliğinden duraklamıyor. |
| 0.097 | 31 Ekim 2026 | Tahta videoyu kendiliğinden oynatamazsa "dosya açılamıyor" demek yerine videoyu duraklatıyor. |
| 0.096 | 31 Ekim 2026 | Dosya açılırken hemen verilen komutlar (sayfa çevirme gibi) kaybolmuyor. |
| 0.095 | 31 Ekim 2026 | Takılan bir Word ya da PowerPoint dönüştürmesi sonraki dosyaları artık engellemiyor. |
| 0.094 | 31 Ekim 2026 | Tahtanın kendi kendini denetlemesi artık PDF, video ve ses açmayı da deniyor. |
<!-- /AUTO:HISTORY -->

## Kullanım

TahtaPilot ücretsiz. İsteyen her öğretmen ve okul kurup kullanabilir. Ayrıntılar [LICENSE.md](LICENSE.md) dosyasında.

Bir sorun yaşarsan ya da bir fikrin olursa sayfanın üstündeki "Issues" bölümünden yazabilirsin.

<p>
  <img src="assets/gelistirici.gif" width="300" alt="Taylan Soylu">
</p>

<img src="assets/okul-logosu.png" width="80" alt="Şahin Sevin İlkokulu">
