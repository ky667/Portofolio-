# Dicky Andi Ronaldi — Portfolio

Website portofolio single-page berbasis vanilla HTML, CSS, dan JavaScript. Tidak memerlukan build tools atau framework.

## Menjalankan
1. Ekstrak folder proyek.
2. Buka `index.html` di browser modern.
3. Google Fonts hanya digunakan sebagai peningkatan visual; jika offline, browser memakai font sistem.

## Struktur
- `index.html` — struktur halaman, metadata SEO, form, modal, dan footer.
- `style.css` — tema dark/light, layout responsif, animasi, aksesibilitas dasar.
- `script.js` — data proyek/pendidikan/pengalaman/sosial dan interaksi.
- `assets/cv-dicky-andi.rtf` — CV dummy yang bisa diunduh dan diedit.

## Sebelum dipublikasikan
- Edit array `education` dan `experiences` di `script.js` dengan riwayat aktual.
- Edit `socials` dengan URL LinkedIn/GitHub yang benar dan alamat email yang ingin digunakan.
- Isi `demo` dan `github` setiap proyek dengan URL yang benar. Tautan kosong sengaja tidak diarahkan ke URL palsu.
- Statistik di bagian Tentang adalah angka ilustratif/konsep, bukan klaim pengalaman kerja terverifikasi.
- Form kontak menyimpan pesan hanya ke `localStorage` browser ini. Form tidak mengirim email dan bukan backend sungguhan.
- Untuk produksi, tambahkan backend/API, proteksi spam, kebijakan privasi, dan endpoint pengiriman pesan.
