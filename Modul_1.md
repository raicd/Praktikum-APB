<div align="center">

<br>

LAPORAN PRAKTIKUM  
APLIKASI BERBASIS PLATFORM

<br>

MODUL 1  
 GIT

<br>

<img src="logo.jpeg" width="300">

<br><br>

### Disusun Oleh :

**HAMID SABIRIN**  
**2311102129**  
**S1 IF-11-REG01**

<br>

### Dosen Pengampu :

**Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom**

<br>

### Asisten Praktikum :

**Apri Pandu Wicaksono**  
**Rangga Pradarrell Fathi**

<br><br>

### LABORATORIUM HIGH PERFORMANCE  
### FAKULTAS INFORMATIKA  
### UNIVERSITAS TELKOM PURWOKERTO  
### 2026

</div>

## 1. Dasar Teori

Git merupakan salah satu sistem pengendali versi (Version Control System) yang digunakan dalam pengembangan perangkat lunak dan dibuat oleh Linus Torvalds. Sistem ini berfungsi untuk mencatat setiap perubahan yang terjadi pada file dalam suatu proyek, baik yang dikerjakan secara individu maupun oleh tim. Git juga dikenal sebagai distributed revision control system, yaitu sistem kontrol versi yang basis datanya tidak hanya tersimpan di satu lokasi saja.
---

2. Setup Repository via CLI

Berikut tahapan yang dilakukan untuk melakukan inisialisasi serta pengaturan repositori dari komputer lokal menuju GitHub menggunakan CLI:

Langkah 1: Membuat Repositori Baru di GitHub

Langkah awal yang dilakukan adalah membuat repositori baru pada platform GitHub. Repositori tersebut berfungsi sebagai tempat penyimpanan proyek secara online sehingga kode yang dibuat dapat dikelola dan dibagikan dengan mudah.

Langkah 2: Panduan Perintah Git

Setelah repositori berhasil dibuat, GitHub akan menampilkan panduan berupa daftar perintah Git yang perlu dijalankan. Perintah-perintah ini nantinya digunakan untuk menghubungkan folder proyek yang ada di komputer lokal dengan repositori GitHub.

Langkah 3: Membuat Folder Proyek dan File

Tahap berikutnya adalah menyiapkan folder proyek pada direktori komputer, misalnya membuat folder Pertemuan 1. Di dalam folder tersebut, tambahkan minimal satu file contoh seperti main.txt yang akan digunakan sebagai isi awal repositori.

Langkah 4: Membuka CMD dari Direktori Folder Proyek

Selanjutnya buka Command Prompt (CMD) atau Terminal, lalu arahkan lokasi direktori ke folder proyek yang telah dibuat sebelumnya. Hal ini bertujuan agar setiap perintah Git yang dijalankan nantinya diterapkan pada folder proyek yang benar.

Langkah 5: Menjalankan Perintah Git di Terminal (Push ke GitHub)

Pada tahap ini, seluruh perintah Git yang ditampilkan sebelumnya dijalankan secara berurutan melalui terminal. Proses dimulai dengan melakukan inisialisasi Git pada folder lokal (git init), menambahkan file ke staging area (git add), membuat commit (git commit), menghubungkan repositori lokal dengan repositori GitHub, hingga akhirnya mengunggah file ke GitHub menggunakan perintah (git push).

Langkah 6: Repositori Berhasil Diperbarui

Apabila proses pengunggahan (git push) berjalan dengan lancar tanpa kesalahan, maka seluruh file dan folder yang ada pada proyek lokal akan berhasil tersimpan di repositori GitHub. Dengan demikian, proyek tersebut sudah siap untuk digunakan maupun dikembangkan secara kolaboratif.