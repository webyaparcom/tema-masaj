# Menü 10 — Şeffaf overlay — `9zt0aj` (tema-masaj)

## Amaç
Hero'nun üstüne binen şeffaf menü (position:absolute): başlangıçta şeffaf zemin + açık yazı (menutextOverlay) ve altında ince koyu gradient scrim; kaydırınca 300 ms'de katı zemine (menubg/menutext) geçer ve sabitlenir. Sayfada hero yoksa (#content ilk çocuğu data-mx-hero / *-hero değilse) baştan katı ve akışta. Mobil: tam ekran panel. desing.stil: sade | cta-butonlu (sağda vurgulu düğme). Dil seçici {{langbar}}. Üç dil + RTL.

## Meta
- version: `1.0.0`
- category: `menu`
- tags: menu, overlay, seffaf, transparent, hero, sticky, ar
- icon: `layers`

## Dosyalar
- `back.js` — sunucu tarafı çizim
- `index.html` — şablon
- `index.jpeg` — önizleme görseli
- `index.json` — tanım
- `README.md` — bu belge

## Not
Bu klasör siteye özel kurulum örneğidir; kurulum kaynağı `projeler/webyapar/data/tema/tema-set/icerik/masaj/spec.js` → `tema-set/araclar/demo-kur.js` (webmaker uçları). Burası elle değiştirilmez; değişiklik spec'te yapılıp yeniden kurulur.
