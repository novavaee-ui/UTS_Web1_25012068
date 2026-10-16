# Dokumentasi Pengujian

## Identitas

- Nama: Nur Fadilah
- NIM: 25012068
- Kelas: 25M31

## Hasil Pengujian

| ID | Langkah dan Input | Hasil yang Diharapkan | Hasil Aktual | Status | Bukti |
|---|---|---|---|---|---|
| U01 | Buka halaman menu | Minimal 5 menu tampil | Isi setelah diuji | Lulus/Gagal | [Screenshot](01-Daftar-menu.png) |
| U02a | Cari Nasi Goreng | Menu yang sesuai tampil | Isi setelah diuji | Lulus/Gagal | [Screenshot](U02a-pencarian-ditemukan.png) |
| U02b | Cari Pizza | Pesan tidak ditemukan | Isi setelah diuji | Lulus/Gagal | [Screenshot](U02b-pencarian-kosong.png) |
| U03a | Jumlah kosong | Ditolak, keranjang tetap | Isi setelah diuji | Lulus/Gagal | [Screenshot](U03a-jumlah-kosong.png) |
| U03b | Jumlah negatif | Ditolak, keranjang tetap | Isi setelah diuji | Lulus/Gagal | [Screenshot](U03b-jumlah-negatif.png) |
| U03c | Jumlah melebihi maksimum | Jumlah 11 ditolak | Isi setelah diuji | Lulus/Gagal | [Screenshot](U03c-jumlah-melebihi-maksimum.png) |
| U03 | Periksa isi keranjang | Menu dan subtotal tampil sesuai | Isi setelah diuji | Lulus/Gagal | [Screenshot](U03-keranjang-berisi.png) |
| U04 | Hapus satu menu | Item terhapus dan total menyesuaikan | Isi setelah diuji | Lulus/Gagal | [Screenshot](U04-hapus-satu-menu.png) |
| U05 | Kosongkan keranjang | Semua item terhapus dan keranjang kosong | Isi setelah diuji | Lulus/Gagal | [Screenshot](U05-kosongkan-keranjang.png) |
| U06 | Filter kategori Makanan | Hanya menu makanan tampil | Isi setelah diuji | Lulus/Gagal | [Screenshot](U06-filter-kategori-makanan.png) |
| U07 | Filter kategori Minuman | Hanya menu minuman tampil | Isi setelah diuji | Lulus/Gagal | [Screenshot](U07-filter-kategori-minuman.png) |
| U08 | Simpan preferensi favorit | Preferensi tersimpan menggunakan cookie | Isi setelah diuji | Lulus/Gagal | [Screenshot](U08-preferensi-favorit-cookie.png) |

## Catatan Perbaikan

Catat masalah yang ditemukan, perbaikan yang dilakukan, dan hasil pengujian ulang.

Contoh:
- Kondisi diskon diperbaiki agar berlaku ketika subtotal sama dengan atau lebih dari Rp50.000.
- Pengujian ulang dilakukan setelah perbaikan.
- Hasil akhir dicatat berdasarkan pengujian aktual.