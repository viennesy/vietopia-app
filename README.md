# Vietopia Website (APK)

Aplikasi Android yang membuka https://vietopia.vercel.app di dalam app sendiri (WebView), tanpa Chrome.
Isi website selalu terbaru, jadi APK tidak perlu dibuild ulang tiap website diubah.

## Build otomatis lewat GitHub
1. Upload semua isi folder ini ke repo GitHub (branch `main`).
2. Buka tab **Actions** > **Build APK**. Tunggu sampai hijau (2-4 menit).
3. Buka run-nya, download **Vietopia-Website-APK** di bagian Artifacts.

## Link download permanen (untuk Discord)
Buat tag di repo, misalnya `v1.0` (Releases > Draft a new release > tag `v1.0` > Publish).
Actions akan melampirkan `Vietopia-Website.apk` ke Release itu. Share link Release-nya.

## Ganti domain / versi
- Domain: `HOME` di `app/src/main/java/com/vietopia/website/MainActivity.java`
- Versi: `versionCode` dan `versionName` di `app/build.gradle` (naikkan tiap rilis baru)
