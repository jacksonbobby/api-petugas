# API-seleksi petugas survei

STEP 1 Install XAMPP bagi yang belum ada sebagai Webserver Localhost
1. Download untuk windows https://www.apachefriends.org/download.html (OS lain silahkan menyesuaikan pilihannya pada halaman web tersebut)
2. Install XAMPP Untuk windows,(Next and next) Silahkan ikuti langkah-langkahnya

STEP 2 Install HeidiSQL untuk akses database untuk SQL Query

1. Download untuk windows https://www.heidisql.com/download.php
2. Install HeidiSQL (next and next)

STEP 3 Import Tabel

1. Create database petugas

    CREATE DATABASE petugas;
    
2. Import tabel dan data awal menggunakan petugas.sql
3. Buka HeidiSQL, pilih database petugas, masukkan SQL query dengan menggunakan petugas.sql

STEP 4 Copy Folder petugas
1. Download petugas.rar, kemudian extract pada hasil install XAMPP, biasanya hasil install pada C://xampp, kemudian klik folder xampp dan masukkan folder hasil extract ke folder htdocs atau C://xampp/htdocs/
2. Copy folder petugas pada C://xampp/htdocs/
3. Atur konfigurasi database pada C://xampp/htdocs/petugas/application/config/database.php, untuk default saya tidak menggunakan password, dengan menggunakan host 'localhost' dan user 'root'

STEP 5 Menampilkan
1. Untuk menampilkan hasil JSON, buka internet browser, ketik URL dengan link http://localhost/petugas/
2. Untuk menampilkan API seleksi, buka internet browser, ketik URL dengan link http://localhost/petugas/frontend/
3. Untuk menampilkan Kode Kecamatan dan Kode Desa, klik "Daftar Kode Kecamatan dan Desa" pada link http://localhost/petugas/frontend/
4. Untuk Tampilkan Data, klik tombol tampilkan pada link http://localhost/petugas/frontend/


Note : Jika belum bisa mohon baca README.md dari atas kembali, semoga membantu, terimakasih


