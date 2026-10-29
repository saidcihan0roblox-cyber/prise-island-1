# 🏴‍☠️ PRISE ISLAND

Mr. Robot esintili, siyah-yeşil terminal arayüzlü **gizli arama** uygulaması. Telefona gerçek uygulama gibi kurulur (PWA), çevrimdışı açılır.

## Özellikler
- 🕶 **Gizli arama** (DuckDuckGo, Startpage, Brave, Mojeek, Qwant, Swisscows) ve 🌐 **normal arama** (Google, Bing, Yandex, YouTube, Yahoo, Ecosia, Wikipedia)
- Geçmiş yok, çerez yok, referrer gönderilmez (gizli modda)
- Araçlar: şifre üretici, SHA-256, Base64, link temizleyici, takma ad üretici
- Gizli not defteri (sadece cihaz hafızasında)
- Ters görsel arama bağlantıları, VPN/Tor rehberi
- 6 dil: Türkçe, English, Deutsch, Français, Español, Русский
- Giriş kilidi, Matrix yağmuru, FPS sayacı, PANİK düğmesi

## ⚠️ Dürüst notlar
- Bu bir **VPN değildir** ve IP adresini gizlemez. Gerçek koruma için VPN veya Tor kullan.
- Giriş kilidi sadece ekranı gizler, **gerçek güvenlik değildir** (kod tarayıcıda çalışır).
- Arama sonuçları ilgili arama motorunun sitesinde açılır.

## GitHub Pages ile yayınlama
1. GitHub'da yeni bir depo oluştur (örn. `prise-island`), **Public** seç.
2. Bu klasördeki tüm dosyaları depoya yükle (`index.html`, `manifest.json`, `sw.js`, `icon*.png`, `icon.svg`, `.nojekyll`).
3. Depoda **Settings → Pages** bölümüne gir.
4. **Source:** `Deploy from a branch`, **Branch:** `main` ve `/ (root)` seç, **Save**'e bas.
5. 1-2 dakika sonra adresin hazır: `https://KULLANICI-ADIN.github.io/prise-island/`

## Telefona uygulama gibi kurma
- **Android (Chrome):** Siteyi aç → ⋮ menüsü → **Uygulamayı yükle** / **Ana ekrana ekle**.
- **iPhone (Safari):** Siteyi aç → Paylaş → **Ana Ekrana Ekle**.

## Dosyalar
| Dosya | Görevi |
|---|---|
| `index.html` | Uygulamanın tamamı |
| `manifest.json` | Uygulama adı, simge, renkler |
| `sw.js` | Çevrimdışı çalışma |
| `icon.svg`, `icon-192.png`, `icon-512.png` | Uygulama simgeleri |
| `.nojekyll` | GitHub Pages'in dosyaları olduğu gibi sunması için |

## Lisans
Kendi lisansını seç (örn. MIT). Lisans eklemezsen kodun tüm hakları sende kalır.
