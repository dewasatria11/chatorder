# ChatOrder

Landing page dan dashboard awal untuk ChatOrder: mengubah chat WhatsApp menjadi pesanan yang rapi.

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## PWA

Manifest, icon, dan service worker tersedia di `public/`. Aplikasi dapat dipasang ke layar utama perangkat dari browser yang mendukung PWA.

## Supabase

SQL database dan konfigurasi backend dapat ditambahkan pada tahap integrasi berikutnya. Jangan commit file `.env.local` atau secret API.

## WhatsApp

CTA landing page membuka WhatsApp ChatOrder ke nomor bisnis dengan pesan produk awal.

## Deployment

Proyek dapat dideploy ke Vercel menggunakan konfigurasi Vite yang tersedia.
