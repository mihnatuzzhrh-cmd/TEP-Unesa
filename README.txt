TEP UNESA BELAJAR - PAKET PWA

ISI PAKET
  index.html            aplikasinya
  bank.json             bank soal bawaan (268 soal)
  manifest.webmanifest  data ikon dan nama app
  sw.js                 agar bisa dipakai offline
  icons/                ikon app

CARA PASANG DI GITHUB PAGES (lewat browser, tanpa install apa pun)
1. Login ke github.com, klik "+" di kanan atas, pilih "New repository".
2. Nama bebas, mis. tep-unesa. Pilih Public. Klik "Create repository".
3. Klik "uploading an existing file". Ekstrak zip ini dulu, lalu seret SEMUA isinya
   (index.html, bank.json, manifest.webmanifest, sw.js, dan folder icons) ke halaman upload.
   Klik "Commit changes".
4. Buka Settings > Pages. Di "Branch" pilih main dan folder / (root). Klik Save.
5. Tunggu 1-2 menit. Alamat app muncul di halaman itu:
   https://NAMA-GITHUB-KAMU.github.io/tep-unesa/

PASANG DI HP
- Android (Chrome): buka alamat tadi, menu titik tiga > Install app / Add to Home screen.
- iPhone (Safari): tombol Share > Add to Home Screen.
Buka sekali saat online supaya semua file tersimpan. Setelah itu app jalan offline.

MENGGANTI FILE SETELAH ADA PERUBAHAN
Kalau kamu mengubah index.html atau bank.json, buka sw.js dan ganti 'tep-v1' jadi 'tep-v2'
(lalu v3, dst) supaya HP mengambil versi terbaru.

CATATAN
- Progres dan soal tambahan tersimpan di browser HP-mu. Menghapus data browser menghapusnya juga.
- Fitur impor .xlsx memakai pustaka dari internet; simpan sekali saat online agar tersedia offline.
