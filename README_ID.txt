PETUALANGAN DUNIA MISTERIUS 3D - PROYEK ANDROID

ISI:
- app/src/main/assets/index.html : game 3D berbasis Three.js
- app/src/main/java/.../MainActivity.java : pembungkus Android WebView
- File Gradle dan AndroidManifest untuk dibuka di Android Studio.

CARA MENJALANKAN DI KOMPUTER:
1. Instal Android Studio dan Android SDK.
2. Ekstrak folder proyek.
3. Buka folder PetualanganDuniaMisterius3D di Android Studio.
4. Tunggu Gradle Sync selesai.
5. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
6. APK debug akan muncul di app/build/outputs/apk/debug/app-debug.apk.

CATATAN:
- Game memakai Three.js dari CDN jsDelivr, jadi koneksi internet diperlukan saat bermain.
- Proyek ini belum berupa APK yang ditandatangani untuk rilis Google Play.
- Untuk publikasi, siapkan signing key, ikon, kebijakan privasi, pengujian perangkat, dan kepatuhan kebijakan Google Play.
- Untuk penggunaan di HP saja, buka app/src/main/assets/index.html di browser Android yang mendukung WebGL.
