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

Abah

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

##### Tabel Buku.

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

##### Tabel Guru.

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

##### Tabel Jurusan.

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

##### Tabel Kategori.

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

##### Tabel Maple.

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

##### Tabel Siswa/Siswi.

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

##### Tabel User.

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

**3.1.1 DFD Level 0**

**3.1.2 DFD Level 1 Proses M**

**3.1.3 DFD Level 1 Proses M**

**3.2 Deskripsi Rinci Tabel**

**3.3 Matriks Rinci Modul**

**3.3.1 Modul**

**3.3.1.1 Fungsi Modul**

**3.3.1.2 Spesifikasi Layar utama**

**3.3.1.3 Spesifikasi Query **

**3.3.1.4 Spesifikasi Field Data Layar**

**3.3.1.5 Spesifikasi Proses/Algoritma**

**3.4 Matriks Kerunutan**