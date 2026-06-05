# Fitness PWA — Program Transformasi 6 Bulan

## File Structure
```
fitness-pwa/
├── index.html      ← App utama
├── manifest.json   ← PWA manifest
├── sw.js           ← Service Worker (offline + cache)
├── icon-192.png    ← App icon (192x192)
├── icon-512.png    ← App icon (512x512)
└── README.md       ← Panduan ini
```

## Cara Deploy ke Netlify (Paling Cepat)
1. Buka https://app.netlify.com/drop
2. Drag & drop seluruh FOLDER `fitness-pwa` ke halaman tersebut
3. Tunggu upload selesai → dapat URL seperti: `https://amazing-name-123.netlify.app`
4. Buka URL di HP → tap "Add to Home Screen"

## Cara Deploy ke GitHub Pages
1. Buat repo baru di GitHub
2. Upload semua file ke repo
3. Settings → Pages → Source: main, folder: / (root)
4. URL: `https://username.github.io/nama-repo`

## Fitur PWA
- ✅ Install ke Home Screen (Android & iOS)
- ✅ Berjalan 100% offline setelah pertama kali dibuka
- ✅ Data tersimpan di IndexedDB (tidak hilang)
- ✅ Streak tracker harian
- ✅ Progress 24 minggu tersimpan permanen
