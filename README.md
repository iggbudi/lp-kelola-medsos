# SobatSosmed — Jasa Kelola Media Sosial UMKM Jawa Tengah

Landing page promosi untuk **SobatSosmed**, agensi lokal yang menyediakan jasa pengelolaan media sosial khusus UMKM di wilayah Jawa Tengah.

---

## Tentang Proyek

SobatSosmed hadir untuk membantu pelaku UMKM Jawa Tengah tampil profesional di media sosial tanpa harus pusing mengurus konten sendiri. Halaman ini menampilkan layanan, paket harga, dan ajakan konsultasi gratis via WhatsApp.

## Fitur Halaman

- **Navigasi** — Menu tetap (sticky) dengan link ke setiap seksi dan tombol CTA konsultasi gratis
- **Hero Section** — Headline utama dengan dua tombol aksi (lihat harga & pelajari dulu)
- **Masalah UMKM** — Tiga pain point umum yang dihadapi pelaku UMKM
- **Solusi Kami** — Penjelasan layanan: foto produk, video Reels/TikTok, desain & caption, analisa akun
- **Harga Paket** — Tiga pilihan paket bulanan (Sedulur, Juragan, Sultan)
- **CTA Kontak** — Tombol langsung ke WhatsApp
- **Footer** — Link media sosial (Instagram, Facebook, TikTok)

## Paket Layanan

| Paket | Harga | Highlight |
|---|---|---|
| **Sedulur** | Rp 499.000/bln | 12 konten, 1x kunjungan foto/video |
| **Juragan** | Rp 999.000/bln | 20 konten, admin DM & komen, FB/IG Ads dasar |
| **Sultan** | Rp 1.900.000/bln | 30 konten harian, full admin, manajemen iklan profesional |

## Teknologi

- **HTML5** — Struktur halaman
- **Tailwind CSS** (via CDN) — Styling dan layout responsif dengan tema warna kustom (Teal, Sage, Green)
- **Google Fonts** — Tipografi Inter
- **Lucide Icons** (via CDN) — Ikon antarmuka

## Cara Menjalankan

Tidak memerlukan build tool atau instalasi apapun. Cukup buka file langsung di browser:

```bash
# Buka langsung di browser
start index.html
```

Atau gunakan ekstensi **Live Server** di VS Code untuk preview dengan auto-reload.

## Struktur File

```
.
└── index.html   # Seluruh halaman dalam satu file (HTML + CSS inline + JS)
```

## Kustomisasi

- **Nomor WhatsApp** — Ganti `628123456789` di link `https://wa.me/628123456789` pada seksi kontak
- **Warna tema** — Konfigurasi Tailwind ada di blok `<script>` di bagian `<head>`
- **Harga & fitur paket** — Edit langsung di seksi `#harga`
- **Menu mobile** — Logika toggle menu mobile saat ini menampilkan `alert()`, perlu dikembangkan sesuai kebutuhan

---

&copy; 2024 SobatSosmed Jateng. Melayani dengan amanah untuk UMKM Jawa Tengah.
