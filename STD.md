


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


## BAB IV
## DESKRIPSI HASIL UJI



 
