# Tokokita Flutter App

Tokokita adalah aplikasi Flutter yang dirancang untuk mengelola toko online. Aplikasi ini memungkinkan pengguna untuk melihat produk, menambahkannya ke keranjang belanja, dan melakukan pembelian.

## Fitur

- Lihat daftar produk
- Tambahkan produk ke keranjang belanja
- Hapus produk dari keranjang belanja
- Lakukan pembelian
- Autentikasi pengguna

## Prasyarat

Sebelum memulai, pastikan Anda telah memenuhi persyaratan berikut:

- Dart >= 2.12
- Flutter SDK
- Firebase account
- Node.js dan npm untuk pengelolaan paket
- Emulator Android atau iOS atau perangkat fisik untuk pengujian

## Instalasi

1. Clone repository ini:
    ```bash
    git clone https://github.com/FauzanTanzil/tokokita-flutter-app.git
    cd tokokita-flutter-app
    ```

2. Install dependencies menggunakan Flutter:
    ```bash
    flutter pub get
    ```

3. Setup Firebase untuk proyek Anda:
    - Ikuti panduan [Firebase setup guide](https://firebase.google.com/docs/flutter/setup) untuk mengonfigurasi Firebase untuk aplikasi Flutter Anda.
    - Pastikan untuk menambahkan `google-services.json` (untuk Android) dan `GoogleService-Info.plist` (untuk iOS) ke direktori yang sesuai sesuai dengan panduan.

4. Jalankan aplikasi:
    ```bash
    flutter run
    ```

## Penggunaan

- Buka aplikasi di emulator atau perangkat fisik Anda.
- Lihat daftar produk yang tersedia.
- Tambahkan produk ke keranjang belanja dan lanjutkan ke pembayaran.

## Struktur Direktori

- `lib/` - Berisi kode utama aplikasi.
    - `controllers/` - Berisi logika kontrol aplikasi.
    - `models/` - Berisi model data aplikasi.
    - `screens/` - Berisi tampilan aplikasi.
    - `widgets/` - Berisi widget khusus.
- `assets/` - Berisi aset statis seperti gambar dan font.
- `android/` - Berisi konfigurasi khusus Android.
- `ios/` - Berisi konfigurasi khusus iOS.
- `web/` - Berisi konfigurasi khusus web.
- `windows/` - Berisi konfigurasi khusus Windows.
- `macos/` - Berisi konfigurasi khusus macOS.
- `linux/` - Berisi konfigurasi khusus Linux.

## Kontribusi

Jika Anda ingin berkontribusi, silakan fork repository ini dan buat pull request. Untuk perubahan besar, harap buka issue terlebih dahulu untuk mendiskusikan apa yang ingin Anda ubah.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

## Kontak

Untuk informasi lebih lanjut, Anda dapat menghubungi Fauzan Tanzil Habibi melalui [GitHub](https://github.com/FauzanTanzil).
