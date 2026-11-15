# gitarnota.com güncellemesi: Nota Arşivi

Bu klasördeki dosyalar gitarnota.com'a Nota Arşivi'ni ekler. Site Wix Headless üzerinde, kodla yazılmış HTML dosyalarından oluşuyor. Bu dosyaları siteyi ilk kuran yöntemle yükleyin; aynı adlı dosyaların yerine geçerler.

## Yeni dosyalar
- `nota-arsivi.html`: Nota Arşivi sayfası. Sitenin üst menüsü, ahşap teması ve alt bilgisiyle birlikte gelir.
- `gn-card-7.jpg`: Ana sayfadaki Nota Arşivi kartının görseli.

## Değişen dosyalar
- `index.html`: Üst menüye "🎼 Nota Arşivi" düğmesi ve Uygulamalar bölümüne "Nota Arşivi" kartı eklendi. Menüde 7 düğme olduğu için tablet ve telefonda son düğme tam genişlikte gösteriliyor.
- `oyunlar.html`, `akor-pro.html`, `gitar-akor-atolyesi.html`, `gitar-nota-metronom.html`, `gitar-nota-v18.html`, `kare-bulmaca.html`, `muzik-kelime-avcisi.html`, `nota-eslestirme.html`, `nota-ogretmeni.html`: Her sayfanın üst menüsüne yalnızca "🎼 Nota Arşivi" bağlantısı eklendi. Başka bir şey değişmedi.

## Notalar nereden yükleniyor
380 PDF Wix'e yüklenmiyor. Sayfa notaları şu adresten açıyor:
`https://gitarnota.github.io/gitar-nota-arsivi/notalar/`

Bunun için bu depoda GitHub Pages açık olmalı: Settings → Pages → Deploy from a branch → `main` / `(root)`.
