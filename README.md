# toko-komputer-laravel

# To-Do List

-   Bela

-   [ ] Membuat halaman dashboard
-   [ ] Membuat sidebar
-   [ ] Membuat tampilan stok barang
-   [ ] Membuat tampilan barang terjual(penjualan)
-   [ ] Membuat tampilan reset password dan ganti username

-   Uluum

-   [x] membuat tampilan login
-   [ ] Membuat backend untuk upload gambar
-   [ ] login
-   [ ] ganti pasword dan username
-   [ ] cetak laporan
-   [ ] fungionalitas web seperti hapus, tambah, dan ubah data

## Installation

Sebelum melakukan instalasi, pastikan sudah menginstal PHP versi =>8.0 dan Composer.

1. Clone repository. Download sebagai zip atau dengan menjalankan perintah

    ```bash
    git clone https://github.com/uluumbch/toko-komputer-laravel.git
    ```

2. Buka terminal atau CMD dan pindah ke foder dimana hasil projek di download.

    ```bash
    cd C:/tujuan/projek/anda

    # Contoh

    cd c:/xampp/htdocs/toko-komputer-laravel
    ```

    Jalankan perintah composer install pada terminal

    ```bash
    composer install
    ```

3. Buat file `.env` untuk konfigurasi dan generater `APP_KEY`.

    ```
    cp .env.example .env
    php artisan key:generate
    ```

4. Konfigurasi database pada file `.env`, sesuaikan perintah dibawah dengan database yang dibuat.

    ```env
    DB_HOST=127.0.0.1 # ganti dengan url anda atau biarkan default
    DB_PORT=3306 # ganti dengan port atau biarkan default
    DB_DATABASE=toko-komputer-laravel # ganti dengan nama database yang telah dibuat atau buat database baru dengan nama toko-komputer-laravel
    DB_USERNAME=root # sesuaikan dengan username database. biarkan default jika menggunakan database lokal
    DB_PASSWORD= # sesuaikan dengan password database. biarkan default jika menggunakan     database lokal
    ```

5. Migrasi tabel dan lakukan seed untuk mengisi data pada database

    ```composer
    php artisan migrate:fresh --seed
    ```

6. Aplikasi siap dijalankan dengan perintah

    ```composer
     php artisan serve
    ```

<p align="center">Apabila memerlukan database sqldump, file bernama prognet8.sql</p>

## Contributing

1. Jika sudah di clone, pull dulu repository ini dengan perintah berikut, supaya dapat editan terbaru

```
git pull origin main
```

2. Edit projek sesuai keinginan
3. Kalau sudah diedit, push kembali seperti perintah berikut

```
git add .
```

```
git commit -m "pesan"
```

```
git push origin master
```

## Screenshot

## Online Demo
