# Question 1

Silahkan perhatikan diagram ERD di bawah ini
Terdapat beberapa ketentuan dari diagram ERD tersebut:<br>
a. Setiap siswa dapat mengambil beberapa course<br>
b. Setiap course diambil oleh banyak mahasiswa<br>
c. Id_student memiliki tipe data integer dengan length 8<br>
d. Name memiliki tipe data char dengan length 30<br>
e. Address memiliki tipe data varchar dengan length 60<br>
f. Id_course memiliki tipe data varchar dengan length 5<br>
g. Course title memiliki tipe data varchar dengan length 25<br>
 Buatlah model relational, CDM, dan PDM dari ERD diatas**

 ![image](https://github.com/Crown-us/Praktikum-Basis-Data/assets/55532281/f60a55fe-d40f-439e-9ce3-743fb7aae2a8)

# CDM :
![image](https://github.com/Crown-us/Praktikum-Basis-Data/assets/55532281/23dc0209-9e3c-4c08-ad01-0e541d436e66)


# PDM :
![image](https://github.com/Crown-us/Praktikum-Basis-Data/assets/55532281/8f101e4b-4872-4630-89f7-c16e7ee1742b)


# Question 2

Buatlah CDM dan PDM untuk skenario berikut dengan terlebih dahulu membuat relational key yang
terdiri dari nama relasi, superkey, candidate key, primary key, foreign key, dan alternate key.
“Salah satu toko boneka di Malang ingin merubah sistem penjualan yang awalnya manual menjadi otomatis. Oleh karena itu dibutuhkan peracangan basis data dengan memperhatikan proses bisnis dan objek yang terlibat dalam kegiatan jual bali di toko boneka tersebut. Terdapat beberapa
ketentuan di toko tersebut sebagai berikut :<br>**
**1) Member memiliki salah satu jenis member<br>**
**2) Member dapat melakukan pembelian sebanyak mungkin selama membutuhkan. Dan setiap transaksi penjualan dilakukan oleh setiap member secara bergantian<br>**
**3) Pegawai dapat melayani banyak transaksi penjualan dalam sehari<br>**
**4) Setiap hari banyak boneka yang terjual, dan sekali transaksi penjualan dapat terdiri dari beberapa boneka secara sekaligus**

# CDM
![image](https://github.com/Crown-us/Praktikum-Basis-Data/assets/55532281/1ada8337-0f5f-4c9e-8518-951d1a05dfc0)

# PDM
![image](https://github.com/Crown-us/Praktikum-Basis-Data/assets/55532281/928e12b1-05f2-4e2d-b38f-2b93889b893d)

# Question 3

**> ID : Buatlah tabel deskripsi, CDM dan PDM untuk skenario berikut :
“Salah satu restaurant terbesar di Indonesia ingin memperbaiki sistem booking yang dulunya manual menjadi otomatis. Untuk itu diperlukan perncangan basis data sesuai dengan kebutuhan dan sistem yang ada di restaurant tersebut.
Konsumen : kode konsumen, nama awal, nama akhir, no telepon, email, dan keterangan.
Booking : kode booking, dan tanggal<br>
Meja : no meja dan detil meja<br>
Pesanan : kode pesan, dan tanggal<br>
Staf : kode staf, nama awal, nama akhir<br>
Peranan : kode peranan, nama peranan<br>
Menu pesanan : kode menu pesanan, kuantitas, komen<br>
Menu : kode menu, tanggal<br>
Item menu : kode item menu, keterangan, harga<br>
Bahan : kode bahan, nama bahan<br>
Item bahan : kode item bahan dan kuantitas<br>
Tipe bahan : kode tipe bahan dan deskripsi<br>**

**Terdapat beberapa aturan dalam proses pemesanan di restaurant tersebut. Mulai dari setiap konsumen dapat melakukan banyak booking atau tidak sama sekali, setiap meja dapat dibooking oleh banyak konsumen atau tidak sama sekali. Setelah mendapatkan meja pemesanan dapat dilakukan atau tidak jadi dilakukan. Setiap pesanan dilakukan hanya pada satu meja, dan setiap staf dapat melayani banyak pesanan dalam suatu waktu atau tidak sama sekali. Staf yang melayani konsumen pasti memiliki peranan tertentu. Pemesanan dapat memesan banyak menu pesanan atau tidak sama sekali (dalam artian hanya meminjam meja saja tetapi menu dari luar). Setiap item menu terdapat dalam banyak menu pesanan atau tidak sama sekali. Item menu dapat
tertulis atau tidak tertulis di dalam menu yang disediakan. Item menu yang ada terdiri dari banyak Item bahan atau bahkan tidak tertulis di dalam item bahan. Semua bahan yang digunakan dalam item bahan tersimpan di dalam informasi bahan, tetapi belum tentu sebaliknya. Ternyata bahan tersebut memiliki tipe bahan yang bisa jadi sama antara satu bahan dengan bahan yang lain atau bahkan tidak ada di dalam bahan yang tersedia**

# CDM
![image](https://github.com/Crown-us/Praktikum-Basis-Data/assets/55532281/3927b57b-5d2f-421d-b414-f0baf5d13752)

# PDM 
![image](https://github.com/Crown-us/Praktikum-Basis-Data/assets/55532281/8ac681c3-df59-407f-ac2e-da9442b4209c)


