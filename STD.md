


<div align="center">

## **DOCUMENT PENGUJIAN PERANGKAT LUNAK**

Version 1.0

11 Maret 2018

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

**2.3 MATERIAL PENGUJIAN**


**2.4 SUMBER DAYA MANUSIA**

Sumber daya manusia yang dibutuhkan untuk menguji aplikasi ALTIS ini berjumlah empat orang dengan kriteria memahami konsep bahasa pemograman CSS, HTML, PHP, dan SQL.

**2.5 PROSEDUR UMUM PENGUJIAN**

2.5.1 Pengenalan dan Latihan 

Berhubung pihak yang terlibat dalam proses pengujian telah memenuhi persyaratan 2.4 dan dengan mempertimbangkan bahwa perngkat lunak dan keras yang dibutuhkan dalam pengujian sudah umum digunakan, maka pengenalan dan latihan tidak perlu dilakukan. 

2.5.2 PERSIAPAN AWAL

Persiapan awal yang khusus tidak dibutuhkan pada pengujian perangkat lunak ALTIS ini. 

2.5.2.1 Persiapan Prosedural

Pengujian ini dilakukan di luar lingkungan kampus. Dimana pengujian ini dilakukan oleh siswa dan guru. Alat yang digunakan 1 buah laptop dan Android dengan software yang telah di instalasi

2.5.2.2 Persiapan Perangkat Keras

Perangkat keras yang di perlukan untuk menguji aplikasi ini adalah satu set komputer dan satu set smartphone Android dengan spesifikasi:
 - Komputer
 - Processor: Intel Pentium Dual Core
 - Memory: 2 GB DDR3
 - Hardisk : 320 GB
 
 -  Android
 
 - Processor : Snapdragon 435
 - Memory : 2 GB
 - API	: 20

2.5.2.3 Persiapan Perangkat Lunak

Perangkat lunak yang digunakan untuk menguji adalah XAMPP Sebelum melakukan pengujian, terlebih dahulu perangkat lunak ALTIS disimpan di folder “htdocs” tempat perangkat lunak XAMPP tersebut diinstal. Misal jika XAMPP diinstal di drive C, maka ALTIS yang disimpan dalam folder projek akan disimpan di dengan nama C:/xampp/htdocs/altis 
Instruksi untuk mengaktifkan program: 
1. Jalankan server Apache dan MySQL yang ada di XAMPP Control Panel. 
2. Buka browser yang ada dan ketikkan: http://localhost/altis
3. Coba lakukan proses login sesuai dengan data pada database. 

 2. Android
 
 - Siapkan smartphone dengan sistem operasi Android
 - copy kan file apk ke dalam smartphone android
 - lakukan instalasi apk yang sudah di copy tadi
 
**2.5.3 Pelaksanaan**

Pelaksanaan pengujian langsung dilakukan pada tahap pengujian sistem dengan menguji fungsi-fungsi yang terdapat di dalam aplikasi ALTIS ini.  

**2.5.4 Pelaporan Hasil**

Dokumen hasil pengujian akan diserahkan kepada asisten praktikum Rekayasa Perangkat Lunak sebagai laporan dan kepada tim pengembang aplikasi untuk diperbaiki. 

## BAB III
## IDENTIFIKASI DAN RENCANA PENGUJIAN

| Kelas Uji | Butir Uji | Identifikasi | Tingkat Pengujian | Jenis Pengujian | Penguji |
| --- | --- | --- | --- | --- | --- |
| SRS | STD |
| Pengujian Login Siswa | Pengujian Login Siswa | SRS-ALTIS.K-0001 | STD-01 | Pengujian Sistem | Black box |   |
| Kebenaran pengisian Username dan Password |   | STD-02 | Pengujian Sistem | Black box |   |
| Pengujian Login Guru | Pengujian Login Guru | SRS-ALTIS.K-0002 | STD-03 | Pengujian Sistem | Black box |   |
| Kebenaran pengisian Username dan Password |   | STD-04 | Pengujian Sistem | Black box |   |
| Pengujian Login Admin | Pengujian Login Admin | SRS-ALTIS.K-0003 | STD-05 | Pengujian Sistem | Black box |   |
| Kebenaran pengisian Username dan Password |   | STD-06 | Pengujian Sistem | Black box | |
| Pengujian Daftar Siswa | Pengujian Daftar Siswa | SRS-ALTIS.K-0004 | STD-07 | Pengujian Sistem | Black box |   |
| Kebenaran dalan Daftar Siswa |   | STD-08 | Pengujian Sistem | Black box |   |
|  Pengujian Daftar Guru | Pengujian Daftar Guru | SRS-ALTIS.K-0005 | STD-09 | Pengujian Sistem | Black box |   |
| Kebenaran dalan Daftar Guru |   | STD-10 | Pengujian Sistem | Black box |   |
| Pengujian Kelola Siswa | Pengujian Kelola Siswa | SRS-ALTIS.K-0006 | STD-11 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Kelola Siswa |   | STD-12 | Pengujian Sistem | Black box |   |
| Pengujian Kelola Guru | Pengujian Kelola Guru | SRS-ALTIS.K-0007 | STD-13 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Kelola Guru |   | STD-14 | Pengujian Sistem | Black box |   |
| Pengujian Lihat Buku | Pengujian Lihat Buku | SRS-ALTIS.K-0008 | STD-15 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Lihat Buku |   | STD-16 | Pengujian Sistem | Black box |   |
| Pengujian Kelola Buku | Pengujian Kelola Buku | SRS-ALTIS.K-0009 | STD-17 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Kelola Buku |   | STD-18 | Pengujian Sistem | Black box |   |
| Pengujian Lihat Latihan | Pengujian Lihat Latihan | SRS-ALTIS.K-0010 | STD-19 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Lihat Latihan |   | STD-20 | Pengujian Sistem | Black box |   |
| Pengujian Kelola Latihan | Pengujian Kelola Latihan | SRS-ALTIS.K-0011 | STD-21 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Kelola Latihan |   | STD-22 | Pengujian Sistem | Black box |   |
| Pengujian Lihat Ujian | Pengujian Lihat Ujian | SRS-ALTIS.K-0012 | STD-23 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Lihat Ujian |   | STD-24 | Pengujian Sistem | Black box |   |
| Pengujian Kelola Ujian | Pengujian Kelola Ujian | SRS-ALTIS.K-0013 | STD-25 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Kelola Ujian |   | STD-26 | Pengujian Sistem | Black box |   |
| Pengujian Lihat Statistik | Pengujian Lihat Statistik | SRS-ALTIS.K-0014 | STD-27 | Pengujian Sistem | Black box |   |
| Kebenaran dalam Lihat Statistik |   | STD-28 | Pengujian Sistem | Black box |   |

## BAB IV
## DESKRIPSI HASIL UJI



 
