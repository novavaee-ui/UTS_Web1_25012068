
# UTS Web I - Pemesanan Kantin Kampus

## Identitas
- Nama: Nur Fadilah
- NIM: 2501268
- Kelas: 25M31

## Deskripsi Aplikasi
Aplikasi Pemesanan Kantin Kampus dibuat menggunakan PHP native tanpa database. Pengguna dapat melihat dan mencari menu, menambahkan pesanan ke keranjang, serta melihat subtotal, diskon, dan total pembayaran.

## Fitur
- Daftar menu menggunakan array PHP.
- Pencarian menu menggunakan GET.
- Pemesanan dan validasi menggunakan POST.
- Keranjang belanja menggunakan session.
- Penghapusan item dan pengosongan keranjang.
- Perhitungan subtotal, diskon, dan total akhir.
- Redirect dan flash message.
- Preferensi kategori menggunakan cookie selama 7 hari.

## Kebutuhan
- XAMPP dengan PHP
- Browser
- Git
- Akun GitHub

## Cara Menjalankan
1. Simpan project di dalam folder htdocs.
2. Jalankan Apache melalui XAMPP.
3. Buka browser.
4. Akses http://localhost/web1/uts-web1-NIM/

## Struktur File
- index.php: halaman daftar menu.
- keranjang.php: halaman keranjang.
- proses.php: proses pesanan.
- data/menu.php: data menu.
- includes/fungsi.php: fungsi aplikasi.
- includes/header.php: header halaman.
- includes/footer.php: footer halaman.
- assets/style.css: tampilan aplikasi.
- dokumentasi/pengujian/README.md: catatan pengujian.
