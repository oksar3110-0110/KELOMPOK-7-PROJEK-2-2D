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

 Pada bagian ini memberikan deskripsi dan gambaran mengenai apapun yang terdapat pada dokumen SDD. Juga tujuan dari pembuatan dari dokumen ini di gambarkan dan di urutkan juga didefinisikan.
 
 **1.1	Lingkup**

   "Aplikasi Latihan Ujian Berbasis Mobile Apps" merupakan sebuah aplikasi mobile yang dibuat bekerja sama dengan mitra yaitu SMK RISTEK MULTIMEDIA Indramayu. Pada aplikasi ini disediakan materi, latihan soal dan soal - soal yang diharapkan dapat meningkatkan mutu dari siswa - siswa dalam kompetensinya.

   Batasan dari aplikasi ini ialah pada soal - soal dan materi, hanya berkaitan dengan bidang multimedia dan beberapa materi pelajaran wajib. Pada aplikasi inipun disediakan juga fitur live chat antar sesama siswa. Juga disediakan fitur perangkingan berbasis grafik.
   
  **1.2	Tujuan**

   Tujuan dari pembuatan dokumen ini adalah untuk memberikan detail dari System Requirement dari "Aplikasi Latihan Ujian Nasional Berbasis Mobile Apps". Pada dokumen ini mengilustrasikan tujuan dan pernyataan lengkap dari pembuatan sistem. Dokumen ini juga menjelaskan spesifikasi system, interface dan hubungan dengan aplikasi lainnya.
   
  **1.3	Definisi, Akronim, Singkatan**
- Mobile Apps : Aplikasi perangkat bergerak meliputi IOS, Android.
- Firebase	 : Database realtime dari google yang tidak berbasis DBMS.
- Live Chat	 : Merupakan aplikasi Chatting yang up to date terhadap perubahan dalam waktu maksimal 5 detik.

## **2.Deskripsi Umum**

**2.1 Prespektif Produk**

Produk dari SDD ini sebuah aplikasi yang berbasis Website dan Mobile Apps, yang di jalankan dan berfungsi sebagai APLIKASI LATIHAN SOAL UJIAN BERBASIS MOBILE APPS, seperti yang telah dijelaskan pada pendahuluan. Produk ini akan bisa di akses dari aplikasi yang sudah di buat di Smartphone dan juga bisa dijalankan di browser WEB sebagai Admin, dan Aplikasi ini bisa berjalan di Smartphone android.

**2.2 Manfaat Produk**

Manfaat dalam menggunkan sistem atau aplikasi 'APLIKASI LATIHAN SOAL UJIAN BERBASIS MOBILE APPS' ini adalah:

- Siswa/siswi bisa dapat belajar dengan mudah memalui Smartphone.
- Siswa/siswi bisa ujian/latihan ujian dengan budah dan tidak rumit.
- Siswa/siswi bisa mendapatkan module atau materi dari guru dengan mudah.
- Siswa/siswi bisa mendapatkan buku pelajaran dengan mudah dengan memalui smartphone.
- Siswa/siswi bisa belajar ujian bersama dengan siswa/siswi lain.
- Siswa/siswi bisa memantau nilai dari smartphone.
- siswa/siswi bisa bersaing dengan siswa/siswi lain.
- Siswa/siswi bisa dengan buda membuka aplikasi ini dimana saja.
- Guru bisa dengan mudah memberi module/materi pelajaran ke siswa/siswi.
- Guru bisa dengan mudah membuat soal ujian pelajaran.
- Guru bisa dengan mudah melihat nilai siswa/siswi di manasaja.
- Guru bisa dengan mudah bisa mengupload buku pelajaran.
- Guru bisa dengan mudah bisa melakukan kegiatan dimana saja. 

**2.3 Karakteristik User dan Stakeholder**

User yang terlibat dalam APLIKASI LATIHAN SOAL UJIAN BERBASIS MOBILE + 
APPS ini sebagai berikut :

- Siswa/Siswi.
- Guru.
- Admin.

Stackholder yang terkain dengan PLIKASI LATIHAN SOAL UJIAN BERBASIS 
MOBILE + APPS ini sebagai berikut :
- Sebagai pengguna aplikasi.
- Sebagai pengelolah aplikasi dan memberi materi/module.
- Sebagai pengelolah aplikasi dan pembaruan aplikasi.

**2.4 Batasan-batasan**

- Aplikasi ini hanya sebagai Simulasi Ujian saja.
- Membangun aplikasi latihan ujian berbasis mobile apps dengan fitur 
  live chat.
- Soal - soal yang disediakan merupakan soal latihan untuk SMK jurusan
  Multimedia.
- Hanya tersedia latihan soal, kunci jawaban, sekilas materi dan live 
  chat.

**2.5 Asumsi**

- Siswa/siswi atau Guru dalam mengunuakan APLIKASI LATIHAN SOAL UJIAN 
  BERBASIS MOBILE APPS ini bisa paham, dan dapat mengoprasikan 
  simulasi ujian atau mengelolah website/ aplikasi tersebut.
- Setiap Siswa/siswi atau guru mempunyai ID login dan password sebagai 
  Identitas dari aplikasi/website tersebut.
- Guru dianjurkan untuk koneksi internet untuk mengupload 
  materi/module pelajaran yang mau dimasukan.
- Siswa/Siswi dianjurkan untuk koneksi internet untuk mendownload 
  meteri/module yang di upload oleh guru.

## **3.Software Design**

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

**3.1.2	Spesifikasi yang diharapkan pada Login User**

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


