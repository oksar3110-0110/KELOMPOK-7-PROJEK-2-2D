<div align="center">

## **SOFTWARE DESIGN DESCRIPTIONS**

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

## **BAB I Pendahuluan**

Pada bagian ini memberikan deskripsi dan gambaran mengenai apapun yang terdapat pada dokumen SDD. Juga tujuan dari pembuatan dari dokumen ini di gambarkan dan di urutkan juga 
didefinisikan.

 **1.1	Tujuan Penulisan Dokumen**

Tujuan dari pembuatan dokumen ini adalah untuk memberikan detail dari System Requirement dari "Aplikasi Latihan Ujian Nasional Berbasis Mobile Apps". Pada dokumen ini 
mengilustrasikan tujuan dan pernyataan lengkap dari pembuatan sistem. Dokumen ini juga menjelaskan spesifikasi system, interface dan hubungan dengan aplikasi lainnya.

  **1.2	Lingkup Masalah**

"Aplikasi Latihan Ujian Berbasis Mobile Apps" merupakan sebuah aplikasi mobile yang dibuat bekerja sama dengan mitra yaitu SMK RISTEK MULTIMEDIA Indramayu. Pada aplikasi ini 
disediakan materi, latihan soal dan soal - soal yang diharapkan dapat meningkatkan mutu dari siswa - siswa dalam kompetensinya.

Batasan dari aplikasi ini ialah pada soal - soal dan materi, hanya berkaitan dengan bidang multimedia dan beberapa materi pelajaran wajib. Pada aplikasi inipun disediakan juga 
fitur live chat antar sesama siswa. Juga disediakan fitur perangkingan berbasis grafik.

 **1.3 Definisi dan Istilah**

Mobile Apps   : Aplikasi perangkat bergerak meliputi IOS, Android.
Firebase 	 : Database realtime dari google yang tidak berbasis DBMS.
 Live Chat	 : Merupakan aplikasi Chatting yang up to date terhadap perubahan dalam waktu maksimal 5 detik.

 **1.4 Aturan Penamaan dan Penomoran**

 **1.5 Referensi**

- IEEE Draft Standard for Software Design Descriptions,12 December 2005
- Pressman, Roger S. 2001. Software engineering: a practitioner’s approach 5th ed. New York : McGraw-Hill Companies, Inc.

 **1.6 Ikhtisar Dokumen**



## **BAB 2 Global**

**2.1 Rangcangan Lingkungan Implementasi**

- Windows 7
- Windows 10
- Xubuntu 16.04LT
- Android Studio
- Xampp
- Sublem
- HTML
- PHP
- Java
- Javascript
- SQL

**2.2 Deskripsi Data**

**2.2.1 Definisi Domain Model**

**2.2.2 Conceptual Data Model**

**2.2.3 Physical Data Model**

**2.2.4 Daftar Tabel Aplikasi**

**2.3 Deskripsi Model**



## **BAB 3 Perancangan Rinci**

**3.1 	Kebutuhan Fungsional**

Kebutuhan fungsional (Fungsional Requirements) ini adalah kebutuhan utama yang diharapkan dari sistem ini, yang terkait langsung dengan sistem ini. Kebutuhan fungsional dari sistem ini adalah sebagai berikut :

1.Registrasi User

2.Login User

3.Manajemen Soal

4.Manajemen Materi

5.Statistik

6.Chatting Area

7.View Soal latihan

8.View Soal ujian

9.View Materi

**3.1.1	Spesifikasi yang diharapkan pada Registrasi User**

- Membedakan antara user biasa dan guru.
- Terintegrasi dengan E-mail untuk keperluan Chatting (Konfirmasi email diperlukan pada fitur chat).
- Khusus user guru dapat dilakukan oleh admin melalui fitur tambah guru.

	*3.1.2	Spesifikasi yang diharapkan pada Login User**

- Dapat membedakan antara user yang sudah terdaftar dan belum.
- Proses login dapat merespon dengan cepat.
- Login menggunakan username email dan password.

**3.1.3 Spesifikasi yang diharapkan pada Manajemen Soal**

- Terdapat daftar soal yang sudah ada.
- Setiap soal memiliki mata pelajaran masing - masing.
- Setiap soal disertai dengan jawabannya masing - masing.
- Soal memiliki tabel tersendiri.

**3.1.4 Spesifikasi yang diharapkan pada Manajemen Materi**

- Setiap materi berupa E - Book.
- E-Book ditampilkan bera thumbnail Cover.
- Materi ditampilkan berupa kategori - kategori.

**3.1.5 Spesifikasi yang diharapkan pada Statistik**

- Ditampilkan statistik perolehan nilai per-User siswa dan Perankingan Nilai user siswa per mata pelajaran.
- Nilai disajikan dalam bentuk Chart yang interaktif dan realtime.
- Chart Statistik dapat dilihat oleh guru, siswa maupun admin.

**3.1.6 Spesifikasi yang diharapkan pada Chatting Area**

- Chatting Area hanya berlaku untuk user Siswa saja.
- Chatting Area menggunakan database tesendiri yaitu Firebase dan terpisah dengan MySQL namun tetap mengambil username/email dari database MySQL.
- Chatting disajikan secara menarik dan realtime, antar siswa dapat saling berkomunikasi bisa melalui chat pribadi maupu grup chat.

**3.1.7 Spesifikasi yang diharapkan pada View Soal Latihan**

- Tiap soal latihan berdasarkan materi.
- Soal diacak urutan nomornya.
- Latihan soal berformat pilihan ganda bukan essay.
- Tiap latihan soal memiliki waktu hitung mundur selama satu jam.

**3.1.8 Spesifikasi yang diharapkan pada View Soal Ujian**

- Soal ujian berdasarkan materi.
- Tiap user diberikan waktu selama satu jam.
- Tiap menjawab soal ujian, user tidak diizinkan untuk membuka chat maupun browser.
- Soal ujian berformat pilihan ganda, bukan essay.

**3.1.9  Spesifikasi yang diharapkan pada View Materi**

- View Materi berupa thumbnail thumbnail E - Book.
- Tiap Thumbnail memiliki keterangan dibawahnya.
- Tiap user siswa dapat mengakses View Materi untuk pembelajaran.

**3.2 Kebutuhan Non Fungsional**

Kebutuhan yang mendukung kelancaran sistem ini didefinisikan sebagai berikut :

- Availabilty  : Ketersediaan sistem selama 24 Jam Non - Stop dengan kondisi jaringan internet yang stabil dan tidak bermasalah.

- Reliability  : Sistem data reliabel berhubungan dengan materi ddan soal yang ada juga nilai yang tampil sesuai yang didapat.

- Ergonomy     : Tampilan dibuat user friendly memperhatikan aspek interaksi manusia komputer.

- Portability  : Halaman admin dapat diakses berbagai macam browser yang mendukung JS dan Bootstrap. Untuk aplikasi mobile dapat diakses pada platform android 4.0 Keatas.

- Memory       : Minimum memory yang dipakai oleh sistem tidak sampai 100 MB.

- Response Time : Waktu Response dari sistem tidak lebih dari 5 detik.

- Security     : Login dan verifikasi password dan juga verifikasi email untuk chat.

**3.3 Kebutuhan Antar Muka (Interfaces)**

Antar muka untuk aplikasi ALTIS dibagi dua yaitu :

1. Software Interface : Adalah kebutuhan perangkat lunak untuk mengimplementasikan sistem ALTIS : 

-  MySQL dan PHP 7
-  Framework CI
-  Sublime Text
-  Android Studio

2. Hardware Interface : Adalah kebutuhan Hardware untuk mengimplementasikan sistem ALTIS :

- PC / Laptop.
- Modem untuk koneksi internet.
- Adroid Smartphone.

**3.4 Lingkungan Operasi**

Sistem dapat bekerja dengan baik pada lingkungan operasi Sbb :

- OS	: Windows/Linux/Android Kitkat 4.0.
	 DBMS	: MySQL dan Firebase.
	 Pemrograman	: Java, PHP, HTML.

**3.5 Batasan Perancangan**

Pada perancangan program ini adalah berbasis Mobile dan WEB. Bahasa Pemrograman yang dipakai adalah java dan PHP dengan Framework CI.

**3.6 Model Proses**

Untuk menggambarkan pemodelan proses digunakan DFD (Data Flow Diagram), yang
untuk masing-masing level akan digambarkan sebagai berikut:

**DFD Level 0 (Context Diagram)**

Dalam perancangan DFD Level 0, entitas eksternal yang terlihat adalah :

1. Siswa
2. Guru
3. Admin

Yang dapat digambarkan sebagai berikut :

<img src="https://oksareinaldi.files.wordpress.com/2018/03/blank-diagram-1.jpeg?w=640" align="center" width="500">

**DFD Level 1**

Pada DFD level 1 ini , proses-proses yang didekomposisi dari DFD level 0 yaitu:

1. Proses Registrasi User

2. Proses Login User

3. Proses Manajemen Soal

4. Proses Manajemen Materi

5. Proses Statistik

6. Proses Chatting Area

7. Proses View Soal latihan

8. Proses View Soal ujian

9. Proses View Materi

10. Proses Manajemen Siswa

11. Proses Manajemen Guru 

Yang masing-masing entitas dan prosesnya dapat digambarkan sebagai berikut:

<img src="https://oksareinaldi.files.wordpress.com/2018/03/blank-diagram-lvl-1.png?w=640" width="600">

**3.10 Interface Design Input Page Design**

Pada Bagian ini akan menjelaskan bagaimana interface (antarmuka), beberapa 
berupa Page (halaman website) dan apps (aplikasi) untuk interaksi Siswa/Siswi, 
Guru dan Admin yang akan direncanakan produk ini, yang meliputi :

- Desain untuk Frontpage Website (Halaman Login Guru dan Admin).
- Desain untuk Frontpage Website (Halaman Utama Website Guru dan Admin).
- Desain untuk Frontpage Website (Halaman Tambah Buku Guru dan Admin).
- Desain untuk Frontpage Website (Halaman Tambah Siswa/siswi Guru dan Admin).
- Desain untuk Frontpage Website (Halaman Tambah Guru Admin).
- Desain untuk Frontpage Android (Halaman Login Siswa/Siswi).
- Desain untuk Frontpage Android (Halaman Tampilan Utama Aplikasi).
- Desain untuk Frontpage Android (Halaman Buku Pelajaran).
- Desain untuk Frontpage Android (Halaman latihan Ujian).
- Desain untuk Frontpage Android (Halaman Ujian).
- Desain untuk Frontpage Android (Halaman Statistic).

**Input Page Design**

Desain page input ini merupakan semua page input yang akan digunakan pada 
sistem 'APLIKASI LATIHAN SOAL UJIAN BERBASIS MOBILE APPS'. Page input ini 
meliputi :

- Page Tambah Buku (Guru dan Admin).
- Page Tambah Siswa/siswi (Guru dan Admin).
- Page Tambah Guru (Admin).
- Page Tambah Soal Latihan Ujina (Guru dan Admin).
- Page Tambah Soal Ujian (Guru dan Admin).

**Page Halaman Login Website**

Interface ini merupakan halaman Login buat Admin atau Guru yang sudah memiliki Email atau Password yang sudah di bikin oleh Admin.

<img style="width: 50%" src="https://oksareinaldi.files.wordpress.com/2018/03/login1.png?w=315&h=165">



**Page Halaman Utama**

Interface ini merupakan halaman Utama dari website Admin atau Guru yang sudah berhasil login saat Page Login.

<img style="width: 50%" src="https://oksareinaldi.files.wordpress.com/2018/03/tampilan11.png?w=316&h=165">

**Page Halaman Tambah Buku**

Interface ini merupakan halaman Tambah Buku ini untuk membuat Buku Pelajaran yang tar akan di upload oleh Guru atau Admin.

<img style="width: 50%" src="https://oksareinaldi.files.wordpress.com/2018/03/tambah-buku1.png?w=318&h=164">

**Page Halaman Tambah  Siswa/Siswi**

Interface ini merupakan halaman Tambah Siswa/Siswi ini buat Guru atau Admin yang mau menambah Siswa/Siswi yang mau ditambah.

<img style="width: 50%" src="https://oksareinaldi.files.wordpress.com/2018/03/tambah-siswa-siswi1.png?w=316&h=165">

**Page Halaman Tambah Guru**

Interface ini merupakan halaman Tambah Guru yang bisa dilakukan Oleh Admin saja.

<img style="width: 50%" src="https://oksareinaldi.files.wordpress.com/2018/03/tambah-guru1.png?w=316&h=165">

**Page Halaman Login Android**

Interface ini merupakan halaman Merupakan Halaman Utama Masuk ke Aplikasi tersebut hanya untuk Siswa/Siswi.

<img src="https://oksareinaldi.files.wordpress.com/2018/02/a01.png?w=370&h=" width="190">

**Page Halaman Utama Android**

Interface ini merupakan halaman ini adalah tampilan awal saat masuk aplikasi.

<img src="https://oksareinaldi.files.wordpress.com/2018/02/a05.png?w=209&h=426" width="190">

**Page Halaman Tampilan Buku Pelajaran**

Interface ini merupakan halaman ini Siswa/siswi bisa memilih buku mana yang mau dulu dibaca.

<img src="https://oksareinaldi.files.wordpress.com/2018/02/a06.png?w=208&h=426" width="190">

**Page Halaman Statistic**

Interface ini merupakan halaman ini Siswa/siswi bisa melihat nilai meraka dan bisa melihat daftar list rangking antar kelas.

<img src="https://oksareinaldi.files.wordpress.com/2018/02/a07.png?w=211&h=426" width="190">

**Page Halaman Latihan Ujina**

Interface ini merupakan halaman ini Siswa/siswi hanya latihan ujian yang akan di jalankan di ujian nanti.

<img src="https://oksareinaldi.files.wordpress.com/2018/02/a12.png?w=315&h=631" width="190">

**Page Halaman Ujian**

Interface ini merupakan halaman ini Siswa/siswi saat ujian yang akan di jalankan nanti.

<img src="https://oksareinaldi.files.wordpress.com/2018/02/a15.png?w=156&h=313" width="190">