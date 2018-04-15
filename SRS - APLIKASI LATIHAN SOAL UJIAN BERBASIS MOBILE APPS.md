

<div align="center">

## **SOFTWARE REQUIREMENTS SPECIFICATION**

Version 2.3

15 April 2018

<img src="https://oksareinaldi.files.wordpress.com/2018/02/polindra.png?w=421&h=421&crop=1" width="250" height="250">

**APLIKASI LATIHAN UJIAN BERBASIS MOBILE APPS**

​                                                      Disusun Oleh :

​                                                           Bahrainsyah Oksareinaldi (1603092)

​                                                           Dodi Hodayat (1603095)

​                                                           Muhroz Al Farizi (1603108)

​                                                           Syahrul Romadoni (1603114)

​                                                               **D3 Teknik Informatika**

​                                                            ​**Politeknik Negeri Indramayu**
</div>

#### SPESIFIKASI KEBUTUHAN PERANGKAT LUNAK

## **BAB I Pendahuluan**

   Pada bagian ini memberikan deskripsi dan gambaran mengenai apapun yang terdapat pada dokumen SRS. Juga tujuan dari pembuatan dari dokumen ini di gambarkan dan di urutkan juga didefinisikan.

   **1.1  Tujuan**

   Tujuan dari pembuatan dokumen ini adalah untuk memberikan detail dari System Requirement dari "Aplikasi Latihan Ujian Nasional Berbasis Mobile Apps". Pada dokumen ini mengilustrasikan tujuan dan pernyataan lengkap dari pembuatan sistem. Dokumen ini juga menjelaskan spesifikasi sistem, interface dan hubungan dengan aplikasi lainnya.

   **1.2  Lingkup**

   "Aplikasi Latihan Ujian Berbasis Mobile Apps" merupakan sebuah aplikasi mobile yang dibuat bekerja sama dengan mitra yaitu SMK RISTEK MULTIMEDIA Indramayu. Pada aplikasi ini disediakan materi, latihan soal dan soal - soal yang diharapkan dapat meningkatkan mutu dari siswa - siswa dalam kompetensinya.

   Batasan dari aplikasi ini ialah pada soal - soal dan materi, hanya berkaitan dengan bidang multimedia dan beberapa materi pelajaran wajib, Juga disediakan fitur perangkingan berbasis grafik.

   **1.3  Definisi, Akronim, Singkatan**
   
| Akronim | Singkatan | Definisi |
   |-----------|-------------|-------|
   |Mobile Apps | | Aplikasi perangkat bergerak meliputi IOS, Android.|
   | Android Virtual Device | AVD| konfigurasi dari emulator sehingga kita dapat menjalankan perangkat Android sesuai model yang dipilih   |
   | Software Development Kit | SDK | bekal utama bagi developer untuk membuat suatu program dan menjalankan program java |
   |  Application Programming Interface| API | sekumpulan perintah, fungsi, dan protokol yang dapat digunakan oleh programmer saat membangun perangkat lunak untuk sistem operasi tertentu|


   **1.4  Referensi**

-    Software Requirements Specification, "Web Publishing Sistem", April 15, 2004.

-    IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements
    Specifications. IEEE Computer Society, 1998.


   **1.5  Overview**
   
   Didalam dokumen ini memuat 3 bab yang masing - masing bab menjelaskan fungsi dan desain darri aplikasi latihan ujian berbasis mobile apps. Pada bab 1 menjelaskan tentang tujuan, lingkup, definisi singkatan, referensi pembuatan dokumen ini dan gambaran tentang dokumen ini.
   Pada bab ke-2 menjelaskan tentang gambaran dari produk yang akan dibuuat, interface yang digunakan, btasan memory dan operasi - oerasi yang ada pada sistem.
   Pada bab ke-3 menjelaskan tentang spesifikasi yang terdapat pada sistem ini.

##   **BAB II Gambaran Umum**

   **2.1 Perspektif Produk**

   Aplikasi Latihan Ujian Berbasis Mobile Apps bertujuan untuk sekolah-sekolah yang masih belum memiliki fasilitas sekolah yang memadai terutama di bagian fasilitas komputer dan alat-alat electroniklainya, dan juga terutama untuk siswa/siswi yang masih belum memiliki komputer/laptop di rumahnya maka dari itu aplikasi ujian berbasisi mobile ini siswa/siswi bisa latihan ujian nasional dimana saja dan kapan saja karna latihan ujian nasional ini berbasis android yang bisa dibawa kemana saja oleh siswa/siswi.

   **2.1.1  Antarmuka Sistem**
   
   <img src="https://oksareinaldi.files.wordpress.com/2018/04/untitled-diagram.png?w=640">
   
   Dari diagram diatas dijabarkan bahwa siswa hanya bisa mengakses view buku, view ujian, view latihan, dan view statistik. Guru dan admin dalam sistem ini bisa mengakses keseluruhan dari menu yang ada seperti pada diagram.

   **2.1.2  Antarmuka Pengguna (MOCKUP)**

  ​ **A. Mockup Android.**

  | <img src="https://oksareinaldi.files.wordpress.com/2018/02/a01.png?w=370&h=" width="90"><p>Form Login</p>| <img src="https://oksareinaldi.files.wordpress.com/2018/02/a04.png?w=156&h=315" width="90"><p>Form Register Siswa</p>| <img src="https://oksareinaldi.files.wordpress.com/2018/02/a02.png?w=156&h=315" width="90"><p>Form Lupa Password</p>|
  | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  |<img src="https://oksareinaldi.files.wordpress.com/2018/02/a03.png?w=156&h=315" width="90"><p>Form Rubah Password</p>| <img src="https://oksareinaldi.files.wordpress.com/2018/02/a05.png?w=209&h=426" width="90"><p>Menu Utama Aplikasi</p>|<img src="https://oksareinaldi.files.wordpress.com/2018/02/a06.png?w=208&h=426" width="90"><p>Menu View Buku</p>|
  |<img src="https://oksareinaldi.files.wordpress.com/2018/02/a17.png?w=158&h=313" width="90"><p>Menu Pilih Latihan Ujian</p>|<img src="https://oksareinaldi.files.wordpress.com/2018/02/a18.png?w=210&h=420" width="90"><p>Menu Pilih Ujian</p>| <img src="https://oksareinaldi.files.wordpress.com/2018/02/a07.png?w=211&h=426" width="90"><p>Menu Statistik Nilai</p>| <img src="https://oksareinaldi.files.wordpress.com/2018/02/a09.png?w=155&h=316" width="90"><p>Menu Lihat Profil</p>|<img src="https://oksareinaldi.files.wordpress.com/2018/02/a10.png?w=157&h=316" width="90"><p>Menu Times Up</p>|<img src="https://oksareinaldi.files.wordpress.com/2018/02/a24.png?w=155&h=312" width="90"> <p>Soal Latihan</p>|
  |<img src="https://oksareinaldi.files.wordpress.com/2018/02/a25.png?w=211&h=421" width="90"><p>Menu Times Up</p>|<img src="https://oksareinaldi.files.wordpress.com/2018/02/a11.png?w=156&h=316" width="90"><p>Soal Ujian</p>|<img src="https://oksareinaldi.files.wordpress.com/2018/02/a12.png?w=315&h=631" width="90"><p>Konfirmasi Submit Jawaban</p>|
  | <img src="https://oksareinaldi.files.wordpress.com/2018/02/a14.png?w=156&h=313" width="90"><p>Times Up</p>|<img src="https://oksareinaldi.files.wordpress.com/2018/02/a15.png?w=156&h=313" width="90"><p>Tampilan Soal</p>|<img src="https://oksareinaldi.files.wordpress.com/2018/02/a16.png?w=154&h=313" width="90"><p>Konfirmasi jawaban</p>|


 ** B. Mockup Website.**

 <table>
        <tr>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w01.png?w=1000&h=">
 <p>Mockup Login Guru/Admin </p></td>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w02.png?w=700&h=">
 <p>Mockup Register Guru</p></td>
        </tr>
        <tr>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w03.png?w=700&h=">
 <p>Mockup Lupa Password</p></td>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w06.png?w=150&h=99">
 <p>Mockup Tampil Buku</p></td>
        </tr>
        <tr>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w07.png?w=150&h=100">
 <p>Mockup Tambah Buku</p></td>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w16.png?w=150&h=99">
 <p>Mockup Tambah Guru</p></td>
        </tr>
        <tr>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w26.png?w=770&h=">
 <p>Mockup Tambah siswa</p></td>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w09.png?w=770&h=">
 <p>Mockup Tambah Kategori</p></td>
        </tr>
        <tr>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w13.png?w=770&h=">
 <p>Mockup Tambah Penerbit</p></td>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w08.png?w=770&h=">
 <p>Mockup Kategori</p></td>
        </tr>
        <tr>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w18.png?w=770&h=">
 <p>Mockup Tambah Wali Kelas</p></td>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w20.png?w=770&h=">
 <p>Mockup Tambah mata Pelajaran</p></td>
        </tr>
        <tr>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w25.png?w=392&h=">
 <p>Mockup Tambah Jurusan</p></td>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w25.png?w=392&h=">
 <p>Mockup Jurusan</p></td>
        </tr>
        <tr>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w17.png?w=770&h=">
 <p>Mockup Wali Kelas</p></td>
            <td><img style="width: 250; height: 200;" src="https://oksareinaldi.files.wordpress.com/2018/04/w05.png?w=770&h=">
 <p>Mockup Tampil Buku</p></td>
        </tr>
 </table>

 
   **2.1.3  Antarmuka Perangkat Keras**

   <img align="center" src="https://oksareinaldi.files.wordpress.com/2018/04/untitled-diagram.jpg?w=640">
   <p align="center">Gambar 2.1.3.1 Antar Muka Perangkat Keras</p>

  ​

   **2.1.4  Antarmuka Perangkat Lunak**

   Aplikasi Latihan Ujian Berbasis Mobile Apps ini hanya bisa di instal di android versi 4.0.3 (Ice Cream Sandwich) karna simulasi aplikasi ujian ini bisa di jalankan hanya untuk ver 4 ke atas tidak bisa android ver 4 kebawah.

   **2.1.5  Antarmuka Komunikasi**

   Antarmuka komunikasi Aplikasi Latihan Ujian Berbasis Mobile Apps

  ​     Admin dan user harus tersambung internet terutama untuk admin untuk mengupload materi pelajaran dan menginputakan data seperti menabah materi-materi pelajaran dan mengupload ujian dan latihan ujian yang akan di jalankan oleh siswa/siswi, Dan user tidak harus online si user hanya bisa ujian, latihan ujian dan mendownload materi-materi pelajaran yang di upload oleh si guru.


   **2.1.6  Operasi -Operasi**

   ​  

  | No   | Tampilan                          | Operasi                      | Fungsi                                                       |
  | ---- | --------------------------------- | ---------------------------- | ------------------------------------------------------------ |
  | 1    | Tampilan Login                    | Input Email                  | Berfungsi sebagai ID akun masuk ke aplikasi.                 |
  | 2    |                                   | Input Password               | Berfungsi sebagai security ID akun aplikasi anda.            |
  | 3    |                                   | Button Login                 | Berfungsi sebagai proses masuk aplikasi.                     |
  | 4    |                                   | Button Forget                | Berfungsi sebagai ketika user tidak tahu passwordnya atau lupa password. |
  | 5    | Tampilan Lupa Password            | Input Username               | Berfungsi sebagai ID username security yang ada di databases. |
  | 6    |                                   | Input Nomer HP               | Berfungsi sebagai ID nomer security yang ada di databases.   |
  | 7    |                                   | Input Email                  | Berfungsi sebagai ID email security yang ada di databases.   |
  | 8    |                                   | Button Cancel                | Berfungsi sebagai tidak jadi untuk lupa password.            |
  | 9    |                                   | Button Send                  | Berfungsi sebagai mengirim data yang telah di input oleh user, jika benar  buttom ini akan mengarah ke rubah password jika tidak buttom ini akan kembali  ke tampilan lupa password. |
  | 10   | Tampilan Rubah Password Dll       | Input Password               | Berfungsi sebagai perubahan password yang tadi lupa jadi biki lagin  dengan akun yang sama, yang telah di inputkan di Tampilan Lupa Password. |
  | 11   |                                   | Input Nomer HP               | Berfungsi sebagai perubahan nomer hp biasanya nomernya udah muncul, jika  mau dirubah nomernya silahkan ganti nomernya jika tidak dirubah maka jangan  dihapus atau dirubah. |
  | 12   |                                   | Input Email                  | Berfungsi sebagai perubahan email atau jika mau dirubah silahkan dirubah  jika tidak dirubah jangan dihapus atau dirubah emailnya. |
  | 13   |                                   | Button Cancle                | Berfungsi sebagai buttom ini akan mengarahkan ke halaman Tampilan Login  atau buttom ini membatalkan perubahan password baru. |
  | 14   |                                   | Button Send                  | Berfungsi sebagai perubahan databases, buttom ini yang akan mengarahkan  ke databases kalo ada Password, NoHp dan Email yang ada di rubah |
  | 15   | Tampilan Register                 | Input Email                  | Berfungsi sebagai ID login untuk ID masuk ke aplikasi.       |
  | 16   |                                   | Input Password               | Berfungsi sebagai Password security ID akun aplikasi anda.   |
  | 17   |                                   | Button Cancle                | Berfungsi sebagai tidak jadi untuk register buttom ini akan mengarahkan  ke Tampilan Login. |
  | 18   |                                   | Button cread                 | Berfungsi sebagai membuat akun atau ID baru di aplikasi.     |
  | 19   |                                   | Icon GooglePlus              | Berfungsi sebagai membuat akun atau ID baru di aplikasi tapi menggunakan  akun dari Google. |
  | 20   |                                   | Icon Facebook                | Berfungsi sebagai membuat akun atau ID baru di aplikasi tapi menggunakan  akun dari facebook. |
  | 21   | Tampilan Awal Aplikasi            | Icon 3 Garis Horizon         | Berfungsi sebagai buttom fitur tambahan yang ada di Tampilan Awal  Aplikasi fitur tamabahanya itu editting profile user dll. |
  | 22   |                                   | Button Icon Buku             | Berfungsi sebagai buttom yang akan mengarahkan ke bacaan buku yang ada di  aplikasi tersebut. |
  | 23   |                                   | Button Icon latihan          | Berfungsi sebagai buttom yang akan mengarahkan ke latihan ujian yang  sudah di pelajari dan akan muncul di soal Ujian. |
  | 24   |                                   | Button Icon Ujian            | Berfungsi sebagai buttom yang akan meagarahkan ke Simulasi Ujian asli  yang akan muncul di Ujian Online. |
  | 25   |                                   | Button Icon Static           | Berfungsi sebagai buttom yang akan mengarahkan ke static grafic latihan  ujian dan rangking yang sudah di kerjakan. |
  | 26   |                                   | Button Icon Setting          | berfungsi sebagai mengatur pengaturan yang ada di aplikasi tersebut. |
  | 27   |                                   | Button Icon About            | Berfungsi sebagai yang akan mengarahkan informasi aplikasi.  |
  | 28   | Tampilan Buku                     | Button icon buku             | Berfungsi sebagai buku pelajaran yang bisa dibaca lewat hp selain buku  normal biasanya. |
  | 29   | Tampilan Statistic                |                              | Berfungsi sebagai melihat grafic statistic ujian, latihan,rangking dll. |
  | 30   | Tampilan About                    |                              | Berfungsi sebagai menampilkan informasi aplikasi seperi aplikasi servi  berapa, dibuat siapa dll. |
  | 31   | Tampilan Setting                  |                              | Berfungsi sebagai menampilkan settingan beberapa penganturan yang mau  akan dirubah oleh user. |
  | 32   | Tampilan Latihan Ujian            | Timedown                     | Berfungsi sebagai menampilakan waktu yang akan diujian oleh latihan ujian  aplikasi. |
  | 33   |                                   | Button Icon Play             | Berfungsi sebagai akan dimulainya latihan ujian.             |
  | 34   |                                   | Button icon pause            | Berfungsi sebagai mulai laginya ujian yang sudah pause sebelunya pada  saata latihan ujian sedang berlangsung. |
  | 35   | Tampilan saat mulai latihan ujian | Timedown                     | Berfungsu sebagai waktu mundur yang sedang berjalan.         |
  | 36   |                                   | Button icon pause            | Berfungsi sebagai di pausenya latihan ujian untuk memberhentikan  sementara time down latihan ujian dan akan mengarahkan ke tampilan Mulai  latihan ujian. |
  | 37   |                                   | Button icon panah kanan/kiri | Berfungsi sebagai menggati soal yand ada di latihan ujiantersebut. |
  | 38   |                                   | Button icon Pilihan          | Berfungsi sebagai pilihan jawan user.                        |
  | 39   | Tampilan selesai latihan ujian    | Button icon ya               | Berfungsi sebagai jika jawaban sudah fik buttom ini akan mengarahkan ke  Tampilan Awal Aplikasi. |
  | 40   |                                   | Button icon tidak            | Berfungsi sebagai jika jawaban salah maka buttom ini akan mengarahkan ke  tampilan mulai ujian atau kembali mengerjakan latihan ujian. |
  | 41   | Tampilan ujian                    | Timedown                     | Berfungsi sebagai jangka waktu pengerjaan ujian latihan.     |
  | 42   |                                   | Buttom Icon Play             | berfungsi sebagai mulainya ujian.                            |
  | 43   | Tampilan saat mulai Ujian         | Timedown                     | Berfungsu sebagai waktu mundur yang sedang berjalan.         |
  | 44   |                                   | Button icon panah kanan/kiri | Berfungsi sebagai menggati soal yand ada di latihan ujiantersebut. |
  | 45   |                                   | Button icon Pilihan          | Berfungsi sebagai pilihan jawan user.                        |
  | 46   | Tampilan selesai ujian            | Button icon ya               | Berfungsi sebagai jika jawaban sudah fik buttom ini akan mengarahkan ke  Tampilan Awal Aplikasi. |
  | 47   |                                   | Button icon tidak            | Berfungsi sebagai jika jawaban salah maka buttom ini akan mengarahkan ke  tampilan mulai ujian atau kembali mengerjakan latihan ujian. |
  | 48   | Tampilan Pilih Latihan Ujian      | Button icon Pilihan Ujian    | Berfungsi sebagai memilih latihan soal ujian yang akan dipilih. |
  | 49   | Tampilan Pilih Ujian              | Button icon Pilihan Ujian    | Berfungsi sebagai memilih soal ujian yang akan dipilih.      |
  | 50   | Tampilan Lihat Buku               |                              | Berfungsi sebagai menampilkan buku pelajaran.                |
  | 61   | Tampilan Profile                  | Button Back                  | Berfungsi sebagai kembali ke Tampilan Awal Aplikasi.         |
  | 62   |                                   |                              | Menampikan informasi user.                                   |
  | 63   |                                   | Button Setting               | Berfungsi sebagai mengedit Profile user.                     |
  | 64   | Tampilan EditUser                 | Button Back                  | Berfungsi kembali ke Tampilan Profile.                       |
  | 65   |                                   | Input Username               | Berfungsi sebagai merubah username.ke databases.             |
  | 66   |                                   | Input Password               | Berfungsi sebagai merubah password ke databases.             |
  | 67   |                                   | Input Email                  | Berfungsi sebagai merubah email ke databases.                |
  | 68   |                                   | Input Nomer HP               | Berfungsi sebagai merubah nomer hp ke databases.             |
  | 69   |                                   | Input Alamat                 | Berfungsi sebagai merubah alamat ke databases.               |
  | 70   |                                   | Input Ayah                   | Berfungsi sebagai merubah nama orang tua ayah ke databases.  |
  | 71   |                                   | Input Ibu                    | Berfungsi sebagai merubah nama orang tua ibu ke databases.   |
  | 72   |                                   | Input Nomer HP Orangtua      | Berfungsi sebagai merubah nomer orang tua ayah/ibu ke databases. |

   **2.2  Spesifikasi Kebutuhan Fungsional**

  <img src="https://oksareinaldi.files.wordpress.com/2018/04/untitled-diagram1.png?w=640">

- Deskripsi

| **NO** | **Deskripsi Fungsional**                                                |
  | ------ | ------------------------------------------------------------ |
  | 1      |  Aplikasi dapat menampikan halaman login Siswa |
  | 2      | Aplikasi dapat menampikan halaman login Guru |
  | 3      | Aplikasi dapat menampikan halaman login Admin |
  | 4      |  Aplikasi dapat menampilkan grafik statistik nilai|
  | 5      | Aplikasi dapat menampilkan soal dan latihan |
  | 6      | Aplikasi dapat menampilkan materi |
  | 7      |  Aplikasi terdapat fitur register siswa|
  | 8      |  Aplikasi terdapat fitur tambah guru|

2.2.1  Login Siswa

use case: Login Siswa

diagram:

![enter image description here](/HUBUNGAN/login_siswa.png)

deskripsi singkat: siswa login terlebih dahulu untuk masuk kedalam menu utama

deskripsi  langkah-langkah:

1\. User memilih menu login

2\. Sistem menampilkan form isian login

3\. User mengisi data login

4\. User menekan tombol login

5\. Sistem menuju data user

X Ref: Section 3.2.1, Login Siswa

2.2.2  Login Guru

use case: Login Guru

diagram:

![enter image description here](/HUBUNGAN/login_guru.png)

deskripsi singkat: guru login terlebih dahulu untuk masuk kedalam menu utama

deskripsi  langkah-langkah:

1\. User memilih menu login

2\. Sistem menampilkan form isian login

3\. User mengisi data login

4\. User menekan tombol login

5\. Sistem menuju data user

X Ref: Section 3.2.2, Login Guru

2.2.3  Login Admin

use case: Login Admin

diagram:

![enter image description here](/HUBUNGAN/login_admin.png)

deskripsi singkat: admin login terlebih dahulu untuk masuk kedalam menu utama

deskripsi  langkah-langkah:

1\. User memilih menu login

2\. Sistem menampilkan form isian login

3\. User mengisi data login

4\. User menekan tombol login

5\. Sistem menuju data user

X Ref: Section 3.2.3, Login Admin

2.2.4  Daftar Siswa

use case: Daftar Siswa

diagram:

![enter image description here](/HUBUNGAN/register_siswa.png)

deskripsi singkat: guru mendaftarkan siswa

deskripsi  langkah-langkah:

1\. User memilih menu daftar

2\. Sistem menampilkan form daftar

3\. User mengisi form data

4\. User menekan tombol daftar untuk menyimpan data

5\. Sistem menyimpan data ke dalam database user

6\. Sistem mengirimkan data verifikasi kepada guru

7\. Guru menyetujui verifikasi

8\. User sudah bisa menggunakan fitur aplikasi

X Ref: Section 3.2.4, Daftar Siswa

2.2.5  Daftar Guru

use case: Daftar Guru

diagram:

![enter image description here](/HUBUNGAN/register_siswa.png)

deskripsi singkat: admin mendaftarkan guru

deskripsi  langkah-langkah:

X Ref: Section 3.2.5, Daftar Guru

2.2.6  Kelola Siswa

use case: Kelola Siswa

diagram:

![enter image description here](/HUBUNGAN/kelola siswa_siswa.png)

deskripsi singkat: guru mengelola identitas siswa

deskripsi  langkah-langkah:

1\. User memilih menu daftar

2\. Sistem menampilkan form daftar

3\. User mengisi form data

4\. User menekan tombol daftar untuk menyimpan data

5\. Sistem menyimpan data ke dalam database user

6\. Sistem mengirimkan data verifikasi kepada guru

7\. Guru menyetujui verifikasi

8\. User sudah bisa menggunakan fitur aplikasi

X Ref: Section 3.2.6, Login Siswa

2.2.7  Lihat Buku

use case: Lihat Buku

diagram:

![enter image description here](/HUBUNGAN/lihat_buku.png)

deskripsi singkat: siswa melihat buku yang akan dibaca

deskripsi  langkah-langkah:

1\. User memilih menu kelola siswa

2\. Sistem menampilkan list siswa

3\. User mengelola siswa

4\. User memperbarui siswa

5\. Sistem menyimpan data kedalam database

X Ref: Section 3.2.7, Lihat Buku

2.2.8  Kelola Buku

use case: Kelola Buku

diagram:

![enter image description here](/HUBUNGAN/kelola_buku.png)

deskripsi singkat: guru mengelola buku

deskripsi  langkah-langkah:

1\. User memilih menu buku

2\. User memilih kategori buku

3\. User memilih buku

4\. Sistem menampilkan buku

5\. User melihat buku

X Ref: Section 3.2.8, Kelola Buku

2.2.9  Lihat Latihan

use case: Lihat Latihan

diagram:

![enter image description here](/HUBUNGAN/lihat_latihan.png)

deskripsi singkat: siswa mengerjakan latihan

deskripsi  langkah-langkah:

1\. User memilih menu buku

2\. Sistem menampilkan menu kelola data buku

3\. User memilih data yang akan di kelola

4\. User mengedit data

5\. User memperbarui data

6\. Sistem menyimpan pembaruan ke dalam database

X Ref: Section 3.2.9, Lihat Latihan

2.2.10  Kelola Latihan

use case: Kelola Latihan

diagram:

![enter image description here](/HUBUNGAN/kelola_latihan.png)

deskripsi singkat: guru mengelola latihan

deskripsi  langkah-langkah:

1\. User memilih menu Latihan

2\. User memilih kategori Latihan

3\. User memilih Latihan

4\. Sistem menampilkan Latihan

5\. User Menjawab Latihan

6\. User Menyimpan Latihan

7\. Sistem menyimpan Latihan ke dalam database

8\. User melihat tampilan berhasil disimpan

X Ref: Section 3.2.10, Kelola Latihan

2.2.11  Lihat Ujian

use case: Lihat Ujian

diagram:

![enter image description here](/HUBUNGAN/lihat_ujian.png)

deskripsi singkat: siswa mengerjakan ujian

deskripsi  langkah-langkah:

X Ref: Section 3.2.11, Lihat Ujian

2.2.12  Kelola Ujian

use case: Kelola Ujian

diagram:

![enter image description here](/HUBUNGAN/kelola_ujian.png)

deskripsi singkat: guru mengelola ujian untuk siswa

deskripsi  langkah-langkah:

1\. User memilih menu Latihan

2\. User memilih kategori Latihan

3\. User memperbarui Latihan

4\. User Menyimpan Latihan

5\. Sistem menyimpan latihan kedalam database

6\. User melihat tampilan berhasil disimpan

X Ref: Section 3.2.12, Kelola Ujian

2.2.14  Statistik

use case: Statistik

diagram:

![enter image description here](/HUBUNGAN/lihat_statistik.png)

deskripsi singkat: siswa dan guru dapat melihat statistik tentang nilai 

deskripsi  langkah-langkah:

1\. User memilih menu Statistik

2\. Sistem menampilkan statistic siswa

3\. User melihat statistic siswa

X Ref: Section 3.2.14, Statistik


   **2.3  Spesifikasi Kebutuhan Non-Fungsional**

  | **NO** | **Deskripsi**                                                |
  | ------ | ------------------------------------------------------------ |
  | 1      | Antar muka Bahasa pada sistem menggunakan Bahasa Indonesia   |
  | 2      | Sistem aplikasi dapat memvalidasi email dan password yang diinputkan |
  | 3      | Perangkat lunak dapat berjalan pada platform android kitkat dan web  browser chrome atau firefox |

   **2.4  Karakteristik Pengguna**

  Siswa diharapkan dapat menggunakan aplikasi smartphone android dan sambungan internet pada smartphone dengan baik. Pada halaman utama menampilkan menu - menu dari aplikasi, disini siswa diharapkan sudah mengerti tentang tata cara penggunaan dari aplikasi android.

  Bagi guru diharapkan dapat mengerti tentang cara penggunaan aplikasi web, upload suatu content, dan me-manage user account siswa. pada setiap halaman fungsi yang ada pada web terdapat fitur pencarian yang diharapkan dapat mempermudah guru dalam mencari suatu objek.

  Untuk admin diharapkan dapat mengelola server dengan baik. admin diharapkan dapat mengerti tentang tata cara mengelola sistem dan melakukan troubleshooting ketika terjadi masalah pada sistem.

   **2.5  Batasan - Batasan**
   
   - Aplikasi mobile hannya dapat dijalankan pada platform android Kitkat (API 19 Keatas).
   - Aplikasi WEB dapat dijalankan dengan optimal pada web browser chrome dengan OS Windows dan Linux.
   - Tidak semua fungsi bisa terlaksana karena keterbatasan waktu.

   **2.6  Asumsi - Asumsi Keterkaitan**
   

##   **BAB III Requirement Specification**

3.1 External Interface Requirements

Link ke external sistem adalah link ke webstore database untuk memverifikasi keanggotaan dari siswa, guru, dan admin

3.2 Functional Requirements

3.2.1 Login Siswa

|Use Case Name    |Login                                 |
|-----------------|--------------------------------------|
|X Ref            |Section 2.2.1, Login Siswa            |
|Trigger          |User(Siswa) memilih menu login        |
|Precondition     |Aplikasi mobile menampilkan menu login|
|Basic Path       |1. User memilih menu login            |
|                 |2. Sistem menampilkan form isian login|
|                 |3. User mengisi data login            |
|                 |4. User menekan tombol login          |
|                 |5. Sistem menuju data user            |
|Alternative Paths|Tidak ada                             |

3.2.2 Login Guru

|Use Case Name    |Login                                 |
|-----------------|--------------------------------------|
|X Ref            |Section 2.2.2, Login Guru             |
|Trigger          |User(Guru) memilih menu login         |
|Precondition     |Aplikasi mobile menampilkan menu login|
|Basic Path       |1. User memilih menu login            |
|                 |2. Sistem menampilkan form isian login|
|                 |3. User mengisi data login            |
|                 |4. User menekan tombol login          |
|                 |5. Sistem menuju data user            |
|       |6. Sistem menampilkan data user  |
|Alternative Paths|Tidak ada                             |

3.2.3 Login Admin

|Use Case Name    |Login                                 |
|-----------------|--------------------------------------|
|X Ref            |Section 2.2.3, Login Admin            |
|Trigger          |User(Admin) memilih menu login        |
|Precondition     |Aplikasi mobile menampilkan menu login|
|Basic Path       |1. User memilih menu login            |
|                 |2. Sistem menampilkan form isian login|
|                 |3. User mengisi data login            |
|                 |4. User menekan tombol login          |
|                 |5. Sistem menuju data user            |
| |6. Sistem menampilkan data user  |
|Alternative Paths|Tidak ada                             |

3.2.4 Registrasi Siswa

|Use Case Name    |Daftar                                            |
|-----------------|--------------------------------------------------|
|X Ref            |Section 2.2.4, Daftar Siswa                       |
|Trigger          |User(Guru) memilih menu daftar                    |
|Precondition     |Aplikasi menampilkan menu daftar                  |
|Basic Path       |1. User memilih menu daftar                       |
|                 |2. Sistem menampilkan form daftar                 |
|                 |3. User mengisi form data                         |
|                 |4. User menekan tombol daftar untuk menyimpan data|
|                 |5. Sistem menyimpan data ke dalam database user   |
|                 |6. Sistem mengirimkan data verifikasi kepada guru |
|                 |7. Guru menyetujui verifikasi                     |
|                 |8. User sudah bisa menggunakan fitur aplikasi     |
|Alternative Paths|Tidak ada                                         |

3.2.5 Registrasi Guru

|Use Case Name    |Daftar                                            |
|-----------------|--------------------------------------------------|
|X Ref            |Section 2.2.5, Daftar Guru                        |
|Trigger          |User(Admin) memilih menu daftar                   |
|Precondition     |Aplikasi menampilkan menu daftar                  |
|Basic Path       |1. User memilih menu daftar                       |
|                 |2. Sistem menampilkan form daftar                 |
|                 |3. User mengisi form data                         |
|                 |4. User menekan tombol daftar untuk menyimpan data|
|                 |5. Sistem menyimpan data ke dalam database user   |
|                 |6. Sistem mengirimkan data verifikasi kepada guru |
|                 |7. Guru menyetujui verifikasi                     |
|                 |8. User sudah bisa menggunakan fitur aplikasi     |
|Alternative Paths|Tidak ada                                         |

3.2.6 Manage Siswa

|Use Case Name    |Kelola Siswa                             |
|-----------------|-----------------------------------------|
|X Ref            |Section 2.2.6, Daftar Guru               |
|Trigger          |User(Guru) memilih menu Kelola Siswa     |
|Precondition     |Aplikasi menampilkan menu kelola siswa   |
|Basic Path       |1. User memilih menu kelola siswa        |
|                 |2. Sistem menampilkan list siswa         |
|                 |3. User mengelola siswa                  |
|                 |4. User memperbarui siswa                |
|                 |5. Sistem menyimpan data kedalam database|
|Alternative Paths|Tidak ada                                |

3.2.7 View Buku Use Case

|Use Case Name    |View Buku                     |
|-----------------|------------------------------|
|X Ref            |Section 2.2.7, Daftar Guru    |
|Trigger          |User (Siswa) memilih menu buku|
|Precondition     |Aplikasi menampilkan menu buku|
|Basic Path       |1. User memilih menu buku     |
| |2. Sistem menampilkan menu buku |
|                 |3. User memilih kategori buku |
| |4. Sistem menampilkan kategori buku |
|                 |5. User memilih buku          |
|                 |6. Sistem menampilkan buku    |
|                 |7. User melihat buku          |
| |8. Sistem menampilkan buku |
|Alternative Paths|Tidak ada                     |

3.2.8 Manage Buku

|Use Case Name    |Manage Buku                                    |
|-----------------|-----------------------------------------------|
|X Ref            |Section 2.2.8, Daftar Guru                     |
|Trigger          |User (Guru) memilih menu buku                  |
|Precondition     |Aplikasi menampilkan menu buku                 |
|Basic Path       |1. User memilih menu buku                      |
| |2. sistem menampilkan menu buku |
| |3. user memilih kelola data buku|
|                 |4. Sistem menampilkan menu kelola data buku    |
|                 |5. User memilih data yang akan di kelola       |
| |6. sistem menampilkan data yang akan di kelola |
|                 |7. User mengedit data                          |
|                 |8. User memperbarui data                       |
|                 |9. Sistem menyimpan pembaruan ke dalam database|
|Alternative Paths|Tidak ada                                      |

3.2.9 View Latihan

|Use Case Name    |View Latihan                                 |
|-----------------|---------------------------------------------|
|X Ref            |Section 2.2.9, Daftar Guru                   |
|Trigger          |User (Siswa) memilih menu Latihan            |
|Precondition     |Aplikasi menampilkan menu  Latihan           |
|Basic Path       |1. User memilih menu Latihan                 |
| |2. Sistem menampilkan menu latihan |
|                 |3. User memilih kategori Latihan             |
| |4. Sistem menampilkan kategori Latihan |
|                 |5. User memilih Latihan                      |
|                 |6. Sistem menampilkan Latihan                |
|                 |7. User Menjawab Latihan                     |
|                 |8. User Menyimpan Latihan                    |
|                 |9. Sistem menyimpan Latihan ke dalam database|
|                 |10. User melihat tampilan berhasil disimpan   |
|Alternative Paths|Tidak ada                                    |

3.2.10 Manage Latihan

|Use Case Name    |Kelola Latihan                              |
|-----------------|--------------------------------------------|
|X Ref            |Section 2.2.10, Daftar Guru                 |
|Trigger          |User (Guru) memilih menu Latihan            |
|Precondition     |Aplikasi menampilkan menu Latihan           |
|Basic Path       |1. User memilih menu Latihan                |
| |2. Sistem menampilkan menu Latihan |
|                 |3. User memilih kategori Latihan            |
| |4. Sistem menampilkan kategori latihan |
| |5. User menambahkan Latihan
|                 |6. User memperbarui Latihan                 |
|                 |7. User Menyimpan Latihan                   |
|                 |8. Sistem menyimpan latihan kedalam database|
|                 |9. User melihat tampilan berhasil disimpan  |
|Alternative Paths|Tidak ada                                   |

3.2.11 View Ujian

|Use Case Name    |View Ujian                                 |
|-----------------|-------------------------------------------|
|X Ref            |Section 2.2.11, Daftar Guru                |
|Trigger          |User (Siswa) memilih menu Ujian            |
|Precondition     |Aplikasi menampilkan menu  Ujian           |
|Basic Path       |1. User memilih menu Ujian                 |
| |2. Sistem menampilkan menu Ujian |
|                 |3. User memilih kategori Ujian             |
| |4. Sistem menampilkan kategori Ujian |
|                 |5. User memilih Ujian                      |
|                 |6. Sistem menampilkan Ujian                |
|                 |7. User Menjawab Ujian                     |
|                 |8. User Menyimpan Ujian                    |
|                 |9. Sistem menyimpan Ujian ke dalam database|
|                 |10. User melihat tampilan berhasil disimpan |
|Alternative Paths|Tidak ada                                  |

3.2.12 Manage Ujian

|Use Case Name    |Kelola Ujian                              |
|-----------------|------------------------------------------|
|X Ref            |Section 2.2.12, Daftar Guru               |
|Trigger          |User (Guru) memilih menu Ujian            |
|Precondition     |Aplikasi menampilkan menu Ujian           |
|Basic Path       |1. User memilih menu Ujian                |
| |2. Sistem menampilkan menu Ujian |
|                 |3. User memilih kategori Ujian            |
| |4. Sistem menampilkan kategori Ujian |
| |5. User Menambahkan Ujian |
|                 |6. User memperbarui Ujian                 |
|                 |7. User Menyimpan Ujian                   |
|                 |8. Sistem menyimpan Ujian kedalam database|
|                 |9. User melihat tampilan berhasil disimpan|
|Alternative Paths|Tidak ada                                 |


3.2.14 Statistik

|Use Case Name    |Lihat Statistik                          |
|-----------------|-----------------------------------------|
|X Ref            |Section 2.2.14, Daftar Guru              |
|Trigger          |User(Siswa, Guru)  memilih menu Statistik|
|Precondition     |Aplikasi menampilkan Statistik           |
|Basic Path       |1. User memilih menu Statistik           |
|                 |2. Sistem menampilkan statistic siswa    |
|                 |3. User melihat statistic siswa          |
|Alternative Paths|Tidak ada                                |


**3.3 Logika Struktur Data**

![enter image description here](/ERD.png)

- Tabel Guru


| **DATA ITEM** | **Type** | **Deskripsi**|
  | ------ | ----------|-------------------------------------------------- |
  | id_guru  | int | sebagai identitas guru |
  | id_wali_kelas      | int | sebagai identitas kelas |
  | id_mata_pelajaran      | int | sebagai identitas pelajaran |
  | nama_kelas      | varchar | sebagai penempatan kelas |
  | nama      | varchar | sebagai penempatan nama guru |
  | password      | varchar | sebagai penempatan password |
  | foto      | varchar | sebagai penempatan foto |
  | wali_kelas     | varchar | sebagai penempatan nama wali kelas |
  | no_hp     | varchar | sebagai penempatan nomer hp |
  | alamat      | varchar | sebagai penempatan alamat |
  | email     | varchar | sebagai penempatan email |
  
- Tabel Siswa/Siswi


| **DATA ITEM** | **Type** | **Deskripsi**|
  | ------ | -------------|----------------------------------------------- |
  | id_siswa_siswi | int | sebagai penempatan id siswa/siswi|
  | id_jurusan | int | sebagai penempatan id jurusan|
  | nama_siswa_siswi | varchar | sebagai penempatan nama siswa/siswi|
  | password | varchar | sebagai penempatan password|
  | nisn | int | sebagai penempatan nomer id siswa/siswi|
  | kelas | varchar | sebagai penempatan kelas siswa/siswi|
  | jurusan | varchar | sebagai penempatan jurusan siswa/siswi|
  | wali_kelas | varchar | sebagai penempatan wali kelas siswa/siswi|
  | alamat | varchar | sebagai penempatan alamat siswa/siswi|
  | email | varchar | sebagai penempatan email siswa/siswi|
  | nama_ayah | varchar | sebagai penempatan nama ayah siswa/siwi|
  | nama_ibu | varchar | sebagai penempatan nama ibu siswi/siswi|
  | nama_wali | varchar | sebagai penempatan nama wali dari siswa/siswi|
  | no_hp_ortu | int | sebagai penempatan nomer telepon orang tua siswa/siswi|
  | nama_wali_kelas | varchar | sebagai penempatan nama wali kelas|
  | no_hp_wali_kelas | int| sebagai penempatan nomer wali kelas|
  | alamat_wali_kelas| varchar | sebagai penempatan alamat siswa/siswi|
  | email_wali_kelas | varchar | sebagai penempatan email siswa/siswi|
  | cover| varchar | sebagai penempatan file foto siswa/siswi|
  
- Tabel Buku


| **DATA ITEM** | **Type** | **Deskripsi**|
  | ------ | ---------------|--------------------------------------------- |
  | id_buku| int| sebagai penempatan id buku|
  | id_kategori| int| sebagai penempatan id kategori|
  | id_penerbit| int| sebagai penempatansebagai penempatan id penerbit|
  | id_penulis| int| sebagai penempatan penulis|
  | judul_buku| varchar| sebagai penempatan memasukan judul buku|
  | kategori| varchar| sebagai penempatan memasukan kategori|
  | penerbit| varchar| sebagai penempatan memasukan penerbit|
  | penulis| varchar| sebagai penempatan memasukan penulis|
  | cover| varchar| sebagai penempatan memasukan cover buku|
  
- Tabel Latihan Soal Ujian


| **DATA ITEM** | **Type** | **Deskripsi**|
  | ------ | --------------|---------------------------------------------- |
  | id_latihan_ujian| int| sebagai penempatan id soal latihhan ujian|
  | nama_ujian| varchar| sebagai penempatan nama ujian|
  | kategori| varchar| sebagai penempatan kategori ujian|
  | mata_pelajaran| varchar| sebagai penempatan nama mata pelajaran|
  | file| varchar| sebagai penempatan memasuka file ujian|
  | jurusan| varchar| sebagai penempatan soal jurusan|
  | cover| varchar| sebagai penempatan cover ujian|
  | jawaban_soal| varchar| sebagai penempatan jawaban dari soal latihan jian|
  | kelas| varchar| sebagai penempatan soal ujian untuk kelas berapa|
  
- Tabel Soal Ujian


| **DATA ITEM** | **Type** | **Deskripsi**|
  | ------ | --------------|---------------------------------------------- |
  | id_ujian| int| sebagai penempatan id soal ujian|
  | nama_ujian| varchar| sebagai penempatan nama ujian|
  | kategori| varchar| sebagai penempatan kategori ujian|
  | mata_pelajaran| varchar| sebagai penempatan nama mata pelajaran|
  | file| varchar| sebagai penempatan memasuka file ujian|
  | jurusan| varchar| sebagai penempatan soal jurusan|
  | cover| varchar| sebagai penempatan cover ujian|
  | jawaban_soal| varchar| sebagai penempatan jawaban dari soal latihan jian|
  | kelas| varchar| sebagai penempatan soal ujian untuk kelas berapa|
