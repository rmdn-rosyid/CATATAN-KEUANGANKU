# CATATAN-KEUANGANKU
# Catat Uang – Proyek Android

## Cara 1: Build APK otomatis lewat GitHub (tanpa install apa pun)
1. Buat akun di github.com (gratis), lalu buat repository baru (boleh Private).
2. Ekstrak zip ini, lalu unggah SEMUA isinya ke repository
   (klik "Add file" > "Upload files"). Pastikan folder ".github" ikut terunggah.
   Jika folder tersembunyi tidak terlihat di komputer, aktifkan "Tampilkan file tersembunyi".
3. Buka tab "Actions". Build berjalan otomatis (sekitar 5-8 menit).
   Jika belum jalan, pilih "Build APK" > "Run workflow".
4. Setelah centang hijau, klik build tersebut, lalu unduh "catat-uang-apk" di bagian Artifacts.
5. Ekstrak, kirim file app-debug.apk ke HP, lalu install.
   (Izinkan "Install dari sumber tidak dikenal" jika diminta.)

## Cara 2: Android Studio
Kebutuhan: Node.js 18+ dan Android Studio.
  npm install
  npx cap add android
  npx cap sync android
  npx cap open android
Lalu Build > Build APK(s).

## Mengubah aplikasi
Edit www/index.html. Dengan Cara 1, cukup unggah ulang file itu dan APK baru dibuat otomatis.
