# Tugas Praktikum 4

## Janji
Saya Rasendriya Andhika dengan NIM 2305309 mengerjakan Tugas Praktikum 4 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Desain Program
Program ini terdiri dari 3 class, yaitu Menu, Mahasiswa, dan Main.

### 1. Class Menu:
Class ini merupakan antarmuka aplikasi yang menggunakan Java Swing GUI untuk mengelola data mahasiswa. Data yang dikelola meliputi `NIM, Nama, Jenis Kelamin, dan Status Keaktifan mahasiswa` (dengan pilihan: `Aktif, Cuti, Lulus, dan Dikeluarkan `). Aplikasi ini menyediakan fitur `menambah, memperbarui, dan menghapus` data mahasiswa yang disajikan dalam bentuk tabel. Pengguna dapat menginput atau mengubah data melalui form yang tersedia dan melihat hasil perubahan secara real-time di tabel.

### 2. Class Mahasiswa:
Class ini berfungsi sebagai `model` atau `representasi objek mahasiswa` yang menyimpan atribut-atribut seperti `NIM, Nama, Jenis Kelamin, dan Status Keaktifan.` Setiap objek mahasiswa yang dibuat akan disimpan dalam `ArrayList` yang berada pada `Class Menu.`

### 3. Class Main:
Class ini berfungsi untuk `menjalankan aplikasi` dengan membuat objek dari Class Menu dan menampilkan antarmuka aplikasi kepada pengguna.

## Penjelasan Alur
### 1. Inisialisasi
Aplikasi diinisialisasi dengan membuat jendela utama yang menampilkan Formulir Data, Tombol `Add/Update/Delete, dan Tabel Data Mahasiswa`. Beberapa data mahasiswa juga dimasukkan secara statis untuk uji coba.

### 2. Add
Pengguna mengisi formulir dengan memasukkan `NIM, Nama, memilih Jenis Kelamin, dan memilih Status Mahasiswa`, lalu menekan tombol `Add`. Data baru akan ditambahkan ke dalam tabel dan daftar mahasiswa.

### 3. Update
Pengguna memilih data yang ingin diubah dari tabel. Tombol `Add` berubah menjadi `Update`. Pengguna dapat mengubah semua atribut yang diperlukan dan menekan tombol Update untuk menyimpan perubahan.

### 4. Delete
Pengguna memilih data dari tabel dan menekan tombol `Delete`. Sebuah konfirmasi penghapusan akan muncul, dan data tersebut akan dihapus.

### 5. Clear
Setelah melakukan operasi Add, Update, atau Delete, semua field input akan `dibersihkan` untuk siap digunakan kembali.

## Dokumentasi
- Insert
![Insert](https://github.com/user-attachments/assets/8dadd02b-43a7-45a8-8e53-b1e452607b7d)
![Insert Sukses](https://github.com/user-attachments/assets/d5f2c204-052b-425c-8d00-8bcc2019874f)

- Update
![Update](https://github.com/user-attachments/assets/85d7c0d8-8afc-463c-b8fc-c0b73ac0b2ab)
![Update Sukses](https://github.com/user-attachments/assets/de0b7e9d-82c1-459c-ad3c-1c905ae33f10)

- Delete
![Delete](https://github.com/user-attachments/assets/51e6a7b2-6219-42a0-9158-ad8710673b9c)
![Delete Sukses](https://github.com/user-attachments/assets/5d512589-1fc9-4231-94c7-a20e4bfedacf)





