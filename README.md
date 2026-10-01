# I Shava Yogi Flachintya — A little pink story

Portofolio HTML/CSS/JavaScript bertema coquette pink gradasi. Berisi profil, sekolah, kemampuan, tiga demo interaktif, galeri prestasi, dan WhatsApp. Responsif, menu hamburger, animasi pita, tombol jeda animasi, serta dukungan reduced motion. Font lokal disertakan dengan lisensinya.

## Cara memakai
Ekstrak ZIP, lalu buka index.html. Upload seluruh isi ZIP ke root repository GitHub (index.html langsung di root). Untuk Vercel, import repository, pilih framework Other, tanpa build command; output directory `.`. Tidak perlu npm atau backend. Konfigurasi vercel.json sudah disertakan. Paket belum diterbitkan ke akun GitHub/Vercel.

## Foto profil
Edit config.js, isi `photo` dengan URL gambar langsung HTTPS atau `assets/fotoprofil.jpg`. Alternatif: cukup masukkan fotoprofil.png/jpg/jpeg ke folder assets. Jika foto belum ada/gagal dimuat, inisial Sh tampil. Atur `photoPosition`, misalnya `center 30%`, untuk posisi wajah. Jangan memakai link halaman pratinjau Drive; gunakan URL gambar yang bisa dibuka langsung.

## Prestasi — melalui config.js
Masukkan gambar ke assets/prestasi1.jpg, prestasi2.png, dst, ATAU gunakan URL gambar langsung. Tambahkan satu objek pada `achievements` untuk setiap gambar:

    { title: "Judul prestasi", description: "Keterangan", image: "assets/prestasi1.jpg" }

Pisahkan objek dengan koma. Tidak ada batas jumlah yang ditetapkan kode. Nama file lokal bebas asalkan cocok dengan path di config.js, termasuk huruf besar/kecil. Gambar mempertahankan rasio asli dan dapat diklik untuk diperbesar. File yang hanya ditaruh di folder tanpa didaftarkan belum akan tampil. Galeri kosong sampai pemilik menambahkan prestasi asli.

## Kontak dan data
WhatsApp 085656504478 sudah menjadi 6285656504478. Edit `whatsapp` di config.js tanpa tanda +. Identitas dan pendidikan ada di index.html: I Shava Yogi Flachintya, X RPL 3, absen 30; SD Cinta Hati; SMP Muhammadiyah 6 Krian; SMK Krian 1 Sidoarjo. Kemampuan 100% mengikuti penilaian diri yang diberikan, bukan sertifikasi.

## Proyek
Tiga demo dibuat untuk paket ini, bukan klaim karya historis pemilik:
- Pink Gradient Lab: memilih dua warna dan arah gradasi, keluaran kode CSS.
- Catatan Kata: menghitung kata berbasis spasi, karakter Unicode termasuk spasi, estimasi baca 200 kata/menit.
- Kado Patungan: harga + kemasan dibagi orang, pembulatan ke atas dan sisa pembulatan; validasi angka.

Tidak membutuhkan koneksi internet kecuali membuka WhatsApp atau foto dari URL eksternal. Foto orang lain dan prestasi fiktif tidak disertakan.
