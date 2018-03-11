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
- DBMS	: MySQL dan Firebase.
- Pemrograman	: Java, PHP, HTML.

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

<img src="https://oksareinaldi.files.wordpress.com/2018/03/picture11.png?w=640" align="center" width="500">