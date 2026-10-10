# Salına · 3D Tasarım ve Veriler

COP31 Gençlik İklim İdeathonu projesi. Kum dolu, yosundan (alginat) yapılmış, 4–5 haftada eriyen geçici yapay deniz çayırı.

- **Site:** `https://KULLANICI-ADIN.github.io/salina/`
- **QR sayfası:** `https://KULLANICI-ADIN.github.io/salina/qr.html`

## GitHub Pages'te yayınlama (5 dakika)

1. GitHub'da **New repository** → adı `salina` → **Public** seç → *Create repository*.
2. **Add file → Upload files** → bu klasördeki dosyaların **hepsini** sürükle:
   `index.html`, `qr.html`, `favicon.svg`, `.nojekyll`, `README.md`
   (Klasörü değil, içindeki dosyaları yükle. `index.html` en üst seviyede olmalı.)
3. **Commit changes**.
4. **Settings → Pages** → *Source*: **Deploy from a branch** → *Branch*: **main**, klasör: **/ (root)** → **Save**.
5. 1–2 dakika bekle. Sayfanın üstünde "Your site is live at …" yazacak.
6. `…/salina/qr.html` adresini aç → QR otomatik oluşur → **QR'ı PNG indir**.

## Sık yapılan hatalar

| Sorun | Çözüm |
|---|---|
| QR telefonda kodları gösteriyor | QR, `github.com/...` adresine gidiyor. Doğrusu `KULLANICI-ADIN.github.io/salina/` |
| 404 hatası | `index.html` bir alt klasörün içinde kalmış, ya da Pages açılmamış (4. adım) |
| Pages menüsü yok / açılmıyor | Repo **Private**. Ücretsiz hesapta repo **Public** olmalı |
| Değişiklik görünmüyor | 1–2 dakika bekle, telefonda sayfayı yenile |
