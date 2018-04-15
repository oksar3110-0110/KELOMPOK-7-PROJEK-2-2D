
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

##### Buku.

| Domain        | Keterangan  |
| ------------- | ----------- |
| id_buku       | Primary Key |
| id_kategori   | Forigen Key |
| judul_buku    | String      |
| nama_kategori | String      |
| nama_penerbit | String      |
| nama_penulis  | String      |
| file_buku     | String      |
| cover_buku    | String      |

##### Guru.

| Domain    | Keterangan  |
| --------- | ----------- |
| id_guru   | Primary Key |
| id_user   | Forigen Key |
| id_mapel  | Forigen Key |
| nama_guru | String      |
| nip       | Interger    |
| alamat    | String      |
| no_hp     | String      |
| foto      | String      |

##### Jurusan.

| Domain       | Keterangan  |
| ------------ | ----------- |
| id_jurusan   | Primary Key |
| nama_jurusan | String      |

##### Kategori.

| Domain        | Keterangan  |
| ------------- | ----------- |
| id_kategori   | Primary Key |
| nama_kategori | String      |

##### Mapel.

| Domain     | Keterangan  |
| ---------- | ----------- |
| id_mapel   | Primary Key |
| nama_mapel | nama_mapel  |

##### Siswa/Siswi.

| siswa siswi       |             |
| ----------------- | ----------- |
| Domain            | Keterangan  |
| id_siswa_siswi    | Primary Key |
| id_user           | Forigen Key |
| id_jurusan        | Forigen Key |
| nama_siswa_siswi  | String      |
| nisn              | Interger    |
| nama_ayah         | String      |
| nama_ibu          | String      |
| nama_wali         | String      |
| ttl               | String      |
| kelas             | String      |
| alamat            | String      |
| no_hp_siswa_siswi | String      |
| no_hp_ortu        | String      |
| foto              | String      |

##### User.

| Domain   | Keterangan  |
| -------- | ----------- |
| id_user  | Primaru Key |
| username | String      |
| password | String      |
| email    | String      |
| level    | String      |

**2.2.2 Conceptual Data Model**

**2.2.3 Physical Data Model**

**2.2.4 Daftar Tabel Aplikasi**

**2.3 Deskripsi Model**

| No   | Nama Modul       | Keterangan                                                   |
| ---- | ---------------- | ------------------------------------------------------------ |
| 1    | Buku             | Dapat melihat buku, Dapat mengelolah buku                    |
| 2    | Ujian            | Dapat melaksanakan ujian dengan waktu yang sudah sediakan    |
| 3    | Latihan ujian    | Dapat melaksanakan latihan ujian dengan waktu yang sudah di sediakan |
| 4    | Profil           | Dapat mengelola atau merubah data profil                     |
| 5    | Statistik        | Dapat melihat nilai siswa/siswi                              |
| 6    | Otentifikasi     | Dapat  melakukan login siswa/I,  admin dan guru              |
| 7    | Register         | Dapat melakukan pendataran siswa/I dan guru                  |
| 8    | Lupa password    | Dapat melakukan kehilangan password siswa/I dan guru         |
| 9    | Guru             | Dapat mengelola data guru                                    |
| 10   | Siswa atau siswi | Dapat mengelola data siswa/i                                 |

## **BAB 3 Perancangan Rinci**

**3.1 Diagram Konteks**

![enter image description here](/gambarSDD/diagramkonteks.png)

**3.1.1 DFD Level 0**

![enter image description here](/gambarSDD/0.png)

**3.1.2 DFD Level 1 Proses Data Guru**

![enter image description here](/gambarSDD/1.png)

**3.1.3 DFD Level 2 Proses Data Siswa**

![enter image description here](/gambarSDD/2.png)

**3.1.4 DFD Level 3 Proses Data Ujian**

![enter image description here](/gambarSDD/3.png)

**3.1.5 DFD Level 4 Proses Data Latihan**

![enter image description here](/gambarSDD/4.png)

**3.1.6 DFD Level 5 Proses Data Buku**

![enter image description here](/gambarSDD/5.png)

**3.1.7 DFD Level 6 Proses Data Statistik**

![enter image description here](/gambarSDD/6.png)

**3.2 Deskripsi Rinci Tabel**

**3.2.1 Tabel Buku**

| Identifikasi / Nama  : | tabel_buku                           |               |            |         |                     |
| ---------------------- | ------------------------------------ | ------------- | ---------- | ------- | ------------------- |
| Deskripsi Isi :        | Sebagai tempat penyimpanan data buku |               |            |         |                     |
| Jenis :                | Tabel                                |               |            |         |                     |
| Volume :               |                                      |               |            |         |                     |
| Laju :                 |                                      |               |            |         |                     |
| Primary Key :          | id_buku                              |               |            |         |                     |
|                        |                                      |               |            |         |                     |
| Id Field               | Deskripsi                            | Tipe & length | Boleh Null | Default | Keterangan          |
| id_buku                | sebagai auto increment buku          | int (11)      | no         | none    | primary key         |
| id_kategori            | sebagai forgen key dari t_kategori   | int (11)      | no         | none    | refer ke t_kategori |
| judul_buku             | sebagai judul buku                   | varchar (45)  | no         | none    |                     |
| nama_kategori          | sebagai menepatkan nama kategori     | varchar (45)  | no         | none    |                     |
| nama_penerbit          | sebagai menepatkan nama penerbit     | varchar (45)  | no         | none    |                     |
| nama_penulis           | sebagai menepatkan nama penulis      | varchar (45)  | no         | none    |                     |
| file_buku              | sebagai menepatkan file buku         | varchar (50)  | no         | none    |                     |
| cover_buku             | sebagai menepatkan cover buku        | varchar (50)  | no         | none    |                     |

**3.2.2 Tabel Guru**

| Identifikasi / Nama  : | tabel_guru                           |               |            |         |                  |
| ---------------------- | ------------------------------------ | ------------- | ---------- | ------- | ---------------- |
| Deskripsi Isi :        | Sebagai tempat penyimpanan data guru |               |            |         |                  |
| Jenis :                | Tabel                                |               |            |         |                  |
| Volume :               |                                      |               |            |         |                  |
| Laju :                 |                                      |               |            |         |                  |
| Primary Key :          | id_guru                              |               |            |         |                  |
|                        |                                      |               |            |         |                  |
| Id Field               | Deskripsi                            | Tipe & length | Boleh Null | Default | Keterangan       |
| id_guru                | sebagai auto increment guru          | int (11)      | no         | none    | primary key      |
| id_user                | sebagai forgen key dari t_kategori   | int (11)      | no         | none    | refer ke t_user  |
| id_mapel               | sebagai forgen key dari t_mapel      | int (11)      | no         | none    | refer ke t_mapel |
| nama_guru              | sebagai menepatkan nama guru         | varchar (45)  | no         | none    |                  |
| nip                    | sebagai menepatkan nip guru          | varchar (45)  | no         | none    |                  |
| alamat                 | sebagai menepatkan alamat guru       | varchar (150) | no         | none    |                  |
| no_hp                  | sebagai menepatkan no_hp guru        | varchar (45)  | no         | none    |                  |
| foto                   | sebagai menepatkan foto guru         | varchar (50)  | yes        | null    |                  |

**3.2.3 Tabel Jurusan**

| Identifikasi / Nama  : | tabel_jurusan                           |               |            |         |             |
| ---------------------- | --------------------------------------- | ------------- | ---------- | ------- | ----------- |
| Deskripsi Isi :        | Sebagai tempat penyimpanan data jurusan |               |            |         |             |
| Jenis :                | Tabel                                   |               |            |         |             |
| Volume :               |                                         |               |            |         |             |
| Laju :                 |                                         |               |            |         |             |
| Primary Key :          | id_jurusan                              |               |            |         |             |
|                        |                                         |               |            |         |             |
| Id Field               | Deskripsi                               | Tipe & length | Boleh Null | Default | Keterangan  |
| id_jurusan             | sebagai auto increment jurusan          | int (11)      | no         | none    | primary key |
| nama_jurusan           | sebagai menepatkan nama jurusan         | varchar (25)  | no         | none    |             |

**3.2.4 Tabel Kategori**

| Identifikasi / Nama  : | tabel_kategori                           |               |            |         |             |
| ---------------------- | ---------------------------------------- | ------------- | ---------- | ------- | ----------- |
| Deskripsi Isi :        | Sebagai tempat penyimpanan data kategori |               |            |         |             |
| Jenis :                | Tabel                                    |               |            |         |             |
| Volume :               |                                          |               |            |         |             |
| Laju :                 |                                          |               |            |         |             |
| Primary Key :          | id_kategori                              |               |            |         |             |
|                        |                                          |               |            |         |             |
| Id Field               | Deskripsi                                | Tipe & length | Boleh Null | Default | Keterangan  |
| id_kategori            | sebagai auto increment kategori          | int (11)      | no         | none    | primary key |
| nama_kategori          | sebagai menepatkan nama kategori         | varchar (25)  | no         | none    |             |

**3.2.5 Tabel Mapel**

| Identifikasi / Nama  : | tabel_mapel                                    |               |            |         |             |
| ---------------------- | ---------------------------------------------- | ------------- | ---------- | ------- | ----------- |
| Deskripsi Isi :        | Sebagai tempat penyimpanan data mata pelajaran |               |            |         |             |
| Jenis :                | Tabel                                          |               |            |         |             |
| Volume :               |                                                |               |            |         |             |
| Laju :                 |                                                |               |            |         |             |
| Primary Key :          | id_mapel                                       |               |            |         |             |
|                        |                                                |               |            |         |             |
| Id Field               | Deskripsi                                      | Tipe & length | Boleh Null | Default | Keterangan  |
| id_mapel               | sebagai auto increment mata pelajaran          | int (11)      | no         | none    | primary key |
| nama_mapel             | sebagai menepatkan nama mata pelajaran         | varchar (25)  | no         | none    |             |

**3.2.6 Tabel Siswa/Siswi**

| Identifikasi / Nama  : | tabel_siswa_siswi                           |               |            |         |                    |
| ---------------------- | ------------------------------------------- | ------------- | ---------- | ------- | ------------------ |
| Deskripsi Isi :        | Sebagai tempat penyimpanan data siswa siswi |               |            |         |                    |
| Jenis :                | Tabel                                       |               |            |         |                    |
| Volume :               |                                             |               |            |         |                    |
| Laju :                 |                                             |               |            |         |                    |
| Primary Key :          | id_siswa_siswi                              |               |            |         |                    |
|                        |                                             |               |            |         |                    |
| Id Field               | Deskripsi                                   | Tipe & length | Boleh Null | Default | Keterangan         |
| id_siswa_siswi         | sebagai auto increment siswa siswi          | int (11)      | no         | none    | primary key        |
| id_user                | sebagai forgen key dari user                | int (11)      | no         | none    | refer ke t_user    |
| id_jurusan             | sebagai forgen key dari jurusan             | int (11)      | no         | none    | refer ke t_jurusan |
| nama_siswa_siswi       | sebagai menepatkan nama siswa siswi         | varchar (45)  | no         | none    |                    |
| nisn                   | sebagai menepatkan id nisn                  | varchar (45)  | no         | none    |                    |
| nama_ayah              | sebagai menepatkan nama ayah                | varchar (45)  | no         | none    |                    |
| nama_ibu               | sebagai menepatkan nama ibu                 | varchar (45)  | no         | none    |                    |
| nama_wali              | sebagai menepatkan nama wali                | varchar (45)  | yes        | null    |                    |
| ttl                    | sebagai menepatkan tempat tanggal lahir     | varchar (45)  | no         | none    |                    |
| kelas                  | sebagai menepatkan kelas                    | varchar (45)  | no         | none    |                    |
| alamat                 | sebagai menepatkan alamat                   | varchar (50)  | no         | none    |                    |
| no_hp_s                | sebagai menepatkan nomer hp siswi siswi     | varchar (45)  | no         | none    |                    |
| no_hp_ortu             | sebagai menepatkan nomer hp orangtua        | varchar (45)  | no         | none    |                    |
| foto                   | sebagai menepatkan file foto                | varchar (50)  | yes        | null    |                    |

**3.2.7 Tabel User**

| Identifikasi / Nama  : | tabel_user                           |               |            |         |             |
| ---------------------- | ------------------------------------ | ------------- | ---------- | ------- | ----------- |
| Deskripsi Isi :        | Sebagai tempat penyimpanan data user |               |            |         |             |
| Jenis :                | Tabel                                |               |            |         |             |
| Volume :               |                                      |               |            |         |             |
| Laju :                 |                                      |               |            |         |             |
| Primary Key :          | id_user                              |               |            |         |             |
|                        |                                      |               |            |         |             |
| Id Field               | Deskripsi                            | Tipe & length | Boleh Null | Default | Keterangan  |
| id_user                | sebagai auto increment user          |               |            |         | primary key |
| username               | sebagai menepatkan username          |               |            |         |             |
| password               | sebagai menepatkan password          |               |            |         |             |
| email                  | sebagai menepatkan email             |               |            |         |             |
| level                  | sebagai menepatkan level             |               |            |         |             |



**3.3 Matriks Rinci Modul**

**3.3.1 Modul**

**3.3.1.1 Fungsi Modul**

| No   | Fungsi                             | Jenis                       | Tabel Yang terkait | Kategori    |
| ---- | ---------------------------------- | --------------------------- | ------------------ | ----------- |
| 1    | Input Data Guru/Siswa/i            | Import File atau Form Modal | Guru/Siswa/i       | WEB         |
| 2    | Update Data Guru/Siswa/i           | Import File atau Form Modal | Guru/Siswa/i       | WEB         |
| 3    | Delete Data Guru/Siswa/i           | Import File atau Form Modal | Guru/Siswa/i       | WEB         |
| 4    | Menampilkan Data Data Guru/Siswa/i | Tabel                       | Guru/Siswa/i       | WEB/Android |
| 5    | Ujian Siswa/Siswi                  | Tabel                       | Siswa/Siswi        | Android     |
| 6    | Latihan Ujian Siswa/Siswi          | Tabel                       | Siswa/Siswi        | Android     |
| 7    | Membaca Buku Siswa/Siswi           | Import File                 | Siswa/Siswi        | Android     |

**3.3.1.2 Spesifikasi Layar utama**

**3.3.1.3 Spesifikasi Query **

**3.3.1.4 Spesifikasi Field Data Layar**

**3.3.1.5 Spesifikasi Proses/Algoritma**

| No   | Tampilan                          | Operasi                      | Fungsi                                                       |
| ---- | --------------------------------- | ---------------------------- | ------------------------------------------------------------ |
| 1    | Tampilan Login                    | Input Email                  | Berfungsi sebagai ID akun masuk ke aplikasi.                 |
| 2    |                                   | Input Password               | Berfungsi sebagai security ID akun aplikasi anda.            |
| 3    |                                   | Buttom Login                 | Berfungsi sebagai proses masuk aplikasi.                     |
| 4    |                                   | Buttom Forget                | Berfungsi sebagai ketika user tidak tahu passwordnya atau lupa password. |
| 5    | Tampilan Lupa Password            | Input Username               | Berfungsi sebagai ID username security yang ada di databases. |
| 6    |                                   | Input Nomer HP               | Berfungsi sebagai ID nomer security yang ada di databases.   |
| 7    |                                   | Input Email                  | Berfungsi sebagai ID email security yang ada di databases.   |
| 8    |                                   | Buttom Canlce                | Berfungsi sebagai tidak jadi untuk lupa password.            |
| 9    |                                   | Buttom Send                  | Berfungsi sebagai mengirim data yang telah di input oleh user, jika benar  buttom ini akan mengarah ke rubah password jika tidak buttom ini akan kembali  ke tampilan lupa password. |
| 10   | Tampilan Rubah Password Dll       | Input Password               | Berfungsi sebagai perubahan password yang tadi lupa jadi biki lagin  dengan akun yang sama, yang telah di inputkan di Tampilan Lupa Password. |
| 11   |                                   | Input Nomer HP               | Berfungsi sebagai perubahan nomer hp biasanya nomernya udah muncul, jika  mau dirubah nomernya silahkan ganti nomernya jika tidak dirubah maka jangan  dihapus atau dirubah. |
| 12   |                                   | Input Email                  | Berfungsi sebagai perubahan email atau jika mau dirubah silahkan dirubah  jika tidak dirubah jangan dihapus atau dirubah emailnya. |
| 13   |                                   | Buttom Cancle                | Berfungsi sebagai buttom ini akan mengarahkan ke halaman Tampilan Login  atau buttom ini membatalkan perubahan password baru. |
| 14   |                                   | Buttom Send                  | Berfungsi sebagai perubahan databases, buttom ini yang akan mengarahkan  ke databases kalo ada Password, NoHp dan Email yang ada di rubah |
| 15   | Tampilan Register                 | Input Email                  | Berfungsi sebagai ID login untuk ID masuk ke aplikasi.       |
| 16   |                                   | Input Password               | Berfungsi sebagai Password security ID akun aplikasi anda.   |
| 17   |                                   | Buttom Cancle                | Berfungsi sebagai tidak jadi untuk register buttom ini akan mengarahkan  ke Tampilan Login. |
| 18   |                                   | Buttom cread                 | Berfungsi sebagai membuat akun atau ID baru di aplikasi.     |
| 19   |                                   | Icon GooglePlus              | Berfungsi sebagai membuat akun atau ID baru di aplikasi tapi menggunakan  akun dari Google. |
| 20   |                                   | Icon Facebook                | Berfungsi sebagai membuat akun atau ID baru di aplikasi tapi menggunakan  akun dari facebook. |
| 21   | Tampilan Awal Aplikasi            | Icon 3 Garis Horizon         | Berfungsi sebagai buttom fitur tambahan yang ada di Tampilan Awal  Aplikasi fitur tamabahanya itu editting profile user dll. |
| 22   |                                   | Buttom Icon Buku             | Berfungsi sebagai buttom yang akan mengarahkan ke bacaan buku yang ada di  aplikasi tersebut. |
| 23   |                                   | Buttom Icon latihan          | Berfungsi sebagai buttom yang akan mengarahkan ke latihan ujian yang  sudah di pelajari dan akan muncul di soal Ujian. |
| 24   |                                   | Buttom Icon Ujian            | Berfungsi sebagai buttom yang akan meagarahkan ke Simulasi Ujian asli  yang akan muncul di Ujian Online. |
| 25   |                                   | Buttom Icon Static           | Berfungsi sebagai buttom yang akan mengarahkan ke static grafic latihan  ujian dan rangking yang sudah di kerjakan. |
| 26   |                                   | Buttom Icon Chatting         | Berfungsi sebagai chatting user, fitur ini bisa digunakan untuk chatting  sesama userlain yang dapat di diskusian bersama userlain dan bisa membuat  group user. |
| 27   |                                   | Buttom Icon Setting          | berfungsi sebagai mengatur pengaturan yang ada di aplikasi tersebut. |
| 28   |                                   | Buttom Icon About            | Berfungsi sebagai yang akan mengarahkan informasi aplikasi.  |
| 29   | Tampilan Buku                     | Buttom icon buku             | Berfungsi sebagai buku pelajaran yang bisa dibaca lewat hp selain buku  normal biasanya. |
| 30   | Tampilan Static                   |                              | Berfungsi sebagai melihat grafic static ujian, latihan,rangking dll. |
| 31   | Tampilan About                    |                              | Berfungsi sebagai menampilkan informasi aplikasi seperi aplikasi servi  berapa, dibuat siapa dll. |
| 32   | Tampilan Setting                  |                              | Berfungsi sebagai menampilkan settingan beberapa penganturan yang mau  akan dirubah oleh user. |
| 33   | Tampilan Latihan Ujian            | Timedown                     | Berfungsi sebagai menampilakan waktu yang akan diujian oleh latihan ujian  aplikasi. |
| 34   |                                   | Buttom Icon Play             | Berfungsi sebagai akan dimulainya latihan ujian.             |
| 35   |                                   | Buttom icon pause            | Berfungsi sebagai mulai laginya ujian yang sudah pause sebelunya pada  saata latihan ujian sedang berlangsung. |
| 36   | Tampilan saat mulai latihan ujian | Timedown                     | Berfungsu sebagai waktu mundur yang sedang berjalan.         |
| 37   |                                   | Buttom icon pause            | Berfungsi sebagai di pausenya latihan ujian untuk memberhentikan  sementara time down latihan ujian dan akan mengarahkan ke tampilan Mulai  latihan ujian. |
| 38   |                                   | Buttom icon panah kanan/kiri | Berfungsi sebagai menggati soal yand ada di latihan ujiantersebut. |
| 39   |                                   | Buttom icon Pilihan          | Berfungsi sebagai pilihan jawan user.                        |
| 40   | Tampilan selesai latihan ujian    | Buttom icon ya               | Berfungsi sebagai jika jawaban sudah fik buttom ini akan mengarahkan ke  Tampilan Awal Aplikasi. |
| 41   |                                   | Buttom icon tidak            | Berfungsi sebagai jika jawaban salah maka buttom ini akan mengarahkan ke  tampilan mulai ujian atau kembali mengerjakan latihan ujian. |
| 42   | Tampilan ujian                    | Timedown                     | Berfungsi sebagai jangka waktu pengerjaan ujian latihan.     |
| 43   |                                   | Buttom Icon Play             | berfungsi sebagai mulainya ujian.                            |
| 44   | Tampilan saat mulai Ujian         | Timedown                     | Berfungsu sebagai waktu mundur yang sedang berjalan.         |
| 45   |                                   | Buttom icon panah kanan/kiri | Berfungsi sebagai menggati soal yand ada di latihan ujiantersebut. |
| 46   |                                   | Buttom icon Pilihan          | Berfungsi sebagai pilihan jawan user.                        |
| 47   | Tampilan selesai ujian            | Buttom icon ya               | Berfungsi sebagai jika jawaban sudah fik buttom ini akan mengarahkan ke  Tampilan Awal Aplikasi. |
| 48   |                                   | Buttom icon tidak            | Berfungsi sebagai jika jawaban salah maka buttom ini akan mengarahkan ke  tampilan mulai ujian atau kembali mengerjakan latihan ujian. |
| 49   | Tampilan Pilih Latihan Ujian      | Buttom icon Pilihan Ujian    | Berfungsi sebagai memilih latihan soal ujian yang akan dipilih. |
| 50   | Tampilan Pilih Ujian              | Buttom icon Pilihan Ujian    | Berfungsi sebagai memilih soal ujian yang akan dipilih.      |
| 51   | Tampilan Lihat Buku               |                              | Berfungsi sebagai menampilkan buku pelajaran.                |
| 52   | Tampilan Tambah Chatting Private  | Buttom chatting              | Interaksi user dan user yang sedang dijalan.                 |
| 53   |                                   | Buttom Tambah Chatting       | Berfungsi sebagai menabha kontak baru dari private chatting. |
| 54   |                                   | Buttom kurang chatting       | Berfungsi sebagai mengurangi beberapa kontak  Chatting Private. |
| 55   | Tampilan Tambah Chatting group    | Buttom chatting Group        | Interaksi user dan user yang sedang dijalan.                 |
| 56   |                                   | Buttom Tambah Chatting Group | Berfungsi sebagai menabha kontak baru dari group chatting.   |
| 57   |                                   | Buttom kurang chatting       | Berfungsi sebagai mengurangi beberapa kontak group chatting. |
| 58   | Tampilan Profile                  | Buttom Back                  | Berfungsi sebagai kembali ke Tampilan Awal Aplikasi.         |
| 59   |                                   |                              | Menampikan informasi user.                                   |
| 60   |                                   | Buttom Setting               | Berfungsi sebagai mengedit Profile user.                     |
| 61   | Tampilan EditUser                 | Buttom Back                  | Berfungsi kembali ke Tampilan Profile.                       |
| 62   |                                   | Input Username               | Berfungsi sebagai merubah username.ke databases.             |
| 63   |                                   | Input Password               | Berfungsi sebagai merubah password ke databases.             |
| 64   |                                   | Input Email                  | Berfungsi sebagai merubah email ke databases.                |
| 65   |                                   | Input Nomer HP               | Berfungsi sebagai merubah nomer hp ke databases.             |
| 66   |                                   | Input Alamat                 | Berfungsi sebagai merubah alamat ke databases.               |
| 67   |                                   | Input Ayah                   | Berfungsi sebagai merubah nama orang tua ayah ke databases.  |
| 68   |                                   | Input Ibu                    | Berfungsi sebagai merubah nama orang tua ibu ke databases.   |
| 69   |                                   | Input Nomer HP Orangtua      | Berfungsi sebagai merubah nomer orang tua ayah/ibu ke databases. |

**3.4 Matriks Kerunutan**

