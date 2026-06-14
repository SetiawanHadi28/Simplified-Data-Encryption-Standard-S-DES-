# S-DES Simulator

Simulasi algoritma **Simplified DES (S-DES)** — aplikasi web interaktif untuk enkripsi dan dekripsi data 8-bit menggunakan kunci 10-bit.

## Fitur
- Enkripsi & Dekripsi menggunakan algoritma S-DES
- Visualisasi langkah-langkah step-by-step (Key Generation, Round 1, Round 2, IP⁻¹)
- Tampilan bit-cell interaktif untuk tiap tahap operasi
- Tabel referensi: P10, P8, IP, IP⁻¹, EP, P4, S0, S1

## Struktur File

```
Tugas12/
├── index.html     ← Halaman utama aplikasi S-DES
├── style.css      ← Stylesheet terpisah
└── render.yaml    ← Konfigurasi deploy Render
```

## Deploy ke Render

1. Upload semua file ini ke repositori **GitHub** (public atau private)
2. Buka [render.com](https://render.com) → **New** → **Static Site**
3. Hubungkan repositori GitHub kamu
4. Isi konfigurasi:
   - **Name**: `sdes-simulator` (atau nama lain)
   - **Branch**: `main`
   - **Build Command**: *(kosongkan)*
   - **Publish Directory**: `.`
5. Klik **Create Static Site**
6. Tunggu deploy selesai — URL akan muncul otomatis

## Teknologi
- HTML5, CSS3, Vanilla JavaScript
- Font: [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono) via Google Fonts
