# Catatan Keuangan Saya

Aplikasi web (PWA) untuk mencatat keuangan pribadi. Data tersimpan di perangkat pengguna, tanpa server.

## Pasang di GitHub Pages
1. Buat repository baru di GitHub (publik), misalnya `keuangan-saya`.
2. Unggah semua file di folder ini ke root repository (Add file > Upload files), lalu Commit.
3. Buka Settings > Pages. Pada Source pilih "Deploy from a branch", branch `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1-2 menit. Alamatnya: `https://NAMA-GITHUB.github.io/keuangan-saya/`

## Pasang di HP
- Android (Chrome): buka alamatnya, menu titik tiga > "Pasang aplikasi" atau "Tambahkan ke layar utama".
- iPhone (Safari): tombol Bagikan > "Tambah ke Layar Utama".
- Ingin file APK? Masukkan alamat GitHub Pages ke https://www.pwabuilder.com lalu pilih Android.

## Catatan
- Data hanya ada di browser perangkat itu. Gunakan Pengaturan > Cadangan data secara berkala.
- Setelah mengubah file, naikkan angka versi `V` di `sw.js` agar pengguna mendapat pembaruan.

## Fitur perkiraan
- Proyeksi akhir bulan, proyeksi 6 bulan, skenario hemat dan kenaikan pemasukan, serta estimasi tercapainya target tabungan.
- Isi "Saldo awal" pada kartu Perkiraan keuangan agar saldo dan proyeksi akurat.
- Tombol Cetak laporan membuat laporan bulanan (simpan sebagai PDF dari dialog cetak).
