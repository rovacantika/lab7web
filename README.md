# lab7web
## Nama : Rova cantika putri
## NIM  : 312310390
## kelas :TI 23 A.4

Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama lab7_php_dasar pada docroot webserver (htdocs)
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya. Langkah-langkah Praktikum Persiapan Untuk memulai membuat kode php, perlu disiapkan web server dan interpreter PHP terlebih dahulu. Web servar yang kita gunakan adalah Apache 2 dan interpreter PHP 7. Untuk memudahkan proses praktikum, kita gunakan aplikasi bundle web server yaitu XAMPP.

Install XAMPP
Unduh XAMPP dari https://www.apachefriends.org/download.html dan pilih versi portable untuk memudahkan proses installasi. Kemudian extract file tersebut, seusikan direktorinya.

Menjalankan Web Server

Untuk menjalankan web server dari menu XAMPP Control.
Gambar1. XAMPP Control
![Screenshot 2024-11-14 115251](https://github.com/user-attachments/assets/9e593d93-4615-4ea2-af1c-1c1ac5910429)

• Uji coba apakah server sudah berkerja dengan baik http://127.0.0.1 atau http://localhost Tampil halaman utama XAMPP jika server sudah berkerja dengan baik. • Dokumen Website Semua file website tempatkan di direktori: \xampp\htdocs
• Database MySQL Direktori: \xampp\mysql
Manajemen database: http://localhost/phpmyadmin

Memulai PHP

Buat folder lab7_php_dasar pada root directory web server (D:\xampp\htdocs)
Gambar2. Directory Lab7
![Screenshot 2024-11-14 155840](https://github.com/user-attachments/assets/d4203cf0-dd63-4b42-9a79-753120cda452)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: http://localhost/lab7_php_dasar/
Gambar3. Tampilan Web Server

![Screenshot 2024-11-20 062705](https://github.com/user-attachments/assets/4c2d2735-8ef1-48fe-8417-790ffd877f3d)


PHP Dasar

Buat file baru dengan nama php_dasar.php pada directory tersebut. Kemudian buat kode seperti berikut.
![Screenshot 2024-11-13 170953](https://github.com/user-attachments/assets/8bca6586-e014-406f-91c5-83981d4c1d5a)

Hasilnya
![Screenshot 2024-11-20 062503](https://github.com/user-attachments/assets/693af4d5-aa0c-45b1-9b9e-4dc0a0989ad9)

Variable PHP

Menambahkan variable pada program.
![Screenshot 2024-11-20 062006](https://github.com/user-attachments/assets/6a706983-723d-4970-a8c9-4fb3fce2408e)


Hasilnya
![Screenshot 2024-11-20 062900](https://github.com/user-attachments/assets/5f0e5973-221a-4b6e-887a-0be382d6c426)


Predefine Variable $_GET

![Screenshot 2024-11-13 173438](https://github.com/user-attachments/assets/6f98dd1e-fa51-49a1-b28a-74fb91c5f3ae)

Hasilnya

![Screenshot 2024-11-20 063201](https://github.com/user-attachments/assets/329f3951-7573-4086-ace7-1da13639f5f5)


Membuat Form Input

![Screenshot 2024-11-13 182118](https://github.com/user-attachments/assets/06f09dc7-9bf5-4b2b-91a2-9d8b3d8f6fb5)

Hasilnya 
![Screenshot 2024-11-20 063538](https://github.com/user-attachments/assets/02f15bf6-37fb-47cf-8f05-513fd301cc00)


Operator

![Screenshot 2024-11-14 112711](https://github.com/user-attachments/assets/2314eaae-c84a-409d-9203-4599fc831425)

Hasilnya 
![Screenshot 2024-11-20 063721](https://github.com/user-attachments/assets/30e67abc-e6a9-4fec-87af-3b07135b4aa5)


Kondisi IF

![Screenshot 2024-11-14 112854](https://github.com/user-attachments/assets/35112a5b-8d64-48ec-920f-22c0705f48f3)

Hasilnya
![Screenshot 2024-11-15 091013](https://github.com/user-attachments/assets/a45c9f1b-ab99-4f42-a947-e024f9c0b1fb)

Kondisi Switch

![Screenshot 2024-11-14 113123](https://github.com/user-attachments/assets/81fabe96-4df8-4a16-8c1e-96d4e6d538df)

Hasilnya
![Screenshot 2024-11-15 091104](https://github.com/user-attachments/assets/088fd192-46a9-47e8-88dc-a70fd67d773d)

Perulangan for

![Screenshot 2024-11-14 113310](https://github.com/user-attachments/assets/08d61a30-af82-4c0e-b08b-5dfa4dc885e3)

Hasilnya
![Screenshot 2024-11-14 113654](https://github.com/user-attachments/assets/260a9d2c-ad41-432e-b9cd-aa2d19af040b)

Perulangan while

![Screenshot 2024-11-14 113855](https://github.com/user-attachments/assets/81865f3a-163c-4b1e-8129-c4c060141af8)

Hasilnya
![Screenshot 2024-11-14 113837](https://github.com/user-attachments/assets/f56989a3-a089-46ed-b86a-2ef03536bd5f)

Perulangan dowhile

![Screenshot 2024-11-14 114008](https://github.com/user-attachments/assets/ee541209-e9d4-4857-aedb-d59cc5963244)

Hasilnya
![Screenshot 2024-11-14 113950](https://github.com/user-attachments/assets/01a00f67-8011-4360-a785-080cde905122)


Pertanyaan dan Tugas

Buatlah program PHP sederhana dengan menggunakan form input yang menampilkan nama, tanggal lahir dan pekerjaan. Kemudian tampilkan outputnya dengan menghitung umur berdasarkan inputan tanggal lahir. Dan pilihan pekerjaan dengan gaji yang berbeda-beda sesuai pilihan pekerjaan.

JAWAB

![Screenshot 2024-11-14 114349](https://github.com/user-attachments/assets/0f6582a2-76ee-4c11-8259-4695565769d4)

![Screenshot 2024-11-14 114414](https://github.com/user-attachments/assets/5226d0df-065e-4368-ba8e-cdb108836b8f)

Hasilnya
![Screenshot 2024-11-14 114315
