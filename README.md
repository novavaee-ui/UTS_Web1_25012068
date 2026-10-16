# UTS Web 1 — Sistem Pemesanan Menu Kantin

## Identitas Pengembang

- **Nama:** Nur Fadilah
- **NIM:** 25012068
- **Kelas:** 25M31

## Deskripsi Proyek

Aplikasi web pemesanan menu kantin yang dibuat menggunakan PHP Native. Aplikasi ini menyediakan daftar menu, pencarian menu, filter kategori, pengelolaan keranjang, validasi jumlah pesanan, dan preferensi favorit.

## Teknologi yang Digunakan

- PHP Native
- HTML
- CSS
- JavaScript (jika digunakan pada implementasi)
- Session PHP dan Cookie
- XAMPP
- Git dan GitHub

## Fitur Aplikasi

1. Menampilkan daftar menu kantin.
2. Mencari menu berdasarkan kata kunci.
3. Memfilter menu berdasarkan kategori.
4. Menambahkan menu ke keranjang.
5. Memvalidasi jumlah pesanan.
6. Menghapus menu dari keranjang.
7. Mengosongkan keranjang.
8. Menyimpan preferensi favorit menggunakan cookie, jika fitur tersebut diterapkan.

## Struktur Folder

```text
UTS_Web1_25012068/
├── assets/
│   └── style.css
├── data/
│   └── menu.php
├── dokumentasi/
│   └── Pengujian/
├── includes/
│   ├── fungsi.php
│   ├── header.php
│   └── footer.php
├── index.php
├── keranjang.php
├── proses.php
└── README.md
```

## Cara Menjalankan Aplikasi

1. Instal dan buka XAMPP.
2. Simpan folder project di dalam direktori `C:\xampp\htdocs\web1\UTS_Web1_25012068`.
3. Jalankan Apache melalui XAMPP Control Panel.
4. Buka browser.
5. Akses alamat berikut:

   `http://localhost/web1/UTS_Web1_25012068/`

## Pengujian Aplikasi

Pengujian dilakukan untuk memeriksa fitur-fitur aplikasi, antara lain:

- Daftar menu ditampilkan dengan benar.
- Pencarian menu dengan hasil ditemukan dan tidak ditemukan.
- Validasi jumlah pesanan kosong, negatif, dan melebihi batas.
- Penambahan menu ke keranjang.
- Penghapusan salah satu menu.
- Pengosongan keranjang.
- Filter kategori makanan dan minuman.
- Penyimpanan preferensi favorit apabila tersedia.

Bukti pengujian dapat dilihat pada folder `dokumentasi/Pengujian/`.

## Repository GitHub

[UTS_Web1_25012068](https://github.com/novavaee-ui/UTS_Web1_25012068)

## Informasi

Proyek ini dibuat untuk memenuhi tugas UTS mata kuliah Web 1.