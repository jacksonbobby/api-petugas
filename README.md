# API-seleksi petugas survei

STEP 1 Install XAMPP bagi yang belum ada sebagai Webserver Localhost
1. Download untuk windows https://www.apachefriends.org/download.html (OS lain silahkan menyesuaikan pilihannya pada halaman web tersebut)
2. Install XAMPP Untuk windows,(Next and next) Silahkan ikuti langkah-langkahnya

STEP 2 Install HeidiSQL untuk akses database untuk SQL Query

1. Download untuk windows https://www.heidisql.com/download.php
2. Install HeidiSQL (next and next)

STEP 3 Create Database petugas dan Import SQL ke Database Petugas

1. Create database petugas

    CREATE DATABASE petugas;

2. Download petugas.sql
3. Import tabel dan Insert data awal menggunakan petugas.sql pada database petugas
4. Buka HeidiSQL, pilih database petugas, masukkan SQL query dengan menggunakan petugas.sql

STEP 4 Copy Folder petugas
1. Download petugas.rar, kemudian extract pada hasil install XAMPP, biasanya hasil install bisa dicari pada C://xampp, kemudian klik folder xampp dan masukkan folder 'petugas' hasil extract ke folder htdocs atau C://xampp/htdocs/
2. Copy folder 'petugas' pada C://xampp/htdocs/
3. Atur konfigurasi database pada C://xampp/htdocs/petugas/application/config/database.php, untuk default saya tidak menggunakan password, dengan menggunakan host 'localhost' dan user 'root'

STEP 5 Menampilkan Data
1. Klik XAMPP control panel, tekan Action Start pada Module Apache dan MySQL
2. Untuk menampilkan hasil JSON, buka internet browser, ketik URL dengan link http://localhost/petugas/
3. Untuk mencoba hasil JSON bisa menggunakan aplikasi POSTMAN, masukkan URL dengan link http://localhost/petugas/, klik SEND dan pilih dropdown HTML dan pilih JSON
4. Untuk menampilkan API seleksi, buka internet browser, ketik URL dengan link http://localhost/petugas/frontend/
5. Untuk menampilkan Kode Kecamatan dan Kode Desa, klik "Daftar Kode Kecamatan dan Desa" pada link http://localhost/petugas/frontend/
6. Untuk Tampilkan Data, klik tombol tampilkan pada link http://localhost/petugas/frontend/


Note : Jika belum bisa mohon baca README.md dari atas kembali, semoga membantu, terimakasih


