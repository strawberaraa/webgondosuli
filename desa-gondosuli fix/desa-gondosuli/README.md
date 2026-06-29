# 🌿 Website Desa Gondosuli

Website resmi Desa Gondosuli, Kecamatan Pakuniran, Kabupaten Probolinggo, Jawa Timur.

## 📁 Struktur Folder

```
desa-gondosuli/
├── index.html          ← Halaman utama (semua section)
├── css/
│   └── style.css       ← Design system & semua styling
├── js/
│   └── main.js         ← Interaktivitas (navbar, animasi, form)
├── images/             ← Taruh foto-foto desa di sini
│   └── (kosong, siap diisi)
└── README.md
```

## 🎨 Fitur & Section

| Section | Deskripsi |
|---------|-----------|
| **Hero** | Landing page dengan tagline, stat card, dan CTA |
| **Profil Desa** | Info lengkap desa, luas wilayah, kode pos |
| **Sejarah** | Timeline visual perjalanan desa |
| **Potensi Desa** | Komoditas & kekayaan lokal (durian, padi, tahu, dll) |
| **Wisata** | Destinasi wisata (Rengganis, Batu Sudung, dll) |
| **Peta Wilayah** | Batas desa + tombol load Google Maps |
| **Galeri** | Grid foto/ilustrasi desa |
| **Kontak** | Info kantor + form kirim pesan |
| **Footer** | Link navigasi & info singkat |

## 🚀 Cara Menjalankan di VS Code

### Metode 1 — Live Server (Rekomendasi)
1. Install ekstensi **"Live Server"** dari Ritwick Dey di VS Code
2. Klik kanan `index.html` → **"Open with Live Server"**
3. Browser otomatis terbuka di `http://127.0.0.1:5500`

### Metode 2 — Buka Langsung
1. Klik dua kali `index.html`
2. Otomatis terbuka di browser

## 🖼️ Cara Menambahkan Foto Asli

1. Taruh foto di folder `images/`
2. Ganti emoji placeholder di `index.html` dengan tag `<img>`

Contoh — ganti bagian hero image:
```html
<!-- Sebelum -->
<div class="profil-map-placeholder">🏔️</div>

<!-- Sesudah -->
<img src="images/foto-desa.jpg" alt="Pemandangan Desa Gondosuli" 
     style="width:100%;height:100%;object-fit:cover;border-radius:20px;" />
```

## 🎨 Kustomisasi Warna

Edit file `css/style.css` di bagian `:root` untuk mengubah palet warna:

```css
:root {
  --green-700: #1a5232;   /* Hijau utama navbar & tombol */
  --green-600: #22683d;   /* Aksen hijau medium */
  --green-400: #3daa67;   /* Hijau muda / highlight */
  --gold:      #c9a84c;   /* Emas untuk badge penghargaan */
}
```

## 📝 Cara Update Konten

- **Nama Kepala Desa / No. Telepon** → cari di `index.html` section `#kontak`
- **Nama-nama dusun** → cari class `dusun-pill` di `index.html`
- **Foto galeri** → ganti emoji di section `#galeri`
- **Batas wilayah** → edit `.batas-list` di section `#peta`

## 📱 Responsif

Website sudah responsif untuk:
- ✅ Desktop (1280px+)
- ✅ Laptop (1024px)
- ✅ Tablet (768px)
- ✅ HP (480px ke bawah)

## 🗺️ Peta Google Maps

Klik tombol **"Muat Peta Google Maps"** di section Peta Wilayah untuk memuat peta interaktif. Pastikan ada koneksi internet.

---
© 2025 Pemerintah Desa Gondosuli · Dibuat untuk kemajuan desa 💚
