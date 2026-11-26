# Booking Gunung

Website landing page **Booking Gunung** – *Submit Langsung Summit*.
Layanan booking SIMAKSI pendakian: cek kuota real-time, proses cepat dan praktis, aman dan terpercaya.

Dibuat sebagai bagian dari Tugas 1 Strategy Brand Communication (UNDIRA).

## Struktur

```
booking-gunung/
├── index.html
├── css/style.css
├── assets/
│   ├── logo.svg
│   └── poster.jpg
├── vercel.json
└── README.md
```

Website ini statis (HTML + CSS), tanpa build step.

## Jalankan lokal

Buka `index.html` di browser, atau:

```bash
npx serve .
```

## Push ke GitHub

```bash
git init
git add .
git commit -m "Initial commit: website Booking Gunung"
git branch -M main
git remote add origin https://github.com/USERNAME/booking-gunung.git
git push -u origin main
```

## Deploy ke Vercel

1. Masuk ke [vercel.com](https://vercel.com) dan login dengan GitHub.
2. Klik **Add New → Project**, lalu import repo `booking-gunung`.
3. **Framework Preset:** Other. Kosongkan Build Command dan Output Directory.
4. Klik **Deploy**.

Domain kustom (misalnya `bookinggunung.id`) bisa ditambahkan di **Settings → Domains**.
