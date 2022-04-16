<img src="https://banners.beyondco.de/Laundry%20App.png?theme=light&packageManager=&packageName=&pattern=architect&style=style_1&description=Aplikasi+Management+Laundry&md=1&showWatermark=1&fontSize=100px&images=truck" />
<p>Halo, ini adalah aplikasi Laundry yang dibangun dengan cinta (love). Aplikasi ini sudah bisa multi toko loh, alias kamu bisa membuat cabang laundry.<br>

## Requirements

-   PHP 7.3 or higher
-   Database (eg: MySQL)
-   Web Server (eg: Apache, Nginx, IIS)

## Framework

Laundry dibangun menggunakan [Laravel](http://laravel.com), the best existing PHP framework, as the foundation framework.

## Installation

-   Install [Composer](https://getcomposer.org/download) and [Npm](https://nodejs.org/en/download)
-   Clone the repository: `git clone https://github.com/andes2912/laundry.git`
-   Install dependencies: `composer install ; npm install ; npm run dev`
-   Run `cp .env.example .env` for create .env file
-   Run `php artisan migrate --seed` for migration database
-   Run `php artisan storage:link` for create folder storage
-   Detail login, Email : `admin@laundry.com` Password `123456`
-   Run `php artisan queue:listen` for run queue

</p>

## Package

-   [IndoBank](https://github.com/andes2912/indobank) package Laravel untuk menyimpan data Nama Bank yang ada di Indonesia

## Fitur Release

#### [Versi 3.x](https://github.com/andes2912/laundry/tree/3.x)

#### Administrator

-   Dashboard Administrator
-   Tambah User Karyawan
-   Lihat data transaksi
-   Data Finance
-   Data Harga
-   Atur target laundry
-   Ubah thema (untuk saat ini hanya ada Dark & White)
-   Data Bank
-   Setting Notifikasi Email, Telegram dan WhatsAapp
-   Dokumentasi

#### Karyawan

-   Dashboard Karyawan
-   Data order masuk
-   Data customer
-   Tambah customer
-   Tambah transaksi Laundry
-   Laporan
-   Ubah thema (untuk saat ini hanya ada Dark & White)

#### Customer

-   Dashboard Customer
-   Ubah thema (untuk saat ini hanya ada Dark & White)

## Sponsors

Support E-Laundry by becoming a sponsor on [Saweria](https://saweria.co/andes2912). Your logo will show up here with a link to your website.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
