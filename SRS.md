SOFTWARE REQUIREMENTS SPESIFICATION

![img](https://lh3.googleusercontent.com/-onacuhIfe3o/Wo527rrDQxI/AAAAAAAAAIY/vbWMfcRxOQ4Qfsou4ovY6TqzVo_fd5PnwCJoC/w530-h530-n-rw/POLINDRA.png)                                                                        

 

 

 

 

 

 

 

 

 

 

 

 

 

Disusunoleh   :

Eko Prastyo                 (1603096)

Syahrul Gunawan    			(1603113)

Tuti Nurafni Amalia			(1603116)

Wulandiani                  (1603118)

 

 

 

 

 

JURUSAN TEKNIK INFORMATIKA

POLITEKNIK NEGERI INDRAMAYU 2018

 

 

BAB 1

PENDAHULUAN

1.1  Tujuan

Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun ”Aplikasi Pemesanan Lapangan Futsal ”. Dokumen ini dibangun untuk memudahkan Prima  Fusal dan Sintia Sinta Futsal .Dalam melakukan proses pemesanan lapanganfutsal yang dilakukan oleh penyewa lapangan. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "Let's Ball" Aplikasi Pemesanan Lapangan Futsal.

1.2  Lingkup proyek

Lets'sBall merupakan aplikasi untuk pengguna kalangan umum untuk pemesanan dan penjadwalan penggunaan lapangan futsal, serta dapat memberikan informasi pemesanan lapangan dan penjadwalan futsal. dan mempermudah pelanggan untuk pemesanan lapangan futsal.

1.3  Definsi,akronim,singkatan

| Istilah | Arti                                             |
| ------- | ------------------------------------------------ |
| SRS     | *Software  Requirement Specifications*           |
| IEEE    | Institute of Electrical and Electronics Engineer |

 

1.4  Referensi

[1]IEEE Software Engineering Standards Committee, “IEEE Std 830-1998, IEEERecommended

Practicefor Software Requirements Specifications”, October 20, 1998.

[2]Feldt R,”re_lecture5b_100914”, unpublished.

 

 

 

 

 

 

 

 

BAB 2

GAMBARAN UMUM

Aplikasi pemesanan lapangan futsal membantu user atau calon pelanggan untuk memesan lapangan,

2.1 Perspektif Produk 

Produk ini memiliki fungsi pemesanan lapangan futsal melalui *mobile apps*. Penggunaan sistem terbagi menjadi dua yaitu antar muka pelaggan menggunakan *mobile apps* dan antarmuka admin menggunakan *web apps*.Dibandingkan dengan aplikasi yang sudah ada sebagian besar berbasis website disamping itu belum ada aplikasi yang bernar-benar digunakan.Kemudian aplikasi memiliki keunggulan bisa mencatat transaksi pemesanan lapangan untuk pemilik usaha futsal. Selain itu aplikasi ini sebagai promosi pemilik futsal untuk meningkatkan pendapatan usahanya.

2.1.1 Antarmuka sistem

Bagian sistem aplikasi untuk sisi user menggunakan *mobile apps* yang bisa menampilkan menu daftar dan login sebagai autentifikasi awal masuk ke sistem, kemudian bisa menampilkan form pemesanan lapangan kepada calon pelanggan, selanjutnya sistem mampu menampilkan daftar lapangan yang tersedia dan belum dipesan atau kosong. Disamping itu sistem memliki fitur tampilan bukti pemesanan yang dapat dicetak oleh calon pelanggan kemudian mampu mengirim bukti pembayaran ke server.   

Bagian sistem aplikasi untuk sisi admin menggunakan *web apps*. Sistem mampu menampilkan tampilan login admin. Kemudian menampilkan fitur menipulasi data lapangan dan tarif, kemudian memiliki fitur menampilkan konfirmasi pembayaran,selanjutnya sistem mampu menampilkan daftar pelanggan yang memesan. Disamping itu sistem melakukan transaksi pemesanan lapangan.

 

 

 

 

 

 

 

 

 

 

2.1.2 Antarmuka pengguna

![img](https://lh3.googleusercontent.com/-82R76oif8eA/Wp9qnbhVVBI/AAAAAAAAANc/OMISVh_uyfskuiNxZTuE5dJxkbBatYItwCL0BGAs/w414-d-h736-n-rw/daftar.jpg)

Gambar 2.1 Daftar user

​            Menudaftar user menggunakan form tampilan text edit,password dan button menggunakan warna merah dan memiliki latar belakang orang menendang bola ,kemudian terdapat link login berwaran biru.

![img](https://lh3.googleusercontent.com/-Yzb95U1nufc/Wp9qkgZTegI/AAAAAAAAANQ/q_fNGhPBNKADYXes5v9yuh2b5aY55aJ0gCL0BGAs/w414-d-h736-n-rw/login.jpg)

Gambar 2.2 Tampilan login

​            Tampilan login terdapat text edit email dan password dilengkapi icon email dan kunci. di sisi atas terdapat header berwarna merah dengan tulisan berwarna putih. di sisi bawah terdapat button login,link lupa password,dan link register.

 

 

 

 

 

 

 

 

 

![img](https://lh3.googleusercontent.com/-PIzm7F4EZyE/Wp9qhuFa51I/AAAAAAAAANE/m33W0qFaQY45VH-yL0cVt_4DfoHG5A3UQCL0BGAs/w414-d-h736-n-rw/menu%2Bawal.jpg)

Gambar 2.3 Menu awal

​            Tampilan menu awal terdapat header berwarna merah dengan tulisan berwarna putih. Kemudian dibawah header terdapat icon fitur utama berwarna merah.

![img](https://lh3.googleusercontent.com/-FEWKudkYP9E/Wp9odATlfuI/AAAAAAAAAMQ/qOPc5y4f5FQ5RPAqPxVC15BRyK9w6rsgQCJoC/w414-h736-n-rw/daftar%2Bllapangan.jpg)

Gambar 2.4 Tampilan list lapangan

​            Tampilan list lapangan terdapat header berwarna merah dengan tulisan berwarna putih dan di sisi kiri terdapat icon panah berwarna putih. Kemudian di bawahnya terdapat 3 textview dan 2 button.

 

 

 

 

 

 

 

 

 

![img](https://lh3.googleusercontent.com/-Sf8iaxYabm4/Wp9qqfazAzI/AAAAAAAAANo/zLstdCq4wQ016zSE_Y4PuYPK33z_uN_wACL0BGAs/w414-d-h736-n-rw/daftar%2Bpemesan.jpg)

Gambar 2.5 Tampilan daftar pemesan

​            Tampilan daftar menggunakan data tabel berwarana abu dengan jumlah kolom sebanyak 4 kemudian di setiap baris di variasi warna putih dan abu-abu. 

 

 

 

 

 

 

 

 

 

![img](https://lh3.googleusercontent.com/-oBNUr2ecXmM/Wp9r1nNk8AI/AAAAAAAAAOM/U2dHFB3b_AAwePMb1a6jS6U-CYzKI9KVACL0BGAs/w530-d-h336-n-rw/Antarmuka%2BHardware%2B-%2BAntarmuka%2BHardware%25281%2529.png)2.1.3Antarmuka perangkat keras

 

 

 

 

 

 

 

 

 

Antarmuka perangkat keras calon pemesan menggunakan device *smartphone* android untuk bisa memesan pertama kali device harus terhubung ke internet kemudian membuka aplikasi sistem maka terhubung ke server. Kemudian antarmuka perangkat keras admin menggunakan device komputer atau laptop dan pastikan terhubung dengan internet selanjutnya buka website sistem admin.

2.1.4 Antarmuka perangkat lunak

2.1.5 Antarmuka komunikasi

2.1.6 Batasan-batasan memori

2.1.7 Operasi-operasi

​            Sistem ke calon pelanggan mampu menampilkan menu login untuk autentifikasi pertama dan menampilkan form pendaftaran pelanggan yang belum memiliki akun, selanjutnya menampilkan daftar lapangan yang tersedia, menampilkan form pemesanan lapangan, menampilkan bukti pemesan untuk dicetak, dan mengirim bukti pembayaran lapangan.

​            Sistem ke admin menampilkan menu login admin. Kemudian menampilkan fitur manipulasi data lapangan dan tarif harga, menampilkan daftar pelanggan yang memesan lapangan. Kemudian menampilkan konfirmasi pembayaran dan transaksi.   

2.1.8 Kebutuhan-kebutuhan dalam tahapan adaptasi

 

 

 

 

2.2 Spesifikasi kebutuhan fungsional

​            A. Usecase admin

![img](https://lh3.googleusercontent.com/-oMzaRahEeOc/Wp9sFFv2HGI/AAAAAAAAAOk/ySSSblqSDlAPgUcRWB5r1jyM16dF9GLdQCL0BGAs/w530-d-h416-n-rw/Use%2BCase%2BMember%2B-%2BUse%2Bcase%2Bdiagram%2Badmin%25281%2529.png)

![img](https://lh3.googleusercontent.com/-uRmM-vI1VvA/Wp9r9D9d9PI/AAAAAAAAAOY/C6hPd-uAw5wF_YrJG_qqST7Xo_qe-qL7ACL0BGAs/w530-d-h433-n-rw/Use%2BCase%2BMember%2B-%2BUse%2Bcase%2Bdiagram%2Bpelanggan%25282%2529.png)            B. Usecase calon pelanggan

 

 

 

 

 

 

 

 

 

 

 

 

 

2.3 Karakteristik pengguna

2.4 Batasan-batasan

| Kategori pengguna | Tugas                              | Hak Akses ke Aplikasi |
|-------------------|------------------------------------|-----------------------|
| Admin             | CRUD data lapangan                 | Admin                 |
|                   | CRUD tarif harga lapangan          |                       |
|                   | mengkonfirmasi data pembayaran     |                       |
|                   | pendataan pemesanan lapangan       |                       |
|                   | transaksi pembayaran               |                       |
| user              | melihat jadwal lapangan kosong     | user pengguna         |
|                   | menginputkan data booking lapangan |                       |
|                   | mengkonfirmasi pembayaran          |                       |

2.4Batasan-batasan


2.5 Asumsi-asumsi dan ketergantungan/keterkaitan

2.6 Kebutuhan-kebutuhan penyeimbang

 

 

 

 


BAB 3
PERSYARATAN KEBUTUHAN 
3.1 Persyaratan antar muka 

3.2 Functional Requirement

3.3 Struktur Detail Kebutuhan Non-Fungsional
3.3.1 Logika Struktur Data
3.3.2 Keamanan
