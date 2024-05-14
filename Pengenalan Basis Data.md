![[bahagia.jpg]]

# DEFINISI BASIS 
BASIS dapat diartikan  sebagai gudang, atau  tempat bersarang atau berkumpul nya para data
# DEFINISI DATA 
sekumpulan data yang disimpan pada wadah atau tempat tertentu dengan aturan dan perintah 
tertentu.
# KESIMPULAN BASIS DATA
basis adalah sekumpulan data adalah informasi jadi Basis data adalah  sekumpulan data data yang mempunyai hubungan secara logika yang di sertai dengan deskripsi data data. sifat basis data, yaituu dapat di bagi (shereable), didesain, dan diorganisasi untuk memenuhi kebutuhan informasi dari organisasi pemiliknya.

Data data yang  disimpan dalam sebuah basis data bersifat dapat dibagi karena data data yang ada dimungkinkan diakses tidak hanya oleh pemilik data, melaikan juga  pengguna atau pihak lain
yang di beri hak akses.

# PERANAN BASIS DATA
peranan basis data memiliki peranan penting dalam menyimpan, mengelola, dan mengakses informasi secara efisien. fungsi utamanya melibatkan penyimpanan data, pembaruan pencarian, dan penghapusan informasi untuk mendukung aplikasi dan proses bisnis.

# Contoh Struktur Basisi Data
| New Column | New Column | New Column       | New Column |
| ---------- | ---------- | ---------------- | ---------- |
| NIP        | NAMA       | ALAMAT           | GAJI       |
| 08199      | Raihan     | jln. cendrawasia | 5.000.000  |
| 72190      | Kausar     | jln. kakaktua    | 2.500.000  |
| 81297      | Wais       | jln. rajawali    | 4.000.000  |


pada tabel mengacu pada struktur organisasi data dalam bentuk tabel. Dalam konteks ini:

- Database: Kumpulan data yang terorganisir dengan baik, biasanya disimpan dalam tabel atau struktur data lainnya.

- Tabel: Struktur data dalam database yang terdiri dari baris dan kolom. Setiap kolom mewakili field, dan setiap baris mewakili record. Tabel digunakan untuk menyimpan informasi terkait dalam bentuk yang terstruktur.

# Dalam konteks database:

Field (Kolom): Bagian terkecil dari sebuah record yang menyimpan satu jenis informasi, seperti nama atau nomor telepon.

Record (Baris): Kumpulan field yang membentuk satu kesatuan informasi, misalnya informasi lengkap seorang karyawan.

Karakter: Unit dasar data yang terdiri dari satu huruf atau simbol.

Data: Informasi yang direpresentasikan oleh kumpulan karakter atau nilai dalam field, seperti nama atau angka

Struktur hierarki dalam basis data pada tabel mengacu pada cara data diorganisir secara bertingkat atau berjenjang. Dalam konteks ini:

Hierarki: Representasi tingkatan atau tingkat kepentingan antar data. Informasi diatur dalam tingkatan-tingkatan yang membentuk struktur berjenjang.

Basis Data pada Tabel: Merujuk pada cara data disusun dalam tabel di dalam sistem basis data.

Jadi, struktur hierarki dalam basis data pada tabel menunjukkan hubungan hierarkis antar data di dalam tabel, di mana beberapa data memiliki ketergantungan atau tingkatan yang lebih tinggi dibandingkan dengan yang lain.

# Menggunakan xampp
1. Buka Xampp
2. klik start di mysql
    ![[r.p.png]]
3. klik shell

    ![[rpl.png]]

  4. ketik mysql -u root -p

    ![[rehan.png]]


 5. baru enter lalu nantinya akan muncul seperti ini klik lagi enter

    ![[frhan.png]]


# Referensi video youtube
<[https://youtu.be/rT93qlWBhoQ?si=icUNByWK57GIuo0v](https://youtu.be/rT93qlWBhoQ?si=icUNByWK57GIuo0v "https://youtu.be/rT93qlWBhoQ?si=icUNByWK57GIuo0v")>

# Penggunaan awal mysql

## **Query mysql -u root -p**
Query dalam konteks basis data mengacu pada perintah atau instruksi yang digunakan untuk mengambil, menyimpan, memperbarui, atau menghapus data dari sebuah basis data. 

Perintah mysql -u root -p sendiri bukanlah sebuah query MySQL, melainkan cara untuk mengakses server MySQL menggunakan klien baris perintah (CLI) dan login sebagai pengguna "root" dengan meminta kata sandi.
## Hasil
![contoh](contoh.jpg)

# Analisis
Perintah mysql -u root -p adalah cara untuk mengakses server MySQL menggunakan klien baris perintah (CLI) dan login sebagai pengguna "root" dengan meminta kata sandi. Ini memiliki beberapa implikasi dan aspek yang perlu dianalisis:
## Mysql
Keamanan: Menggunakan akun "root" memiliki kekuatan penuh atas server MySQL. Ini berarti Anda memiliki kemampuan untuk melakukan hampir semua tugas administratif, termasuk membuat, menghapus, dan memodifikasi basis data dan pengguna. Namun, dengan kekuatan ini juga datang tanggung jawab besar untuk memastikan keamanan server MySQL Anda. Penggunaan akun "root" harus dibatasi hanya untuk tugas-tugas yang membutuhkan hak akses tertinggi.

##  -u root
Otentikasi Pengguna: Melalui penggunaan opsi -u root, perintah ini secara eksplisit menentukan pengguna yang akan digunakan untuk otentikasi. Ini memungkinkan Anda untuk menggunakan pengguna tertentu saat terhubung ke server MySQL

## -p
Ketergantungan pada Kata Sandi: Argumen -p menandakan bahwa perintah ini akan meminta Anda untuk memasukkan kata sandi setelah dijalankan. Hal ini meningkatkan keamanan karena tidak menyimpan kata sandi di dalam perintah itu sendiri, tetapi juga berarti Anda harus memasukkan kata sandi setiap kali Anda ingin terhubung ke server

# Kesimpulan

- mysql: Ini adalah perintah untuk memulai klien MySQL Command Line Interface (CLI), yang memungkinkan Anda berinteraksi dengan server MySQL dari baris perintah

- -u root: Argumen ini menentukan pengguna yang ingin Anda gunakan untuk terhubung ke server. Di sini, "root" adalah nama pengguna MySQL yang akan digunakan. Dalam banyak instalasi MySQL, pengguna "root" memiliki hak akses penuh ke server dan basis data.

- -p: Argumen ini memberi tahu klien MySQL bahwa Anda ingin memasukkan kata sandi setelah menjalankan perintah ini untuk otentikasi. Setelah Anda mengetikkan perintah dan menekan Enter, sistem akan meminta Anda untuk memasukkan kata sandi.

Jadi, secara keseluruhan, perintah mysql -u root -p digunakan untuk memulai klien MySQL CLI, terhubung ke server MySQL sebagai pengguna "root", dan meminta Anda untuk memasukkan kata sandi untuk otentikasi. Setelah otentikasi berhasil, Anda dapat mulai menjalankan perintah SQL untuk mengelola basis data dan tabel.

# Query Database
## ho 
-  Di sini, nama_database adalah nama yang Anda inginkan untuk basis data baru yang akan Anda buat. Misalnya, jika Anda ingin membuat basis data dengan nama "tokobuku", Anda akan menulis:

## analisis
- Di sini, nama_database adalah nama yang Anda inginkan untuk basis data baru yang akan Anda buat. Misalnya, jika Anda ingin membuat basis data dengan nama "tokobuku", Anda akan menulis: CREATE DATABASE;

# Kesimpulan
kesimpulan dari proses membuat database berserta format di MySQL adalah bahwa ini adalah langkah penting dalam mempersiapkan lingkungan pengembangan data yang sesuai dan merupakan fondasi untuk pengembangan aplikasi yang sukses.

## Hasil
![[hcd.png]]



# SHOW DATABASES; 
- Untuk menampilkan daftar basis data yang ada di server MySQL beserta informasi tambahan seperti pemilik basis data, karakter set, dan kolasi, Anda dapat menggunakan perintah SHOW DATABASES;. Ini akan menampilkan daftar nama basis data yang tersedia di server MySQL.
# DROP DATABASE
- Untuk menghapus sebuah basis data (database) di MySQL, Anda dapat menggunakan perintah SQL DROP DATABASE. Namun, perlu diingat bahwa penghapusan sebuah basis data akan menghapus semua tabel, indeks, dan data yang terkait dengannya, sehingga pastikan untuk melakukan tindakan ini dengan hati-hati dan hanya jika benar-benar diperlukan.
# USE DATABASE
- Untuk menggunakan sebuah basis data (database) di MySQL, Anda perlu terlebih dahulu memilih basis data tersebut menggunakan perintah USE. Setelah itu, semua operasi query yang Anda lakukan akan berlaku pada basis data yang telah Anda pilih.

# analisis
## Buat database
- Di sini, nama_database adalah nama yang Anda inginkan untuk basis data baru yang akan Anda buat. Misalnya, jika Anda ingin membuat basis data dengan nama "tokobuku", Anda akan menulis: CREATE DATABASE;
## Tampilkan databases
- Perintah ini akan menghasilkan output yang berisi daftar semua basis data yang ada di server MySQL. Untuk menampilkan informasi lebih lanjut tentang sebuah basis data tertentu, Anda dapat menggunakan perintah SHOW  DATABASES nama_database;. Ini akan menampilkan pernyataan SQL yang digunakan untuk membuat basis data tersebut, termasuk karakter set dan kolasi yang digunakan
## Hapus database
- Di sini, x1_ adalah nama basis data yang ingin Anda hapus. Misalnya, jika Anda ingin menghapus basis data dengan nama "tokobuku", Anda akan menulis: DROP DATABASE;
## Gunakan databases
- Di sini, nama_database adalah nama basis data yang ingin Anda gunakan. Misalnya, jika Anda ingin menggunakan basis data dengan nama "tokobuku", Anda akan menulis: USE DATABASE;
# Kesimpulan
## Buat database
kesimpulan dari proses membuat database berserta format di MySQL adalah bahwa ini adalah langkah penting dalam mempersiapkan lingkungan pengembangan data yang sesuai dan merupakan fondasi untuk pengembangan aplikasi yang sukses.
## Tampilkan databases
perintah SHOW DATABASES; adalah alat yang penting dalam administrasi dan pengelolaan basis data di MySQL karena memberikan daftar semua basis data yang tersedia, memudahkan navigasi di antara basis data, dan membantu dalam pengambilan keputusan terkait struktur data.
## Hapus database
kesimpulan dari proses menghapus database berserta format di MySQL adalah bahwa ini adalah tindakan serius yang memerlukan pertimbangan dan persiapan yang matang untuk memastikan bahwa data tidak hilang secara tidak sengaja dan bahwa dampaknya dipahami dengan baik

## Gunakan database
Kesimpulannya, penggunaan basis data di MySQL berserta formatnya melibatkan pemahaman tentang desain data, penggunaan SQL, keamanan, dan kinerja. Pemahaman ini diperlukan untuk memastikan pengelolaan data yang efektif dan aplikasi yang dapat diandalkan.

# Hasil Dari Database
##  Hasil dari Create database
![[hcd.png]]
## Hasil dari show databases
![[hsd.png]]

## Hasil dari Drod database
![[hdd.png]]

## Hasil dari Use
![[hud.png]]
# Tipe Data
## Angka
- Integer (Bilangan Bulat): Digunakan untuk menyimpan bilangan bulat tanpa desimal, seperti 1, -5, atau 100.

- Float (Bilangan Desimal): Untuk menyimpan angka dengan desimal, seperti 3.14 atau -0.5.

- Long (Bilangan Bulat Panjang): Digunakan untuk menyimpan bilangan bulat yang sangat besar.

- Complex (Bilangan Kompleks): Untuk menyimpan angka kompleks yang terdiri dari bagian real dan imajiner.
## Teks
- String: Tipe data yang digunakan untuk menyimpan teks atau karakter. String diwakili oleh serangkaian karakter yang diapit oleh tanda kutip, baik itu tunggal (') atau ganda ("). Contoh: 'hello', "world", atau '123abc'.

- Char: Tipe data yang digunakan untuk menyimpan satu karakter. Char diwakili oleh tanda kutip tunggal (''). Contoh: 'a', 'b', atau '1'.

## Tanggal/waktu
- Date (Tanggal): Tipe data yang digunakan untuk merepresentasikan tanggal. Biasanya terdiri dari tahun, bulan, dan hari. Beberapa bahasa pemrograman memiliki tipe data khusus untuk tanggal, misalnya datetime.date di Python.

- Datetime (Tanggal dan Waktu): Tipe data yang digunakan untuk merepresentasikan tanggal dan waktu. Selain tahun, bulan, dan hari, tipe data ini juga menyertakan informasi waktu seperti jam, menit, dan detik. Contoh: 2024-01-27 15:30:00.
## Boolean
- tipe data boolean digunakan untuk menyimpan nilai kebenaran, yaitu True (benar) atau False (salah). Tipe data boolean umumnya digunakan dalam kondisi percabangan dan pengambilan keputusan.

# Tipe data pilihan
## ENUM
Tipe data ENUM pilihan dalam MySQL memungkinkan Anda untuk menentukan set nilai-nilai yang valid yang dapat dimiliki oleh suatu kolom. Ketika Anda mendefinisikan kolom dengan tipe data ENUM, Anda menyediakan daftar nilai-nilai yang diperbolehkan, dan kolom tersebut hanya dapat mengambil salah satu dari nilai-nilai tersebut.

Keuntungan menggunakan tipe data ENUM pilihan adalah:

1. *Keterbatasan Nilai*: Anda dapat membatasi nilai yang dapat dimasukkan ke dalam kolom, memastikan bahwa hanya nilai-nilai tertentu yang diterima.
2. *Keterbacaan*: Enumerasi nilai-nilai yang diperbolehkan membuat struktur data menjadi lebih mudah dipahami bagi pengguna dan pengembang.
3. *Optimasi Ruang*: Dalam beberapa kasus, tipe data ENUM dapat menghemat ruang penyimpanan karena nilainya disimpan sebagai angka, bukan string.

Namun, ada beberapa pertimbangan yang perlu diperhatikan:

1. *Perubahan Nilai*: Menambah atau menghapus nilai ENUM dapat menyebabkan perubahan skema tabel yang memerlukan perhatian khusus saat berinteraksi dengan database.
2. *Tidak Fleksibel*: Tipe data ENUM cenderung kurang fleksibel dibandingkan dengan tabel referensi terpisah, di mana nilai-nilai referensi dapat dimodifikasi tanpa mengubah struktur tabel induk.
## SET
Di MySQL, tipe data SET memungkinkan Anda untuk menyimpan kumpulan nilai-nilai yang dapat dipilih dalam satu kolom. Sama seperti ENUM, SET juga membatasi nilai-nilai yang dapat dimasukkan ke dalam kolom, namun dengan perbedaan bahwa SET memungkinkan lebih dari satu nilai yang dipilih pada saat yang sama.

Berikut adalah beberapa karakteristik tipe data SET dalam MySQL:

1. *Nilai Berganda*: Dalam kolom dengan tipe data SET, Anda dapat memilih lebih dari satu nilai dari kumpulan nilai yang telah ditentukan.

2. *Daftar Nilai*: Nilai-nilai yang diperbolehkan harus didefinisikan saat membuat tabel, dan setiap nilai harus dipisahkan oleh koma.

3. *Urutan Nilai*: Urutan nilai dalam SET tidak penting. Nilai-nilai yang dipilih akan disimpan dalam urutan yang tidak ditentukan.

4. *Optimasi Ruang*: Tipe data SET dapat menghemat ruang penyimpanan karena nilai-nilai disimpan sebagai sebuah bilangan bulat yang menunjukkan kombinasi bit dari nilai-nilai yang dipilih.

Berikut adalah contoh cara mendefinisikan kolom dengan tipe data SET dalam MySQL:

```mysql
CREATE TABLE example_table (
    id INT AUTO_INCREMENT PRIMARY KEY,
    options SET('option1', 'option2', 'option3', 'option4')
);
```

Dalam contoh ini, kolom options dapat memiliki satu atau beberapa kombinasi nilai dari 'option1', 'option2', 'option3', dan 'option4'. Misalnya, nilai kolom tersebut bisa 'option1,option3' atau 'option2,option4', dan seterusnya.

# Q & A
 >[!faq] Mengapa hanya kolom id_pelanggan yang menggunakan constraint PRIMARY KEY
 >Kolom ID pelanggan seringkali menggunakan constraint PRIMARY KEY karena ID pelanggan adalah atribut yang unik dan dapat digunakan sebagai identifikasi utama untuk setiap entri dalam tabel pelanggan. Dengan membuat kolom ID pelanggan sebagai PRIMARY KEY, kita memastikan bahwa setiap nilai di kolom tersebut adalah unik dan tidak ada yang duplikat. Ini memungkinkan untuk efisiensi pencarian dan pengindeksan data, serta memastikan integritas referensial di dalam basis data. Selain itu, PRIMARY KEY juga dapat digunakan sebagai acuan untuk membuat relasi dengan tabel lain dalam skema basis data.
 
>[!faq] Mengapa pada kolom no_telp yang menggunakan tipe data char bukan varchar
>Tipe data CHAR lebih efisien digunakan untuk kolom yang memiliki nilai tetap atau panjang yang konsisten, seperti ID pelanggan yang biasanya memiliki panjang yang sama untuk setiap entri. Penggunaan tipe data CHAR dapat mengoptimalkan penyimpanan dan kinerja database. Sedangkan tipe data VARCHAR lebih fleksibel dan cocok untuk kolom yang memiliki nilai yang bervariasi dalam panjangnya, seperti teks atau deskripsi. Jadi, jika ID pelanggan memiliki panjang yang tetap, penggunaan tipe data CHAR bisa menjadi pilihan yang lebih efisien.


> [!faq] Menngapa hanya kolom no_telp yang menggunakan constraint UNIQUE?
> Kolom nomor telepon (no_telp) seringkali menggunakan constraint UNIQUE karena nomor telepon harus unik untuk setiap entri dalam tabel. Dengan membuat kolom no_telp sebagai UNIQUE, kita memastikan bahwa tidak ada nomor telepon yang sama yang diizinkan untuk dimasukkan ke dalam basis data. Ini penting untuk mencegah duplikasi nomor telepon, yang dapat mengakibatkan kesulitan dalam mengidentifikasi atau menghubungi pelanggan, serta memastikan integritas data yang lebih baik. Selain itu, menggunakan constraint UNIQUE pada kolom no_telp juga memungkinkan pencarian dan pengindeksan yang lebih efisien.
> 


>[!faq] Mengapa kolom no_telp tidak memakai constraint NOT NULL, sementara kolom lainnya menggunakan constraint tersebut?
>Kolom nomor telepon (no_telp) mungkin tidak menggunakan constraint NOT NULL karena dalam beberapa kasus, nomor telepon tidak selalu tersedia atau wajib diisi. Misalnya, saat membuat entri untuk pelanggan yang belum memiliki nomor telepon, memaksa kolom no_telp menjadi NOT NULL dapat menjadi kendala.
>
>Namun, dalam kebanyakan kasus, memang disarankan untuk menggunakan constraint NOT NULL pada kolom nomor telepon untuk memastikan bahwa setiap entri dalam tabel memiliki nomor telepon yang valid. Hal ini membantu menjaga integritas data dan mencegah nilai yang kosong atau tidak valid. Jadi, keputusan untuk menggunakan constraint NOT NULL pada kolom no_telp tergantung pada kebutuhan aplikasi dan preferensi desain basis data.

>[!faq]  Perbedaan antara PK dan UNIQUE
>

PK (Primary Key) dan Unique Key adalah dua konsep dalam desain database yang sering digunakan untuk memastikan keunikan nilai di dalam sebuah tabel, tetapi mereka memiliki perbedaan yang penting:
1. *Primary Key (PK)*:
   - Sebuah kolom atau kombinasi dari kolom yang secara unik mengidentifikasi setiap baris dalam tabel.
   - PK tidak boleh memiliki nilai yang duplikat, dan tidak boleh memiliki nilai NULL.
   - Hanya ada satu PK dalam satu tabel.
   - Biasanya digunakan untuk membangun hubungan antar-tabel (foreign key).

2. *Unique Key*:
   - Sebuah kolom atau kombinasi dari kolom yang juga memiliki nilai yang unik di dalam tabel.
   - Tidak ada batasan pada jumlah unique key yang bisa ada di sebuah tabel.
   - Nilai dari unique key bisa NULL, tetapi hanya satu baris yang boleh memiliki nilai NULL. Jika sebuah unique key memiliki nilai NULL, maka hanya satu baris yang bisa memiliki nilai NULL untuk unique key tersebut.
   - Biasanya digunakan untuk memastikan bahwa nilai-nilai tertentu dalam tabel unik, tetapi tidak secara khusus digunakan untuk mengidentifikasi setiap baris.

# Table
## Buat Table
1. Pertama-tama kita membuat data base dengan QUERY Create database; seperti contoh di bawah ini:
     ![[hcd.png]]

2. Kemudia kaloh kita ingin melihat nama databese kita, kita menggunakan QUERY show databases; seperti contoh di bawah ini:
    ![[hsd.png]]

3. selanjutnya kita menggunakan database dengan QUERY USE dan kemudian  membuat table dengan Query create dengan nama database kita kemudian kita tuliskan Query yang ada di dalam table kita seperti contoh di bawah ini:
    ![[buat.table3.png]]

4. makah selesai sudah cara kita membuat table dalam mysql kemudian Query Tampilkan table database describe seperti contoh di bawah ini:
     ![[buat.table6.png]]

## Struktur Buat table

```mysql
create table nama_table(
nama_kolom_1 tipe_data(max karaker) conctraint,
nama_kolom_2 tipe_data(max karakter) conctraint,
nama_kolom_3 tipe_data(max karakter) conctraint,
);
```

## Contoh
```mysql
create table data_penduduk(
NIK int(16) primary key not null,
nama varchar(25) not null
nama_keluarga varchar(25),
no_telp char(12) unique);
```

## Hasil
![[buat.table6.png]]

## Analisis
- `create table` Query untuk membuat table, `data_penduduk` adalah nama table yang kita buat
- `NIK` (Nomor induk kependudukan) adalah sebuah nilai/kerakter kolom pertama `int(16)` adalah sebuah tipe data yang maxsimun 16 kerakter `PRIMARY KEY` Kolom ini merupakan primary key dari tabel, yang berarti setiap nilai di kolom ini harus unik dan tidak boleh NULL. Dengan demikian, NIK digunakan untuk mengidentifikasi setiap penduduk secara unik. `not null` adalah sebuah constraint_data tidak boleh kosong
- `nama` adalah sebuah nilai/kerakter kolom kedua. `varchar` adalah sebuah tipe data yang maxsimun 16 kerakter `not null` adalah sebuah constraint_data tidak boleh kosong
- `nama keluarga` adalah sebuah nilai/kerakter kolom ketiga. `varchar` adalah sebuah tipe data yang maxsimun 16 kerakter `not null` adalah sebuah constraint_data tidak boleh kosong
- `no_telp` adalah sebuah nilai/kerakter kolom ketiga. `char` adalah sebuah tipe data yang maxsimun 16 kerakter `unique` Menggunakan constraint UNIQUE, yang memastikan bahwa tidak ada dua penduduk dengan nomor telepon yang sama dalam tabel. 

## kesimpulan
1. NIK (Nomor Induk Kependudukan):
   - Primary Key: Kolom ini berperan sebagai primary key, yang berarti setiap baris dalam tabel memiliki nilai NIK yang unik dan tidak dapat kosong.
   - Tipe Data: INT(16) menunjukkan bahwa NIK adalah bilangan bulat dengan panjang maksimum 16 digit.

2. nama (Nama Penduduk):
   - Tidak boleh Kosong: Constraint NOT NULL diterapkan, yang berarti setiap entri dalam kolom ini harus memiliki nilai.
   - Tipe Data: VARCHAR(25) menunjukkan bahwa nama bisa memiliki maksimum 25 karakter.

3. nama_keluarga (Nama Keluarga Penduduk):
   - Tidak ada Constraint Khusus: Kolom ini dapat memiliki nilai NULL, dan nilai yang sama dapat muncul berkali-kali.
   - Tipe Data: VARCHAR(25) menunjukkan bahwa nama keluarga bisa memiliki maksimum 25 karakter.

4. no_telp (Nomor Telepon):
   - Unik: Constraint UNIQUE diterapkan, memastikan bahwa setiap nomor telepon di kolom ini harus unik di antara semua entri dalam tabel.
   - Tipe Data: CHAR(12) menunjukkan bahwa nomor telepon harus memiliki panjang tepat 12 karakter.
# Insert
## Insert 1 data

### Struktur
```mysql
insert into nama_table
valeus ('NILAI','NILAI2','NILAI3','NILAI4');
```

## Contoh
```mysql
insert into customerr values (1,'raihan','alfz','087868449445');
```

## Insert >1 data
```mysql
insert into nama_table
valeus ('NILAI','NILAI2','NILAI3','NILAI4'),
('NILAI','NILAI2','NILAI3','NILAI4'),
('NILAI','NILAI2','NILAI3','NILAI4');
```
## Contoh
```mysql
insert into customer
    -> Values(2,'isar','rmn','085882169640'),
    -> (3,'Jamil','lhm','085823967204'),
    -> (4,'ardy','rd','0895333405548');
    ```

# Menyebut kolom
```mysql
insert into nama_table
('NILAI','NILAI2','NILAI3','NILAI4') values ('NILAI','NILAI2','NILAI3','NILAI4')
```

## Contoh
```mysql
Insert into customer
(nama_asli,id_customer) values ('hansar',5);

```

## Hasil
![[h.insert .png]]

![[h.select 1 kolom.png]]
![[h.insert tabel baru.png]]

## Analisis

## Kesimpulan


# Select
## Struktur
```mysql
select * from nama_tabel;
```

## Contoh
```mysql
select * from customer;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:
![[tabel3.png]]

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk menampilkan semua data dari tabel 'customer'. Tidak ada kondisi pencarian khusus yang ditentukan dalam query ini, sehingga query akan mengembalikan semua baris yang ada dalam tabel 'customer'.

Analisis:
- SELECT *: Memilih semua kolom dari tabel 'customer'.
- FROM customer: Menentukan tabel yang akan diambil datanya, yaitu 'customer'.

Jadi, hasil dari query ini akan menampilkan semua data yang tersimpan dalam tabel 'customer'.
## Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data yang tersimpan dalam tabel 'customer'. Ini berarti query tersebut akan mengembalikan daftar lengkap dari semua entri dalam tabel 'customer', termasuk semua kolom yang ada dalam tabel tersebut seperti nama, alamat, nomor telepon, dll.


# Data kolom tertentu
## Struktur

```mysql
select nama_kolom1,nama_kolom2,nama_kolom3,nama_kolom4 from nama_table;
```

## Contoh
```mysql
select nama_depan from customer;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:
![[tabel4.png]]

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk menampilkan hanya kolom 'nama_depan' dari tabel 'customer'. 

Analisis:
- SELECT nama_depan: Memilih hanya kolom 'nama_depan' dari tabel 'customer'.
- FROM customer: Menentukan tabel yang akan diambil datanya, yaitu 'customer'.

Jadi, hasil dari query ini akan menampilkan semua nilai yang ada dalam kolom 'nama_depan' dari tabel 'customer'.
## Kesimpulan
Query MySQL di atas digunakan untuk mengambil data dari kolom 'nama_depan' dalam tabel 'customer'. Ini berarti query tersebut akan menghasilkan daftar semua nilai yang ada dalam kolom 'nama_depan' dari tabel 'customer'.



# KLAUSA WHERE

## Struktur
```mysql
select nama_kolom/ *from nama_table
where kondisi;
```

## Contoh
```mysql
select * from customer
where id_customer=2;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:
![[tabel5.png]]

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk menampilkan semua data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 2.

Analisis:
- SELECT *: Memilih semua kolom dari tabel 'customer'.
- FROM customer: Menentukan tabel yang akan diambil datanya, yaitu 'customer'.
- WHERE id_customer=2: Menentukan kondisi pencarian dimana nilai kolom 'id_customer' harus sama dengan 2.

Jadi, hasil dari query ini akan menampilkan semua data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 2. Ini berarti hanya satu baris data yang akan ditampilkan, yaitu data dari pelanggan dengan ID 2.
## Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 2. Ini berarti query tersebut akan menghasilkan daftar lengkap dari semua kolom untuk pelanggan dengan ID 2.

# Update

## Struktur
```mysql
 update nama_tabel set nama_kolom where kondisi;
```

## Contoh
```mysql
 update customer set no_telp="08127611712" where id_customer="2";
```
## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:
![[H.UPDATE.png]]

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk memperbarui data dalam tabel 'customer'. Query tersebut memiliki dua bagian utama:

1. UPDATE customer: Menentukan tabel yang akan diperbarui, yaitu 'customer'.
2. SET no_telp="08127611712" WHERE id_customer="2": Menentukan nilai baru yang akan diatur untuk kolom 'no_telp' dimana nilai kolom 'id_customer' sama dengan 2.

Analisis:
- UPDATE customer: Menentukan tabel yang akan diperbarui.
- SET no_telp="08127611712": Menentukan nilai baru untuk kolom 'no_telp'.
- WHERE id_customer="2": Menentukan kondisi dimana hanya data dengan nilai kolom 'id_customer' sama dengan 2 yang akan diperbarui.

Jadi, hasil dari query ini akan memperbarui nomor telepon pelanggan dengan ID 2 menjadi "08127611712" dalam tabel 'customer'.
## Kesimpulan
Query MySQL di atas adalah perintah untuk memperbarui nomor telepon pelanggan dengan ID 2 menjadi "08127611712" dalam tabel 'customer'. Ini berarti nomor telepon untuk pelanggan dengan ID 2 akan diperbarui dengan nomor yang baru.
# Delate

## Struktur
```mysql
DELETE FROM nama_tabel WHERE kondisi;
```

##  Contoh
```mysql
DELETE FROM CUSTOMER WHERE ID_CUSTOMER=1;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:
![[H.DELETE.png]]

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk menghapus data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1.

Analisis:
- DELETE FROM customer: Menentukan tabel yang akan dihapus datanya, yaitu 'customer'.
- WHERE id_customer=1: Menentukan kondisi pencarian dimana nilai kolom 'id_customer' harus sama dengan 1.

Jadi, hasil dari query ini akan menghapus satu baris data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1. Ini berarti data pelanggan dengan ID 1 akan dihapus dari tabel 'customer'.Query MySQL di atas adalah perintah yang digunakan untuk menghapus data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1.

Analisis:
- DELETE FROM customer: Menentukan tabel yang akan dihapus datanya, yaitu 'customer'.
- WHERE id_customer=1: Menentukan kondisi pencarian dimana nilai kolom 'id_customer' harus sama dengan 1.

Jadi, hasil dari query ini akan menghapus satu baris data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1. Ini berarti data pelanggan dengan ID 1 akan dihapus dari tabel 'customer'.
## Kesimpulan
Query MySQL di atas adalah perintah untuk menghapus data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1. Ini berarti data pelanggan dengan ID 1 akan dihapus dari tabel 'customer'