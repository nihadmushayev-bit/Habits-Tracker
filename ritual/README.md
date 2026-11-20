# Ritüel — Günlük Alışkanlıklar

Türkçe açılan, İngilizceye geçiş düğmesi olan kişisel alışkanlık takipçisi. Sade koyu arayüz, geri getirilen yeşil vurgu rengi ve minimal onay simgesi. Antrenman haftada 3, koşu haftada 2 esnek seans olarak gelir; bu hedefleri uygulamada değiştirebilirsin. Verilerin yalnızca kullandığın cihazın tarayıcısında saklanır.

## iPhone 13'e ücretsiz ekleme

Bu paket bir `.ipa` dosyası değil; Safari'den ana ekrana eklenen bir web uygulamasıdır. **VPN ve Aygıt Yönetimi bölümüne profil olarak yüklenmez.** O bölüm, Apple tarafından imzalanmış ve genellikle bir kuruluşun Enterprise programıyla dağıttığı yerel uygulamalar içindir. Apple, Enterprise dağıtımını kuruluş içi uygulamalar için tanımlar ([Apple açıklaması](https://support.apple.com/en-gb/118254)).

Kişisel kullanım için Apple hesabıyla Xcode üzerinden imzalama ücretsiz olabilir; ancak Xcode bir Mac gerektirir ve ücretsiz kişisel profiller 7 gün sonra yeniden oluşturulup yüklenmelidir ([Apple Developer hesabı](https://developer.apple.com/help/account/basics/about-your-developer-account/), [Xcode'da cihaza yükleme](https://developer.apple.com/documentation/xcode/building-and-running-an-app)). Bu çalışma alanında imzalı `.ipa` oluşturamam. En kolay ücretsiz kurulum Safari'den ana ekrana eklemektir; bunun için uygulamayı güvenli (`https://`) bir adreste yayınlayabilirsin.

1. ZIP dosyasını Windows bilgisayarında aç.
2. Ücretsiz GitHub hesabına giriş yap ve `rituel-aliskanliklar` gibi **public** (herkese açık) bir depo oluştur.
3. `index.html`, `manifest.json`, `sw.js`, `icon.svg` ve `icon-*.png` dosyalarını deponun ana klasörüne yükle.
4. Depoda **Settings → Pages** bölümünü aç. **Deploy from a branch** seç; dal olarak `main`, klasör olarak `/(root)` seçip kaydet. GitHub, yayınlanınca sana web adresini gösterir.
5. iPhone'da **Safari**'yi aç ve bu web adresine git. **Paylaş → Ana Ekrana Ekle** seç. **Web Uygulaması Olarak Aç** seçeneğini etkinleştir, sonra **Ekle**'ye dokun. Ritüel simgesi ana ekranda görünür ve ayrı uygulama penceresinde açılır ([Apple yönergeleri](https://support.apple.com/en-az/guide/iphone/iphea86e5236/26/ios)).

GitHub'da uygulamanın dosyaları herkese açık olur; kişisel alışkanlık kayıtların GitHub'a gönderilmez ve yalnızca iPhone'undaki tarayıcıda kalır. Bağlantıyı paylaşmazsan uygulamayı yalnızca sen kullanırsın. Verilerini ara sıra **Ayarlar → JSON dışa aktar** ile yedekleyebilirsin.

## Daha önceki sürümü güncelleme

Yeni paketteki uygulama dosyalarını aynı GitHub Pages deposuna yükleyip eskilerin üzerine yaz. iPhone'da Safari ile siteyi bir kez çevrimiçiyken aç, ardından ana ekrandaki Ritüel simgesini kapatıp yeniden aç. Yeni ikon görünmezse eski ana ekran simgesini kaldırıp Safari'den tekrar **Ana Ekrana Ekle**. Mevcut kayıtların korunur; **Antrenman** ve **Koşu** yoksa otomatik eklenir.

## Dil

Uygulama Türkçe başlar. Sağ üstteki **TR · EN** düğmesine dokunarak arayüz dilini istediğin zaman değiştirebilirsin. Seçimin cihazda hatırlanır.


## Gizlilik ve güvenlik

Alışkanlık kayıtları cihazındaki tarayıcıda saklanır. Uygulama VPN profili veya kurumsal sertifika istemez; sayfa dosyalarında üçüncü taraf uzaktan JavaScript/CSS kaynağı yoktur. Yine de hiçbir yazılım için mutlak virüssüzlük garantisi verilemez; paketi yalnızca bu bağlantıdan indir.

