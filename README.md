# TV Lokal Online
```
echo "# TV-Lokal-Online" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ryanbekabe/TV-Lokal-Online.git
git push -u origin main
```

Aplikasi Android sederhana untuk menonton siaran TV lokal Indonesia secara online melalui WebView yang terintegrasi dengan layanan IndiHomeTV.

## Fitur Utama
- **Live Streaming:** Akses langsung ke siaran TV lokal dan internasional melalui [IndiHomeTV](https://www.indihometv.com/tv/live).
- **Antarmuka Sederhana:** Menggunakan WebView yang dioptimalkan untuk pengalaman menonton yang lancar.
- **Navigasi Pintar:** Dukungan tombol "Back" untuk navigasi halaman di dalam aplikasi sebelum menutup aplikasi.
- **Performa Ringan:** Aplikasi minimalis yang berfokus pada fungsionalitas utama.

## Teknologi yang Digunakan
- **Bahasa Pemrograman:** Kotlin
- **UI Framework:** Android Jetpack (AppCompat, ConstraintLayout)
- **Komponen Utama:** 
  - `WebView` dengan dukungan JavaScript dan DOM Storage.
  - `OnBackPressedDispatcher` untuk manajemen navigasi yang modern.
- **Minimum SDK:** API 23 (Android 6.0 Marshmallow)
- **Target SDK:** API 36 (Android 15+)

## Cara Menjalankan Project
1. Clone repository ini:
   ```bash
   git clone https://github.com/ryanbekabe/TV-Lokal-Online.git
   ```
2. Buka project di **Android Studio**.
3. Pastikan koneksi internet aktif (aplikasi memerlukan izin `INTERNET`).
4. Jalankan aplikasi pada **Emulator** atau perangkat fisik Android.

## Struktur Project
- `app/src/main/java/com/hanyajasa/tvlokalonline/MainActivity.kt`: Logika utama untuk menginisialisasi WebView dan menangani navigasi.
- `app/src/main/res/layout/activity_main.xml`: Tata letak utama aplikasi.
- `app/src/main/AndroidManifest.xml`: Konfigurasi aplikasi dan deklarasi izin internet.

---
Dikembangkan oleh [Hanyajasa](https://github.com/hanyajasa).
