# AVIF Browser

**Amanin Visibilitas Internetmu, Full-Privasi!**  
AVIF Browser adalah modifikasi dari Chromium yang fokus pada privasi, keamanan, dan pengalaman browsing bebas iklan.

---

## Fitur Utama

- **Tanpa Tracking** — Privasi total, tanpa Google telemetry.
- **Adblocker Bawaan** — Langsung blok iklan tanpa ekstensi tambahan.
- **Dark Mode Default** — UI minimalis & nyaman untuk mata.
- **Branding Full Custom** — Bukan Chromium biasa, ini AVIF!

---

## Build dengan CircleCI

Project ini tidak menyertakan full source Chromium (karena ukurannya besar). Sebagai gantinya, kami:
- Fetch Chromium dari repo resmi
- Apply patch modifikasi
- Build otomatis menggunakan CircleCI

---

## Struktur Project

avif-browser/ ├── .circleci/              # Konfigurasi CI ├── patches/                # Patch Chromium (UI, privasi, branding, dll) ├── build.sh                # Script otomatis untuk fetch + patch + build ├── build-config/args.gn    # Konfigurasi build Chromium └── README.md

---

## Cara Build Manual (Optional)

```bash
# Clone repo ini
git clone https://github.com/yourname/avif-browser.git
cd avif-browser

# Jalankan script build
chmod +x build.sh
./build.sh

> Hasil build bisa ditemukan di folder avif-browser-build/




---

Work in Progress

[ ] UI Panel untuk toggle fitur privasi

[ ] Shortcut keyboard custom

[ ] Build untuk Android

[ ] Logo & splash screen baru



---

Kontribusi

Feel free buat ngajuin PR, issue, atau ide gila! Kita terbuka banget buat yang peduli soal privasi & internet bebas.


---

Lisensi

BSD License mengikuti lisensi Chromium.


---

AVIF Browser dibuat dengan semangat oleh komunitas yang cinta privasi & kebebasan digital.

---

