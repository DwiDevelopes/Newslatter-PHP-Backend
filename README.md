# Newslatter-PHP-Backend

**Newslatter-PHP-Backend** adalah sebuah backend aplikasi berbasis PHP yang dirancang untuk mengelola sistem newsletter secara efisien dan aman. Proyek ini memungkinkan pengguna untuk melakukan manajemen langganan email, pengiriman email massal, serta pelacakan statistik pengiriman newsletter.

## Fitur Utama

- **Manajemen Subscriber**  
    Menambah, menghapus, dan memperbarui data pelanggan newsletter secara mudah melalui API atau antarmuka admin.

- **Pengiriman Email Massal**  
    Mendukung pengiriman email ke banyak pelanggan sekaligus dengan dukungan SMTP dan template email dinamis.

- **Otentikasi & Keamanan**  
    Sistem otentikasi berbasis token untuk API, validasi input, dan perlindungan terhadap spam serta serangan umum (XSS, SQL Injection).

- **Pelacakan & Statistik**  
    Mencatat statistik pengiriman, seperti jumlah email terkirim, email dibuka, dan klik pada tautan.

- **Manajemen Template Email**  
    Mendukung pembuatan dan pengelolaan template email HTML yang dapat digunakan ulang.

- **Integrasi Mudah**  
    API RESTful yang mudah diintegrasikan dengan frontend atau aplikasi pihak ketiga.

## Kebutuhan Sistem

- PHP 7.4 atau lebih baru
- Database MySQL/MariaDB
- Web server (Apache/Nginx)
- Composer (untuk manajemen dependensi)

## Instalasi

1. Clone repository ini ke direktori web server Anda.
2. Jalankan `composer install` untuk menginstal dependensi.
3. Konfigurasikan file `.env` untuk pengaturan database dan SMTP.
4. Jalankan migrasi database jika tersedia.
5. Akses endpoint API atau antarmuka admin untuk mulai menggunakan.

## Struktur Direktori

- `/app` — Kode utama aplikasi (controller, model, service)
- `/public` — Entry point aplikasi (index.php)
- `/config` — Konfigurasi aplikasi
- `/resources` — Template email dan aset statis
- `/routes` — Definisi endpoint API

## Lisensi

Proyek ini menggunakan lisensi MIT, sehingga bebas digunakan dan dimodifikasi sesuai kebutuhan.

---

**Newslatter-PHP-Backend** sangat cocok digunakan untuk bisnis, organisasi, atau individu yang ingin membangun sistem newsletter sendiri dengan kontrol penuh terhadap data dan fitur.
