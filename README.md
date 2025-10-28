Nama : Siti faiqotul kifiyah
Nim  : 362458302021

## Tujuan Praktikum ##
Setelah menyelesaikan modul praktikum ini, mahasiswa diharapkan mampu: 
1.	Memahami konsep dasar API (Application Programming Interface) dan REST API. 
2.	Menggunakan package http di Flutter untuk melakukan permintaan (request) ke API eksternal. 
3.	Melakukan operasi CRUD (Create, Read, Update, Delete) terhadap data melalui API. 
4.	Mengurai data JSON (parsing) dan mengubahnya menjadi objek Dart (Model). 
5.	Menampilkan data dari API ke dalam UI Flutter menggunakan widget seperti ListView. 
6.	Mengimplementasikan styling dasar pada komponen UI untuk menyajikan data den gan rapi.
7.	Mengelola state secara sederhana untuk menangani data yang bersifat asinkron (asynchronous).

## Dasar Teori (penjelasan singkat tentang API, REST, JSON, http package) ##
a.	API (Application Programming Interface) adalah seperangkat definisi, protokol, dan tools untuk membangun perangkat lunak aplikasi. Dalam praktikum ini, API bertin dak sebagai jembatan yang memungkinkan aplikasi Flutter (klien) Anda berkomunikasi dengan server (backend) untuk mengambil atau mengirim data.
b.	REST (Representational State Transfer) adalah gaya arsitektur yang paling umum digunakan untuk membuat API berbasis web. REST API menggunakan metode HTTP standar untuk melakukan operasi pada resources. 
Berikut adalah gambaran metode HTTPstandar yang digunakan dalam operasi CRUD:
•	Get(READ): Mengambil satu atau lebih resource
•	Post(CREATE): Membuat resource baru
•	Put(UPDATE): Memperbarui seluruh resource
•	Patch(UPDATE): Memperbarui sebagian resource
•	Delete(DELETE): Menghapus satu atau lebih resource.
c.	JSON adalah format pertukaran data yang ringan dan mudah dibaca manusia serta di parsing oleh mesin. Hampir semua REST API menggunakan JSON sebagai format data utama.

## Langkah-langkah implementasi (disertai screenshot hasil setiap bagian pent ing).##
1.	Membuat struktur project flutter
2.	Menambahkan depedensi HTTP
3.	Membuat model data
4.	Membuat kelas api service
5.	Membuat Halaman daftar pengguna
6.	Membuat halaman tambah dan edit pengguna
