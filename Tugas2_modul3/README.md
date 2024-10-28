# Restaurant Reservation System

## Deskripsi Proyek
Sistem Reservasi Restoran adalah aplikasi berbasis Java yang memungkinkan pengguna untuk membuat reservasi di restoran. Program ini menggunakan konsep OOP untuk menyimpan informasi terkait restoran dan reservasi pelanggan, serta menerapkan prinsip Encapsulation dan Interface. Program mencakup dua kelas utama, yaitu Restaurant dan Reservation, serta sebuah antarmuka Printable untuk mencetak detail reservasi.

## Struktur Proyek
- *Restaurant*: Menyimpan informasi mengenai nama dan lokasi restoran.
- *Reservation*: Menyimpan informasi reservasi, termasuk nama pelanggan, tanggal, waktu reservasi, dan jumlah orang.
- *Printable*: Sebuah interface yang memungkinkan kelas untuk mencetak detailnya sendiri.
- *MainApp*: Kelas utama yang mengelola input pengguna dan menjalankan aplikasi.

## Fitur Utama
- Menyimpan informasi restoran dan mencetaknya.
- Membuat dan menyimpan detail reservasi, seperti nama pelanggan, tanggal, waktu, dan jumlah orang.
- Menampilkan detail reservasi dan restoran.

## Cara Menjalankan Proyek
1. Pastikan Anda memiliki *Java* di komputer Anda (disarankan Java 8 atau versi lebih baru).
2. Clone repositori ini atau salin semua file proyek ke dalam direktori.
3. Buka terminal atau Command Prompt dan arahkan ke direktori proyek.
4. Jalankan perintah berikut untuk mengkompilasi semua file Java:
   ```bash
   javac MainApp.java