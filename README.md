# Kas Angkringan

Aplikasi web (PWA) untuk mencatat penjualan, pengeluaran, dan kasbon angkringan, plus cetak struk. Bisa dipasang di HP, laptop, dan komputer, dan tetap jalan tanpa internet.

## Pasang di GitHub Pages
1. Buat repository baru di GitHub (misalnya `kas-angkringan`).
2. Unggah semua isi folder ini (`index.html`, `sw.js`, `manifest.webmanifest`, folder `icons`) ke repository.
3. Buka **Settings > Pages**. Pada *Build and deployment*, pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu **Save**.
4. Tunggu 1-2 menit. Alamat aplikasi: `https://NAMA-GITHUB-ANDA.github.io/kas-angkringan/`

## Pasang sebagai aplikasi
- **Android (Chrome)**: buka alamatnya, ketuk menu titik tiga, lalu **Instal aplikasi** / **Tambahkan ke layar utama**. Bisa juga lewat tombol "Pasang aplikasi" di tab Hari ini.
- **iPhone/iPad (Safari)**: ketuk **Bagikan**, lalu **Tambah ke Layar Utama**.
- **Windows/Mac/Linux (Chrome atau Edge)**: klik ikon pasang di ujung kanan kolom alamat, lalu **Instal**.

## Catatan
- Data tersimpan di perangkat masing-masing (localStorage), tidak otomatis sinkron antar perangkat. Hapus data browser berarti data hilang, jadi rutin unduh CSV dari tab Hari ini.
- Setelah mengubah file, naikkan angka versi `CACHE` di `sw.js` (misalnya `v2`) agar pengguna mendapat versi terbaru.
- Cetak struk memakai fitur cetak bawaan browser (lebar kertas 58 mm). Printer perlu terhubung ke perangkat.
