# Hero 5 — Tam ekran parallax / video — `tqg5yu` (tema-masaj)

## Amaç
Tam ekran hero: arka plan görseli (desing.img) ya da sessiz döngü video (desing.video + zorunlu poster; reduced-motion'da yalnız poster). Üstte koyu→şeffaf gradient scrim (overlay/overlayText çifti), hafif parallax (JS, reduced-motion'da kapalı), aşağı kaydır oku. desing.stil: ortali | sol | alt-serit (metin alt şeritte yarı saydam kart). Yükseklik desing.yukseklik (vh, min 480px). Üç dil + RTL.

## Meta
- version: `1.0.0`
- category: `hero`
- tags: hero, fullscreen, parallax, video, tam-ekran, ar
- icon: `fullscreen`

## Dosyalar
- `back.js` — sunucu tarafı çizim
- `index.html` — şablon
- `index.jpeg` — önizleme görseli
- `index.json` — tanım
- `README.md` — bu belge

## Not
Bu klasör siteye özel kurulum örneğidir; kurulum kaynağı `projeler/webyapar/data/tema/tema-set/icerik/masaj/spec.js` → `tema-set/araclar/demo-kur.js` (webmaker uçları). Burası elle değiştirilmez; değişiklik spec'te yapılıp yeniden kurulur.
