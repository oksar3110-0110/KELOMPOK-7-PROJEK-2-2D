<div align="center">

## **SOFTWARE PROJECT MANAJEMEN PLAN**

Version 2.2

15 April 2018

<img src="https://oksareinaldi.files.wordpress.com/2018/02/polindra.png?w=421&h=421&crop=1" width="250" height="250">

**APLIKASI LATIHAN UJIAN BERBASIS MOBILE APPS (ALTIS)**

​                                                      Disusun Oleh :

​                                                           Bahrainsyah Oksareinaldi (1603092)

​                                                           Dodi Hodayat (1603095)

​                                                           Muhroz Al Farizi (1603108)

​                                                           Syahrul Romadoni (1603114)

​                                                               **D3 Teknik Informatika**

​                                                            ​**Politeknik Negeri Indramayu**
</div>

## **Software Project Manajemen Plan**

**BAB 1 Pendahuluan**

   **1.1 Gambaran Proyek**

   Aplikasi latihan ujian berbasis mobile apps (ALTIS) merupakan aplikasi yang ditujukan untuk pelajar SMK. Aplikasi ini dapat dijalankan melalui platform android dan disediakan dashboard admin berbasis web untuk pengelolaan administrasinya. Didalam aplikasi ini memuat soal - soal latihan ujian dan beberapa materi mata pelajaran yang berkaitan dengan multimedia. Pada proses pembuatan aplikasi ini kami bekerjasama dengan SMK RISTEK MULTIMEDIA Indramayu.
Didalam aplikasi ini selain menyediakan fitur latihan soal dan materi, terdapat juga fitur penyajian nilai tiap - tiap siswa yang berupa grafik dan sistem perangkingan perolehan nilai.

   **1.2 Dokumen Dokumen dalam Proyek**
   
-    SPMP (Software Project Manajemen Plan)
-    SRS (Software Requirement Spesification)
-    SDD (Software Design Description)
-    Surat MoU Dengan Mitra SMK RISTEK Indramayu
-    Proposal Proyek
-    Laporan Hasil Proyek


   **1.3 Evolusi SPMP**

  Dokumen ini bersifat tertutup, hanya orang - orang yang sudah dipercayakan saja yang dapat mengakses dan mengubah isi dokumen ini. Dokumen ini hanya akan di-update oleh orang yang memiliki wewenang saja seperti Developer dan Admin yang ditunjuk saja.

   **1.4 Material Acuan**
   
-   IEEE Std 610.12-1990, IEEE Standard Glossary of Software Engineering Terminology. 1
-   http://www.utdallas.edu/~chung/CS6354/CS6354_U07_source/Team_2/SoftwareProjectManagement_Plan_v1.1_Team2.doc
-    ESA. ESA Software Engineering Standards. Mar 1995.
   

   **1.5 Definisi dan Akronim \(Singkatan\)**
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

**BAB 2 Organisasi Proyek**

**2.1 Model Proses**

Model proses yang diterapkan pada proses pembuatan aplikasi ini ialah model V-Model karena dianggap cukup mudah dalam setiap langkahnya. Model V-Model sendiri memudahkan perancang ketika terjadi suatu perubahan yang memungkinkan kembali ke proses sebelumnya. Berikut Uraiannya :

<img src="https://oksareinaldi.files.wordpress.com/2018/03/alur.png?w=636&h=291">
<center>Gambar 2.1.1 Model Proses</center>
<table>
	<tr>
    	<td>a.</td>
    	<td>Requirement</td>
        <td>Menentukan permintaan sistem yang akan dibuat berdasarkan batasan masalah yang ada.</td>
    </tr>
    <tr>
    	<td>b.</td>
    	<td>Specification</td>
        <td>Menentukan spesifikasi sistem aplikasi yang akan dibuat agar dapat memenuhi permintaan.</td>
    </tr>
    <tr>
    	<td>c.</td>
    	<td>Architectural Design</td>
        <td>Mendesain arsitektur sistem beserta alur kerja dari setiap bagian sistem.</td>
    </tr>
    <tr>
    	<td>d.</td>
    	<td>Detailed Design	</td>
        <td>Mendesain detail dari aplikasi beserta membuat asset - asset yang terdapat pada aplikasi.</td>
    </tr>
    <tr>
    	<td>e.</td>
    	<td>Coding</td>
        <td>Membangun sistem aplikasi dengan menggunakan code program.</td>
    </tr>
    <tr>
    	<td>f.</td>
    	<td>Unit Testing</td>
        <td>Menguji setiap unit bagian dari sistem aplikasi.</td>
    </tr>
    <tr>
    	<td>g.</td>
    	<td>Integration Testing</td>
        <td>Menguji hubungan antara satu bagian sistem dengan bagian yang lainnya.</td>
    </tr>
    <tr>
    	<td>h.</td>
    	<td>System Testing</td>
        <td>Menguji sistem secara keseluruhan.</td>
    </tr>
    <tr>
    	<td>i.</td>
    	<td>Acceptane Testing</td>
        <td>Menguji sistem aplikasi pada lingkungan client apakah sesuai dengan permintaan atau tidak.</td>
    </tr>
</table>

**2.2 Struktur Organisasi**

<img src="https://oksareinaldi.files.wordpress.com/2018/03/struktur-organisasi.png?w=417&h=215" align="center">

<center>Gambar 2.2.1 Struktur Organisasi</center>

**2.3 Batasan dan Antarmuka Organisasi**

  Batasan dari aplikasi ini adalah hanya bisa diakses oleh siswa, guru dan admin pada SMK RISTEK Multimedia Indramayu. untuk penggunaan yang lebih luasnya akan dikembangkan lagi agar bisa di upload di google playstore dan dapat diakses oleh siswa secara umum dan soal yang diberikan akan di ubah menjadi soal latihan ujian nasional.

**2.4 Lingkup Tanggung Jawab**

- Bahrainsyah Oksareinaldi : Project Leader, Mobile Developer, UI Design
- Dodi Hidayat				  : Database, Mobile Developer, Dokumen
- Muhroz Al Farizi			: Dokumen
- Syahrul Romadoni			: UI Design, Database, Web Developer


**BAB 3 Proses Menajerial** 

**3.1 Tujuan dan prioritas manajemen**

  Tujuan dari proyek ini adalah supaya siswa/siswi smk yang mau UN bisa latihan sendiri dirumah karna aplikasi ini bisa dibawa kemana saja. prioritas utama yaitu SMK RISTEK MULTIMEDIA Indramayu.

**3.2 Asumsi-asumsi, tergantungan/kertetarikan, dan batasan-batasan**

  Asumsi-asumsi dan batasan aplikasi ini sendiri, aplikasi ini masih di siklus sekitar mitra dan belum di perluaskan atau di download di playstore. Aplikasi ini tergantung pada koneksi internet karena dalam mengakses databasenya harus menggunakan koneksi internet yang stabil.

**3.3 Manajemen resiko**

-   Tidak semua siswa mempunyai smartphone, oleh karena itu pada aplikasi ini dalam penggunaannya di setting supaya setiap device smartphone berbeda soal agar semua siswa dapat mengakses soal ujian dengan beberapa smartphone secara bergantian.
-   Konektivitas internet yang terbatas sehingga dapat meenjadi masalah dalam proses pengiriman data dari database sehingga pada desain dibuat sederhana mungkin agar tidak terlalu membebankan koneksi internet. 
  

**3.4 Mekanisme monitoring dan kontroling**

  Sistem monitoring dan kontroling di pegang oleh administrator. Setiap traffic yang ada di monitor oleh admin dan ketika terjadi suatu permasalahan maka admin dapat menghubungi developer aplikasi untuk dilakukan maintance.

**3.5 Perencanaan Staff**

<table>
	<tr>
    	<td>Project manager</td>
        <td>Bahrainsyah Oksareinaldi</td>
    </tr>
    <tr>
    	<td>Mobile Developer</td>
        <td>Bahrainsyah Oksareinaldi & Dody Hidayat</td>
    </tr>
    <tr>
    	<td>Web Developer</td>
        <td>Syahrul Romadoni</td>
    </tr>
    <tr>
    	<td>Database</td>
        <td>Dody Hidayat & Syahrul Romadoni</td>
    </tr>
    <tr>
    	<td>UI Design</td>
        <td>Syahrul Romadoni & Bahrainsyah Oksareinaldi</td>
    </tr>
   <tr>
    	<td>Dokumen</td>
        <td>Muhroz Al Farizi & Dody Hidayat</td>
    </tr>
</table>

**BAB 4 Proses Teknis** 

**4.1 Metode, Alat, dan Teknik**

  Model proses yang diterapkan pada proses pembuatan aplikasi ini ialah model V-Model karena dianggap cukup mudah dalam setiap langkahnya. Model V-Model sendiri memudahkan perancang ketika terjadi suatu perubahan yang memungkinkan kembali ke proses sebelumnya, dan alat seperti Android Studio, Visio, CorelDraw, Photoshop, dan Sublime akan digunakan. Teknik analisis berorientasi objek akan digunakan untuk menyelesaikan proyek dengan sukses.

**4.2 Dokumentasi Perangkat Lunak**

  Dokumentasi seperti piagam proyek, Dokumen Kebutuhan Bisnis, Dokumen Spesifikasi Fungsional, Analisis Manfaat Biaya, dokumen Spesifikasi Teknis, dokumen desain detail, Rencana Uji, Rencana Pelaksanaan, dan dokumen Realisasi Manfaat.

**4.3 Fungsi pendukung proyek**

- Ahli Jaringan Komputer
- Web Hosting Provider

**BAB 5 PAKET PEKERJAAN, RENCANA ANGGARAN, DAN JADWAL** 

**5.1 Paket Pekerjaan**
<table>
	<tr>
    	<td>NO</td>
        <td>Nama</td>
        <td>Jabatan</td>
        <td>Modul</td>
    </tr>
    <tr>
    	<td>1. </td>
        <td>Bahrainsyah Oksareinaldi</td>
        <td>Project Manager, UI Design, Mobile Developer</td>
        <td>
        <li>Mobile Developer : Modul Login, Lupa Password, Register Siswa</li>
        <li>UI Design : Modul UI Android</li>
        </td>
    </tr>
    <tr>
    	<td>2. </td>
        <td>Dody Hidayat</td>
        <td>Mobile Developer, Database, Dokumen</td>
        <td>
        	<li>Mobile Developer : Modul Ujian, Modul Statistik Nilai, Modul Profile</li>
            <li>Database : Database Android & WEB</li>
            <li>Dokumen : SRS (Software Requirement Spesification)</li>
        </td>
    </tr>
    <tr>
    	<td>3. </td>
        <td>Muhroz Al Farizi</td>
        <td>Dokumen</td>
        <td>
        <li>SPMP (Software Project Manajemen Plan)</li>
        <li>SRS (Software Requirement Spesification)</li>
        <li>SDD (Software Design Description)</li>
        </td>
    </tr>
    <tr>
    	<td>4. </td>
        <td>Syahrul Romadoni</td>
        <td>WEB Developer, UI Design, Database</td>
        <td>
        <li>WEB Developer : Front End & Back End WEB</li>
        <li>UI Design : UI Design WEB</li>
        <li>Database : Database WEB</li>
        </td>
    </tr>
</table>

**5.2 RENCANA ANGGARAN BIAYA**

PengembanganSistem Aplikasi Simulasi Ujian Berbasis Mobile

I. BIAYA LANGSUNG PERSONIL

| NO     | Keahlian                          | Volume |       | Harga Satuana | Jumlah Harga   |
| ------ | --------------------------------- | ------ | ----- | ------------- | -------------- |
|        |                                   | Jumlah | Waktu |     (Rp)      | (Rp)           |
| A.     | Biaya Tenaga Ahli                 |        |       |               |                |
| 1.     | Ahli Perancangan Sistem Informasi | 4      |   4   | Rp 3.500.000  | Rp 14.000.000  |
| 2.     | Ahli Perancangan Basis  Data      | 2      |   4   | Rp. 3000.000  | Rp. 6000.000   |
| 3.     | Ahli Pemograman Komputer          | 2      |   4   | Rp 5.000.000  | Rp. 10.000.000 |
| 4.     | Sistem Analis                     | 1      |   4   | Rp. 3.000.000 | Rp. 3.000.000  |
| Jumlah | Rp. 33.000.000                    |        |       |               |                |

II. BIAYA LANGSUNG NON PERSONIL

| No     | Keahlian                            | Volume |         | Harga satuan  | Jumlah harga   |
| ------ | ----------------------------------- | ------ | ------- | ------------- | -------------- |
|        |                                     | Jumlah | Waktu   | (Rp)          | (Rp)           |
| A.     | Biaya Perangkat Lunak dan Pelatihan |        |         |               |                |
| 1.     | Komputer atau laptop                | 4      |         | Rp. 9.000.000 | Rp. 36.000.000 |
| 2.     | Dokumentasi                         | 4Ls    |         |               | Rp. 1000.000   |
| 3.     | Software CorelDraw X7 Original      | 1      | 1 Tahun | Rp. 1.150.000 | Rp. 1.150.000  |
| 4.     | Software Photoshop CC original      | 1      | 1 Tahun | Rp. 3.460.000 | Rp. 3.460.000  |
| 5.     | Akun Google Play                    | 1      | 1 tahun | Rp. 300.000   | Rp. 300.000    |
| Jumlah | Rp. 41.910.000                      |        |         |               |                |

 **5.3 Jadwal.**
 
 <img src="https://oksareinaldi.files.wordpress.com/2018/03/jadwal.png?w=636&h=185">

 
