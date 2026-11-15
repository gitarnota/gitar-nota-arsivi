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

## Güncelleme: notaları dinleme
`nota-arsivi.html` yenilendi. Görüntüleyiciye “Çal” düğmesi, hız seçimi (%50–%125) ve ilerleme çubuğu eklendi. Ses, her notanın MIDI kaydından tarayıcıda üretiliyor. MIDI dosyaları da notalar gibi GitHub Pages'te duruyor (`notalar/*.mid`). Bu güncelleme için Wix'e yalnızca `nota-arsivi.html` dosyasının yeniden yüklenmesi yeterli. Diğer 11 dosya değişmedi.

## Güncelleme: Akademi çalışmaları
`nota-arsivi.html` yenilendi. Arşivin en üstüne iki koleksiyon eklendi: Giuliani Op. 51'in parmak numaralı akademi baskısı (No. 1–4) ve 18 etüdün tamamı (Gökay Salkım dizimi). Yeni PDF ve MIDI dosyaları GitHub Pages'te (`notalar/m9000xx`). Wix'e yine yalnızca `nota-arsivi.html` yüklenecek.

## Düzeltme
Op. 51'in tam dizisi (No. 1–18) ve La Partida arşivden kaldırıldı: kaynak dosyaları başka bir MuseScore kullanıcısının hesabından geliyor. Akademi çalışmalarında yalnızca Gökay Salkım'ın parmak numaralı Op. 51 No. 1–4 baskısı kaldı. `nota-arsivi.html` yeniden yüklenmeli.

## Düzeltme 2
Op. 51 tam dizi (No. 1–18) geri eklendi: dizim Marieh'e ait ve copyleft olarak paylaşılmış (PDF altbilgisi: "Marieh 2018 Copyleft"). Künyeler buna göre yazıldı. La Partida dışarıda kalıyor. `nota-arsivi.html` yeniden yüklenmeli.

## R'nin canlı sitedeki iyileştirmeleri kaynağa alındı
Oynatıcıya ses düzeyi çubuğu ve gerçek gitar kaydı (Meta Nylon Guitar Fingerstyle, CC0; `klasik-gitar-meta-v1.mp3`) eklendi. Kayıt yüklenemezse tarayıcıda üretilen gitar sesine dönülür. Bu klasördeki `nota-arsivi.html` canlıdakiyle birebir aynı. `klasik-gitar-meta-v1.mp3` canlı sitenin kökünde duruyor; depoda da kökte bir kopyası var (GitHub Pages sürümü için).

**Önemli:** Canlı sitede doğrudan değişiklik yaparsan, aynı değişikliği bu depoya da gönder (ya da Gökay'a haber ver). Yoksa bir sonraki güncellemede kaybolur.
