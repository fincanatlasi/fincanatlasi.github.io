# fincanatlasi.github.io

Fincan Atlası web sitesi (GitHub Pages, `fincanatlasi` organizasyonu).

- `index.html` — tanıtım sayfası
- `404.html` — paylaşım (`/f/<token>`) ve davet (`/davet/<kod>`) linkleri: fal web'de gösterilmez; Android'de
  Google Play'e (referrer ile), iPhone'da App Store'a yönlendirir. Uygulama yüklüyse link doğrudan uygulamayı açar.
- `.well-known/assetlinks.json` — Android App Links doğrulaması. Şu an yalnızca test sürümü
  (`app.fincanatlasi.dev`, Expo debug anahtarı). Play'e çıkınca `app.fincanatlasi` + Play Console
  "App signing" SHA-256 parmak izi eklenecek.
- `.nojekyll` — `.well-known` klasörünün yayınlanması için gerekli.
