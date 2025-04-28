# Inven BS

Aplikasi inventaris barang sekolah menggunakan Framework Laravel 9.

### Prasyarat

Berikut beberapa hal yang perlu diinstal terlebih dahulu:

-   Composer (https://getcomposer.org/)
-   PHP ^8.0.2
-   MySQL
-   XAMPP

Jika Anda menggunakan XAMPP, untuk PHP dan MySQL sudah menjadi 1 (bundle) didalam aplikasi XAMPP

### Fitur

-   CRUD Barang
-   Import/export excel barang
-   Print
-   CRUD BOS (Bantuan Operasional Sekolah)
-   CRUD Ruangan

### Preview Gambar

_Tampilan Login_
![Image 1](https://imgur.com/a/QhVkQrc)

_Dashboard_
![Image 2](https://imgur.com/a/MAjVwfn)

_Daftar Barang_
![Image 3](https://imgur.com/a/XRlSe1a)

_Daftar Bantuan Operasional Sekolah_
![Image 4](https://imgur.com/a/rPIoTdi)

_Daftar Ruangan_
![Image 5](https://imgur.com/a/FPtuNZ2)

### Langkah-langkah instalasi

-   Clone repository ini

```
https://github.com/riosaputraduha/inventory-app-bs.git
```

```
git@github.com:riosaputraduha/inventory-app-bs.git
```

-   Settelah itu masuk ke folder project

```
cd inventory-app-bs-main
```

-   Install seluruh packages yang dibutuhkan

```
composer install
```
-  Siapkan database dan atur file .env sesuai dengan konfigurasi Anda

-   copy file .env

```
cp .env.example .env
```

-   Generate Application Key

```
php artisan key:generate
```

-   Jika sudah, migrate seluruh migrasi dan seeding data

```
php artisan migrate --seed
```

-   Jalankan local server

```
php artisan serve
```

-   User default aplikasi untuk login

```
Email       : admin@mail.com
Password    : admin
```

### Dibuat dengan

-   [Laravel](https://laravel.com) - Web Framework
