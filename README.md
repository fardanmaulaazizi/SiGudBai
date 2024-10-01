# <p align="center">SiGudBai</p>

<p align="center" >
    <img width="500" src="/dokumentasi/logo.png" alt="Pasar Cabai Logo">
</p>

## <p align="center">"Sistem Manajemen Pergudangan Cabai"</p>

![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300000f.svg?style=for-the-badge&logo=mysql&logoColor=white)

<p>Sistem manajemen pergudangan cabai adalah platform yang digunakan untuk mencatat informasi tentang penyimpanan cabai yang dikirimkan oleh para petani, yang kemudian akan dikumpulkan dan ditawarkan untuk dijual di pasar online yang sederhana. Sistem ini dirancang untuk memudahkan akses bagi semua orang, memungkinkan mereka untuk dengan mudah mengakses informasi tentang stok cabai di pasar tersebut.</p>
<div>
<p>Sistem ini adalah hasil pengembangan kolaborasi antara saya, dosen saya dan dosen fakultas pertanian untuk keperluan penelitian.</p>
<p>Sistem merupakan update dari sistem [Pasar Cabai](https://github.com/fardanmaulaazizi/Pasar-Cabai) dengan menggunakan teknologi yang lebih baru yaitu <strong>Laravel 11</strong> dan <strong>Laravel Breeze</strong> untuk bagian authentication</p>

## Tampilan Sistem

<div align="center">
    <img width="300" height="150" src="/app_screenshot/beranda.png" alt="Beranda SiGudBai">
    <img width="300" height="150" src="/app_screenshot/produk.png" alt="Produk SiGudBai">
    <img width="300" height="150" src="/app_screenshot/login.png" alt="Login SiGudBai">
</div>
<div align="center">
    <img width="300" height="150" src="/app_screenshot/dashboard-cabai.png" alt="Dashboard Pengelolaan Cabai SiGudBai">
    <img width="300" height="150" src="/app_screenshot/dashboard-komoditas.png" alt="Dashboard Pengelolaan Komoditas SiGudBai">
</div>

## Langkah Instalasi

1.  Clone repository ke local machine anda menggunakan perintah git:

    ```bash
    git clone https://github.com/fardanmaulaazizi/SiGudBai.git
    cd SiGudBai
    ```

2.  Sesuaikan konfigurasi aplikasi pada file `.env` (khususnya database yang digunakan). File `.env` bisa didapatkan dengan menduplikasi file `.env.example` kemudian mengubah nama filenya menjadi `.env`.

3.  Generate `APP_KEY` dari aplikasi dengan menggunakan perintah:

    ```bash
    php artisan key:generate
    ```

4.  Install dependency yang dibutuhkan aplikasi dengan menggunakan perintah:

    ```bash
    composer install
    ```

5.  Migrasikan database beserta seedernya dengan menggunakan perintah:

    ```bash
    php artisan migrate:fresh --seed
    ```

6.  Jalankan Program
    (Optional) Jalankan program dengan menggunakan composer

    ```bash
    cd \Pasar-Cabai\laravel\
    php artisan serve
    ```
