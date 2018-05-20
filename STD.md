


<div align="center">

## **SOFTWARE TESTING DOCUMENT**

Version 1.1

20 Mei 2018

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


## BAB I 
## PENDAHULUAN

Dokumen ini akan berisi  perencanaan, deskripsi, dan hasil uji perangkat lunak (DUPL) atau Software Test Documentation (STD) untuk Sistem Rental Mobil (SRM). Untuk  penamaan dokumen ini selanjutnya akan digunakan istilah DUPL. Dokumen ini sebagian besar adalah adaptasi dari dokumen IEEE Std 8291998.  

 **1. 1 TUJUAN PEMBUATAN DOKUMEN**
 
 Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap perangkat lunak LATIHAN UJIAN BERBASIS MOBILE APPS. Dokumen ini dipakai untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan keinginan dari pengguna. Pembuatan dokumen ini ditunjukan untuk menguji perangkat lunak LATIHAN UJIAN BERBASIS MOBILE APPS yang merupakan bagian dari mata kuliah Rekayasa Perangkat Lunak
 
 **1.2 DESKRIPSI UMUM SISTEM**
 
 Perangkat lunak yang akan diuji adalah "LATIHAN UJIAN BERBASIS MOBILE APPS". Perangkat lunak ini adalah perangkat lunak yang digunakan untuk simulasi latihan ujian siswa dalam menghadapi ujian. 
 

 **1.3 DESKRIPSI DOKUMEN**
 
 Dokumen DUPL ini terdiri dari dua tahap yaitu tahap perencanaan (baik secara manajerial maupun perencanaan kasus ujinya sendiri) dan tahap pelaporan. Yang disebut dengan tahap pelaporan adalah pendokumentasian hasil uji yang didapat setelah pengujian itu sendiri berlangsung. Hal inilah yang harus menjadi perhatian bagi manajemen konfigurasi yang digunakan di projek. 
 
 **1.4 DEFINISI DAN SINGKATAN**
 <table>
 	<tr>
    	<td>V-Model</td>
        <td>V-Model Merupakan salah satu model proses pembuatan software</td>
    </tr>
    <tr>
    	<td>Google Playstore</td>
    	<td>Google Playstore merupakan store aplikasi dari google yang menyediakan berbagai aplikasi Android baik yang gratis maupun yang berbayar</td>
    </tr>
    <tr>
    	<td>ALTIS</td>
        <td>ALTIS(APLIKASI LATIHAN UJIAN BERBASIS MOBILE APPS) merupakan aplikasi latihan ujian yang dirancang khusus untuk siswa SMK Ristek Multimedia dan Siswa SMK Pada Umumnya</td>
    </tr>
    <tr>
    	<td>SDD</td>
        <td>Software Design Description merupakan dokumen project software yang berisi tentang deskripsi desain software yang akan dirancang / dibuat</td>
    </tr>
    <tr>
    	<td>SPMP</td>
        <td>Software Project Manajemen Plan merupakan dokumen project software yang berisi tentang perencanaan pembangunan atau pengembangan software aplikasi secara umum</td>
    <tr>
    <tr>
    	<td>SRS</td>
        <td>Software Requirement Specification merupakan dokumen perangkat lunak yang berisi tentang requirement spesifikasi atau spesifikasi yang ada pada perangkat lunak yang akan dibangun atau dirancang</td>
    </tr>
 </table> 

 
 **1.5 DOKUMEN REFERENSI**
 
 Referensi yang digunakan pada perangkat lunak ini adalah: 

 -  SKPL-SRM, 2013. Bogor: Teknik Komputer 
 - DPPL-SRM, 2013. Bogor: Teknik Komputer 
 - GL03AT, template dokumen Deskripsi Uji Perangkat Lunak (DUPL) 
 - IEEE Std 610.12-1990 IEEE Standard Glossary of Software Engineering Terminology 
 - IEEE Std 829-1998 IEEE Standard for Software Test Documentation 
 
 ## BAB II
 ## LINGKUNGAN PENGUJIAN PERANGKAT LUNAK

**2.1 PERANGKAT LUNAK PENGUJIAN**

Perangkat Lunak ini diujikan dengan beberapa perangkat lunak lain, yaitu

 - Sistem operasi: Windows 7
 - Web server: XAMPP
 - Web browser: Mozzila Firefox
 - Scipting Language: PHP
 - DBMS : MySQL

**2.2 PERANGKAT KERAS PENGUJIAN**

Perangkat keras yang di perlukan untuk menguji aplikasi ini adalah satu set komputer dan satu set smartphone Android dengan spesifikasi:
 - Komputer
 - Processor: Intel Pentium Dual Core
 - Memory: 2 GB DDR3
 - Hardisk : 320 GB
 
 -  Android
 
 - Processor : Snapdragon 435
 - Memory : 2 GB
 - API	: 20
 
**2.3 SUMBER DAYA MANUSIA**

Sumber daya manusia yang dibutuhkan untuk menguji aplikasi ALTIS ini berjumlah empat orang dengan kriteria memahami konsep bahasa pemograman CSS, HTML, PHP, dan SQL.

**2.4 PROSEDUR UMUM PENGUJIAN**

2.4.1 Pengenalan dan Latihan 

Berhubung pihak yang terlibat dalam proses pengujian telah memenuhi persyaratan 2.4 dan dengan mempertimbangkan bahwa perngkat lunak dan keras yang dibutuhkan dalam pengujian sudah umum digunakan, maka pengenalan dan latihan tidak perlu dilakukan. 

2.4.2 PERSIAPAN AWAL

Persiapan awal yang khusus tidak dibutuhkan pada pengujian perangkat lunak ALTIS ini. 

2.4.2.1 Persiapan Prosedural

Pengujian ini dilakukan di luar lingkungan kampus. Dimana pengujian ini dilakukan oleh siswa dan guru. Alat yang digunakan 1 buah laptop dan Android dengan software yang telah di instalasi

2.4.2.2 Persiapan Perangkat Keras

Perangkat keras yang di perlukan untuk menguji aplikasi ini adalah satu set komputer dan satu set smartphone Android dengan spesifikasi:
 - Komputer
 - Processor: Intel Pentium Dual Core
 - Memory: 2 GB DDR3
 - Hardisk : 320 GB
 
 -  Android
 
 - Processor : Snapdragon 435
 - Memory : 2 GB
 - API	: 20

2.4.2.3 Persiapan Perangkat Lunak

Perangkat lunak yang digunakan untuk menguji adalah XAMPP Sebelum melakukan pengujian, terlebih dahulu perangkat lunak ALTIS disimpan di folder “htdocs” tempat perangkat lunak XAMPP tersebut diinstal. Misal jika XAMPP diinstal di drive C, maka ALTIS yang disimpan dalam folder projek akan disimpan di dengan nama C:/xampp/htdocs/altis 
Instruksi untuk mengaktifkan program: 
1. Jalankan server Apache dan MySQL yang ada di XAMPP Control Panel. 
2. Buka browser yang ada dan ketikkan: http://localhost/altis
3. Coba lakukan proses login sesuai dengan data pada database. 

 2. Android
 
 - Siapkan smartphone dengan sistem operasi Android
 - copy kan file apk ke dalam smartphone android
 - lakukan instalasi apk yang sudah di copy tadi
 
**2.4.3 Pelaksanaan**

Pelaksanaan pengujian langsung dilakukan pada tahap pengujian sistem dengan menguji fungsi-fungsi yang terdapat di dalam aplikasi ALTIS ini.  

**2.4.4 Pelaporan Hasil**

Dokumen hasil pengujian akan diserahkan kepada asisten praktikum Rekayasa Perangkat Lunak sebagai laporan dan kepada tim pengembang aplikasi untuk diperbaiki. 

## BAB III
## IDENTIFIKASI DAN RENCANA PENGUJIAN

| Kelas Uji | Butir Uji | Identifikasi || Tingkat Pengujian | Jenis Pengujian | Penguji |
| --- | --- | --- | --- | --- | --- | --- |
| --- | --- |SRS | STD | --- | --- | --- |
| Pengujian Login Siswa | Pengujian Login Siswa | SRS-ALTIS.K-0001 | STD-01 | Pengujian Sistem | Black box |Bahrainsyah   |
| --- | Kebenaran pengisian Username dan Password |   | STD-02 | Pengujian Sistem | Black box |Bahrainsyah   |
| Pengujian Login Guru | Pengujian Login Guru | SRS-ALTIS.K-0002 | STD-03 | Pengujian Sistem | Black box |Dody   |
| --- | Kebenaran pengisian Username dan Password |   | STD-04 | Pengujian Sistem | Black box |Dody   |
| Pengujian Login Admin | Pengujian Login Admin | SRS-ALTIS.K-0003 | STD-05 | Pengujian Sistem | Black box |Syahrul   |
| --- | Kebenaran pengisian Username dan Password |   | STD-06 | Pengujian Sistem | Black box |Syahrul |
| Pengujian Daftar Siswa | Pengujian Daftar Siswa | SRS-ALTIS.K-0004 | STD-07 | Pengujian Sistem | Black box |Bahrainsyah   |
| --- | Kebenaran dalam Daftar Siswa |   | STD-08 | Pengujian Sistem | Black box |Bahrainsyah   |
|  Pengujian Daftar Guru | Pengujian Daftar Guru | SRS-ALTIS.K-0005 | STD-09 | Pengujian Sistem | Black box |Syahrul   |
| --- | Kebenaran dalan Daftar Guru |   | STD-10 | Pengujian Sistem | Black box |Syahrul   |
| Pengujian Kelola Siswa | Pengujian Kelola Siswa | SRS-ALTIS.K-0006 | STD-11 | Pengujian Sistem | Black box |Dody   |
| --- | Kebenaran dalam Kelola Siswa |   | STD-12 | Pengujian Sistem | Black box |Syahrul   |
| Pengujian Kelola Guru | Pengujian Kelola Guru | SRS-ALTIS.K-0007 | STD-13 | Pengujian Sistem | Black box |Syahrul   |
| --- | Kebenaran dalam Kelola Guru |   | STD-14 | Pengujian Sistem | Black box |Bahrain   |
| Pengujian Lihat Buku | Pengujian Lihat Buku | SRS-ALTIS.K-0008 | STD-15 | Pengujian Sistem | Black box |Bahrain   |
| --- | Kebenaran dalam Lihat Buku |   | STD-16 | Pengujian Sistem | Black box |Bahrain   |
| Pengujian Kelola Buku | Pengujian Kelola Buku | SRS-ALTIS.K-0009 | STD-17 | Pengujian Sistem | Black box | Dody   |
| --- | Kebenaran dalam Kelola Buku |   | STD-18 | Pengujian Sistem | Black box |Dody   |
| Pengujian Lihat Latihan | Pengujian Lihat Latihan | SRS-ALTIS.K-0010 | STD-19 | Pengujian Sistem | Black box |Bahrain   |
| --- | Kebenaran dalam Lihat Latihan |   | STD-20 | Pengujian Sistem | Black box |Bahrain   |
| Pengujian Kelola Latihan | Pengujian Kelola Latihan | SRS-ALTIS.K-0011 | STD-21 | Pengujian Sistem | Black box |Dody   |
| --- | Kebenaran dalam Kelola Latihan |   | STD-22 | Pengujian Sistem | Black box | Dody  |
| Pengujian Lihat Ujian | Pengujian Lihat Ujian | SRS-ALTIS.K-0012 | STD-23 | Pengujian Sistem | Black box |Bahrain   |
| --- | Kebenaran dalam Lihat Ujian |   | STD-24 | Pengujian Sistem | Black box |Bahrain  |
| Pengujian Kelola Ujian | Pengujian Kelola Ujian | SRS-ALTIS.K-0013 | STD-25 | Pengujian Sistem | Black box |Dody   |
| --- | Kebenaran dalam Kelola Ujian |   | STD-26 | Pengujian Sistem | Black box |Dody   |
| Pengujian Lihat Statistik | Pengujian Lihat Statistik | SRS-ALTIS.K-0014 | STD-27 | Pengujian Sistem | Black box |Bahrain   |
| --- | Kebenaran dalam Lihat Statistik |   | STD-28 | Pengujian Sistem | Black box |Bahrain   |

## BAB IV
## DESKRIPSI HASIL UJI

| Identifikasi | Deskripsi | Prosedur Pengujian | Masukan | Keluaran yang diharapkan | Kriteria Evaluasi Hasil 1 | Kriteria Evaluasi Hasil 2 | Hasil Yang Didapat | Kesimpulan |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| STD-01 | Pengujian Login Siswa | Masukkan email dan password untuk masuk ke akun. Lihat form masuk ke menu login untuk pengecekan | Email dan Password | Notifikasi keberhasilan login | Apabila text field email dan password tidak di isi salah satu atau kedua nya, maka login akan gagal | Apabila email atau password salah, maka login akan gagal | Sukses | Diterima |
| STD-03 | Pengujian Login Guru | Masukkan email dan password untuk masuk ke akun. Lihat form masuk ke menu login untuk pengecekan | Email dan Password | Notifikasi keberhasilan login | Apabila text field email dan password tidak di isi salah satu atau kedua nya, maka login akan gagal | Apabila email atau password salah, maka login akan gagal | Sukses | Diterima |
| STD-05 | Pengujian Login Admin | Masukkan email dan password untuk masuk ke akun. Lihat form masuk ke menu login untuk pengecekan | Email dan Password | Notifikasi keberhasilan login | Apabila text field email dan password tidak di isi salah satu atau kedua nya, maka login akan gagal | Apabila email atau password salah, maka login akan gagal | Sukses | diterima |
| STD-07 | Pengujian Daftar Siswa | Buka pada menu daftar siswa, Masukan data siswa, tekan tombol daftar | Masukkan username, nama siswa, password, nisn, jurusan,  nama ayah, nama ibu, nama wali, ttl, kelas, alamat, no hp, no hp orang tua, foto | Notifikasi keberhasilan daftar siswa | Apabila data ada yang kosong, maka akan ada perintah &quot;harap isi data dengan lengkap&quot; | Apabila tipe data tebalik, misalnya untuk nisn harusnya angka malah di isi huruf, maka data yang akan di daftar kan akan gagal | Sukses | Diterima |
| STD-09 | Pengujian Daftar Guru | Buka pada menu daftar guru, Masukan data guru, tekan tombol daftar | Masukkan username, nama, password, nip, mata pelajaran 1, mata pelajaran 2, mata pelajaran 3, no hp, alamat, email, foto | Notifikasi keberhasilan daftar siswa | Apabila data ada yang kosong, maka akan ada perintah &quot;harap isi data dengan lengkap&quot; | Apabila tipe data tebalik, misalnya untuk nip harusnya angka malah di isi huruf, maka data yang akan di daftar kan akan gagal | Sukses | Diterima |
| STD-11 | Pengujian Kelola Siswa | Pilih menu login siswa, pilih profil, pilih salah satu data yang ingin di ubah lalu tekan update | Masukkan username, nama siswa, password, nisn, jurusan,  nama ayah, nama ibu, nama wali, ttl, kelas, alamat, no hp, no hp orang tua, foto |   | Jika ada salah satu data yang kosong, ketika menekan tombol kelola maka akan ada peringatan &quot;harap lengkapi data yang kosong&quot; | Apabila tipe data tebalik, misalnya untuk nisn harusnya angka malah di isi huruf, maka data yang akan di daftar kan akan gagal | Sukses | diterima |
| STD-13 | Pengujian Kelola Guru | Pilih menu login guru, pilih profil, pilih salah satu data yang ingin di ubah lalu tekan update | Masukkan username, nama, password, nip, mata pelajaran 1, mata pelajaran 2, mata pelajaran 3, no hp, alamat, email, foto | Notifikasi keberhasilan dalam mengelola data guru | Jika ada salah satu data yang kosong, ketika menekan tombol kelola maka akan ada peringatan &quot;harap lengkapi data yang kosong&quot; | Apabila tipe data tebalik, misalnya untuk nisn harusnya angka malah di isi huruf, maka data yang akan di daftar kan akan gagal | Sukses | Diterima |
| STD-15 | Pengujian Lihat Buku | Pilih menu login siswa atau guru, pilih menu buku, pilih kategori, pilih buku yang akan di baca |   | Siswa atau guru dapat melihat buku yang akan dibaca | Koneksi internet error, buku tidak ditampilkan | Jika internet down, maka buku yang di muat akan lama untuk di tampilkan | Sukses | Diterima |
| STD-17 | Pengujian Kelola Buku | Pilih menu login guru, pilih menu kelola buku,  masukkan data buku yang akan di kelola, tekan tombol kelola | Masukkan Judul Buku, Kategori, Penerbit, Penulis, File, Cover | Notifikasi keberhasilan dalam mengelola buku | Ketika ada data yang kosong, maka akan ada peringatan &quot;harap isi data dengan lengkap&quot;  | Jika cover ukurannya lebih dari  2 mb, maka data akan gagal tersimpan | Sukses | diterima |
| STD-19 | Pengujian Lihat Latihan | Pilih menu login siswa atau guru, pilih menu latihan, pilih kategori latihan, pilih latihan |   | Siswa dapat melihat latihan yang ingin di kerjakan | Koneksi internet error, latihan tidak ditampilkan | Jika internet latihan, maka buku yang di muat akan lama untuk di tampilkan | Sukses | Diterima |
| STD-21 | Pengujian Kelola Latihan | Pilih menu login guru, pilih menu kelola latihian,  masukkan data latihan yang akan di kelola, tekan tombol kelola | Masukkan jawaban a, jawaban b, jawaban c, jawaban d, foto, soal | Notifikasi keberhasilan dalam mengelola latihan | Ketika ada data yang kosong, maka akan ada peringatan &quot;harap isi data dengan lengkap&quot;  | Jika ada latihan dengan foto lebih dari 2 mb, maka data akan gagal tersimpan | Sukses | Diterima |
| STD-23 | Pengujian Lihat Ujian | Pilih menu login siswa atau guru, pilih menu ujian, pilih kategori ujian, pilih ujian | | Siswa atau guru dapat melihat ujian yang akan dikerjakan | Koneksi internet error, ujian tidak ditampilkan | Jika internet down, maka ujian yang di muat akan lama untuk di tampilkan | Sukses | diterima |
| STD-25 | Pengujian Kelola Ujian | Pilih menu login guru, pilih menu kelola ujian,  masukkan data ujian yang akan di kelola, tekan tombol kelola | Masukkan jawaban a, jawaban b, jawaban c, jawaban d, foto, soal | Notifikasi keberhasilan dalam mengelola data ujian | Ketika ada data yang kosong, maka akan ada peringatan &quot;harap isi data dengan lengkap&quot;  | Jika ada foto dengan ukuran lebih dari 2 mb, maka data akan gagal tersimpan | Sukses | Diterima |
| STD-27 | Pengujian Lihat Statistik | Pilih menu login siswa, pilih menu statistik |   | Siswa dapat melihat statistik nilai | Koneksi internet error, statistik tidak ditampilkan | Jika internet down, maka statistik yang di muat akan lama untuk di tampilkan | Sukses | diterima |

 
