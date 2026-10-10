# Arsip Jiwa — Website Puisi

## Isi
- `index.html`: website satu file, responsif untuk desktop dan HP.
- Kumpulan puisi dengan jendela baca.
- Bagian surat.
- Tombol suasana audio ambient sintetis (tidak memakai file musik eksternal).

## Cara melihat di komputer
1. Ekstrak folder ZIP.
2. Klik dua kali `index.html` untuk membukanya di browser.
3. Untuk mengubah tulisan, buka `index.html` di editor teks (misalnya Visual Studio Code).

## Cara menambah puisi
Cari bagian `const poems = [` di dekat akhir file. Salin satu objek puisi yang sudah ada lalu ubah:
- `tag`: kategori
- `title`: judul
- `excerpt`: ringkasan yang muncul di kartu
- `body`: isi puisi

Jaga tanda koma di antara objek puisi.

## Cara menerbitkan lewat GitHub Pages
1. Buat akun atau masuk ke https://github.com/
2. Buat repository baru bernama `arsip-jiwa` (boleh public).
3. Unggah file `index.html` ke halaman utama repository.
4. Buka Settings → Pages.
5. Pada Build and deployment, pilih Deploy from a branch.
6. Pilih branch `main` dan folder `/ (root)`, lalu Save.
7. Tunggu proses publikasi selesai. GitHub akan menampilkan URL website di bagian Pages.

Catatan privasi: semua isi `index.html` yang dipublikasikan bersifat publik dan bisa dibaca siapa pun yang menemukan tautannya. Bagian surat dalam template ini bukan halaman rahasia atau terlindungi kata sandi. Jangan masukkan informasi pribadi sensitif. Jika butuh halaman yang benar-benar privat, kita perlu menambahkan sistem autentikasi/server atau menggunakan layanan yang mendukung akses privat.
