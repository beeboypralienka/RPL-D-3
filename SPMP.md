# SPMP_RPL
**BAB I**

**SOFTWARE PROJECT MANAGEMENT PLAN** 

**1 Pendahuluan**

**1.1 Gambaran Proyek**

	Proyek yang sedang kami buat adalah membangun sebuah Aplikasi Booking Lapangan Futsal. Dalam rencana pembangunan software,banyak hal yang harus diperhatikan oleh konsumen maupun produsen(programmer) terutama dalam hal pengelolaan waktu dan nilai yang harus dikeluarkan. Adanya kesalahan perhitungan tentu akan memberikan kerugian pada kedua pihak, hal-hal seperti yang harus kita minimalisir. Untuk itu sistem ini dibangun dengan fungsi utama melakukan planing terhadap proyek yang akan dibuat atau dipesan oleh konsumen. Dengan adanya fungsi tersebut, sistem ini dapat merencanakan pembuatan sebuah software dengan baik, dan pasti. Tentunya dalam membangun sistem ini kami butuh sebuah tim yang solid agar dalam proses pembuatannya tidak mengalami banyak kendala, tim kami terdiri dari ketua, programmer, sekertaris, dan seorang tester. Dengan struktur tim tersebut, kami bermaksud membagi beberapa tugas sesuai kriteria kemampuan masing-masing, yang nantinya satu sama lain diharapkan dapat bekerja sama dan melengkapi satu sama lain, sehingga dapat membangun sistem yang baik sesuai yang konsumen/pasar butuhkan.

	Teknologi yang semakin pesat, memberikan dampak paksaan bagi semua pihak untuk berlomba-lomba membangun sistem yang berbasis teknologi informasi, yang disandingkan dengan berbagai bidang, seperti pendidikan, pemasaran, travel, sosial media dan lain-lain. Kemudahan yang ditawarkan menciptakan individu yang haus akan teknologi. Tentu hal ini mendorong terbentuknya pasar tersendiri di dunia teknologi informasi, hal ini kami menfaatkan untuk memenuhi kebutuhan konsumen yang meliputi organisasi, lembaga pemerintahan, pasar, atau individu yang membutuhkan software penunjang kegiatan produksi. Dengan adannya software penunjang, konsumen akan dimudahkan penggunaan waktu ataupun tenaga, sehingga meningkatkan kegiatan produksi. Dengan adanya sistem inilah membuat pemesan/konsumen dapat mengelola waktu dan budget yang harus dikeluarkan untuk membangun sebuah perangkat lunak.


**1.2 Dokumen-dokumen dalam proyek**

	Saat mengerjakan projek ini, pencatatan kegiatan yang telah dilakukan ditulis didalam log book kelompok, anggota yang telah mengerjakan tugas sesuai projek kegiatannya dicatat dalam log book, selain log book dokumen yang berkaitan dengan projek ini meliputi requirtments, penjadwalan, pembagian tugas, dan referensi-referensi yang berkaitan dengan pembuatan projek kami.

**1.3 Revolusi SPMP**

	Dokumen ini bersifat freeware, jadi siapa saja boleh untuk memanfaatkan dokumen ini untuk hal yang positif. Tentu ada hal-hal yang tidak boleh dilakukan dalam pemanfaatan dokumen ini, seperti menjualbelikan dokumen ini secara ilegal, atapun mengubah dokumen tanpa dasar yang jelas.

**1.4 Material acuan**

	Materi yang menjadi acuan dalam pembuatan projek ini menggunakan standar ESA, karena menyediakan kerangka kerja yang menggabungkan seluruh spektrum proses siklus hidup perangkat lunak. Dan juga standar ESA untuk membentuk model yang diakui secara internasional dari kehidupan perangkat lunak umum, siklus proses yang dapat direferensikan oleh industri perangkat lunak diseluruh dunia, untuk mempromosikan pemahaman diantara pihak bisnis dengan aplikasi umum serta mengakui proses, kegiatan dan tugas.

	ESA (European Space Agency) merupakan standard perancangan rekayasa perangkat lunak dengan profesi Rekayasa Perangkat Lunak dan Standardisasi
	Dalam Divisi Sistem Perangkat Lunak, Bagian Rekayasa Perangkat Lunak dan Standardisasi bertanggung jawab atas teknologi dan standar rekayasa perangkat lunak.Bagian ini memiliki keahlian dalam metode perangkat lunak, peralatan, arsitektur dan standar. Rekayasa Perangkat Lunak dengan tanggung jawab bagian mencakup seluruh siklus hidup perangkat lunak, dengan penekanan pada fase awal seperti rekayasa ulang sistem perangkat lunak, teknik persyaratan, desain, bahasa pengkodean dan lingkungan kompilator, pembuatan generasi kode dan uji validasi.
	Beberapa studi Litbang memberikan blok bangunan untuk penggunaan potensial dalam arsitektur generik. Standardisasi perangkat lunak bagian ini sangat terlibat dalam standardisasi perangkat lunak, baik untuk standar ESA internal melalui co-chairmanship BSSC (Board for Software Standardization and Control), dan untuk standar perangkat lunak eksternal - terutama dengan *ECSS (European Cooperation for Space Standardization)* dan terkadang dengan ISO. Kemudian Dukungan proyek bagian ini mendukung banyak proyek luar angkasa, termasuk Galileo (segmen ruang dan darat), EGNOS, percobaan gayaberat mikro dan muatan stasiun luar angkasa, ATV, ExoMars, Vega dan Ariane 5.

**1.5 Definisi dan Akronim (singkatan)**

	Dalam  penulisan  dokumen  pembuatan  projek  ini,  ada  beberapa  kata  yang mungkin akan sulit dipahami oleh orang awam berikut ini :

**Tabel I.1 Akronim**

**Singkatan=====================Arti kata**

  **ESA = European Space Agency**
  **APK = Application Package File**

  	APK *file* (*application package file*) adalah applikasi mentah (bisa disebut installer) dari OS Android.

  	ESA (European Space Agency) merupakan standard perancangan rekayasa perangkat lunak dengan profesi Rekayasa Perangkat Lunak,Standardisasi,dan dukungan proyek.


**BAB 2 Organisasi Proyek**


**2.1  Model proses**

  	Dalam kesempatan ini kami menggunakan model V-model untuk membuat aplikasinya 	 

**2.2.1 Definisi**
	
  	Merupakan model pengembangan perangkat lunak yang didasarkan pada hubungan antara setiap fase pengembangan siklus hidup yang tercantum dalam model Watterfall yang merupakan pengembangan perangkat lunak dan fase yang terkait pengujian. Bisa dikatakan model ini merupakan perluasan dari model waterfall. Disebut sebagai perluasan karena tahap-tahapnya mirip dengan yang terdapat dalam model waterfall. Jika dalam model waterfall proses dijalankan secara linear, maka dalam model V proses dilakukan bercabang.

**2.2.2 Kelebihan**

1. V Model sangat fleksibel. V Model mendukung project tailoring dan 	penambahan dan pengurangan method dantool secara dinamik. Akibatnya sangat mudah untuk melakukan tailoring pada V Model agar sesuai dengan suatu proyek tertentu dan sangat mudah untuk menambahkan method dan tool baru atau menghilangkan method dan tool yang dianggap sudah obsolete.

2. V Model dikembangkan dan di-maintain oleh publik. Userdari V Model berpartisipasi dalam change control boardyang memproses semua change request terhadap V Model.

**2.2.3 Kekurangan**

1. V Model adalah model yang project oriented sehingga hanya bisa digunakan sekali dalam suatu proyek.
2. V Model terlalu fleksibel dalam arti ada beberapa activitydalam V Model yang digambarkan terlalu abstrak sehingga tidak bisa diketahui dengan jelas apa yang termasuk dalamactivity tersebut dan apa yang tidak.

**2.2.4 Tujuan**

  	Untuk pengembangan versi pertambahan software secara cepat. untuk menyelesaikan sistem secara global terlebih dahulu, kemudian untuk feature dari sistem akan dikembangkan kemudian. Sehingga mempercepat dalam pengimplementasian project. 

**2.2.5 Cara kerja**

  	Bentuk spiral memberikan gambaran bahwa makin iteraksinya membesar, maka menunjukkan makin lengkapnya versi dari perangkat lunak yang digunakan. Selama awal  sirkuit,  objektif,  alternatif dan  batasan  didefinisikan  serta  resiko diidentifikasi dan dianalisa. Jika analisa resiko menunjukkan ada ketidakpastian terhadap kebutuhan, maka prototyping harus dibuat pada kuadran engineering. Simulasi dan pemodelan lain dapat digunakan untuk mendefinisikan masalah dan memperbaiki kebutuhan. Pelanggan mengevaluasi hasil engineering (kuadran customer evaluation) dan membuat usulan untuk perbaikan. Berdasarkan masukan dari pelanggan, fase berikutnya adalah planning dan analisis resiko. Setelah analisis resiko, selalu diperiksa apakah proyek diteruskan atau tidak, jika resiko terlalu besar, maka proyek dapat dihentikan.

**2.2 Struktur Organisasi**

**|  Ketua |**

**|Programer|**  ===== **Sekretaris** ===== **Tester**

**2.3  Batasan dan Antarmuka Organisasi**

  	Ketua dimana harus mejadi pengawas dari anggota – anggotanya bilamana saat anggota lalai dengan tugas – tugasnya, Ketua berhak menegur dan bagi anggota tidak berhak melawan jika ditegur, dan untuk Ketua sendiri tidak berhak semena-mena dengan jabatanya. Tester dimana saat programmer melakukan kesalahan dalam mengkoding tester memiliki tanggung jawab untuk mengecek kesalahan koding – koding yang dilakukan programmer.
  
  	Sekertaris  dimana  bertanggung  jawab  untuk  menyimpan  dokumen–dokumen yang diperlukan untuk penggarapan dan hasil akhir project. Programmer dimana dia bertanggung jawab untuk membuat dan menyempurnakan suatu program.

**2.4 Lingkup dan Tanggungjawab**


**2.4.1 Penjelasan**

 	Lingkup dan tanggung jawab ini berisi tugas dari setiap elemen anggota dalam pembuatan proyek RPL ini. 

**2.4.2 Manager**

	Manager adalah seseorang mempunyai tanggung jawab dan tugas yang besar dalam sebuah tim, tidak hanya terfokus pada hal-hal yang teknis sifatnya. Manager juga harus mampu memajemen tim dengan baik, agar target projek dapat tercapai. Selain itu memberi pengarahan, memonitoring kinerja tim, serta serta membagi tugas juga bagian tanggung jawab dari seorang manager.

**2.4.3 Programmer**

	Dalam hal ini, seorang programer bertugas untuk mengimplementasikan dari sistem yang sudah dirancang didesain. Programmer dituntut dapat menuliskan code program dengan baik, dan efesien. Hal ini dimaksudakan untuk menghindari terjadinya banyak error dalam proses implementasinya.

**2.4.4 Tester**

	Dalam proyek ini, tester bertugas untuk melakukan pengecekan terhadap sebuah software/aplikasi. Apakah ada error data bug didalamnya, seorang tester harus teliti dalam melakukan tugasnya, apabila ada error yang dilewatkan, maka konsumen akan dirugikan.

**BAB 3 Proses Manajerial**

**3.1 Tujuan dan Prioritas Manajemen**

**3.1.1 Prioritas Jadwal**


	Prioritas jadwal yang dilakukan pada saat ini adalah membuat sistem yang akan dibuat, dokumen   projek, jadwal   kegiatan, struktur pembuatan projek dan organisasi

**3.1.2 Budget**

	Prioritas budget untuk project ini lebih ditekankan pada kualitas hardware dan requirtment proyek.

**3.1.3 Kemampuan (Kualitas dan reusability)**

	Projek yang kami buat saat ini mempunyai kelebihan dalam memanajemen pembuatan proyek, juga berbasis desktop yang membuat konsumen merasa lebih budah dalam interaksinya.

**3.2 Asumsi, Keterkaitan, dan batasan**

**3.2.1 Asumsi**

	Adapun aplikasi yang sejenis aplikasi manajemen berbasis dekstop, projek yang kami buat membutuhkan unit komputer sebagai media penghubungnya.

**3.2.2 Keterkaitan dan Batasan**

	Dalam projek yang kami buat adapun beberapa software desktop yang mendukungnya, seperti xampp sebagai perantara mysql database. Namun ada batasannya, yaitu tidak bisa digunakan secara online. 

**3.3 Manajemen Resiko**

**3.3.1 Dampak Positif**

**Resiko**	 

1.	Estimasi biaya dan waktu yang tidak realitis.

2.	Mengembangkan sofware yang salah.
	
**Penanganan Resiko**

1.	Membuat berapa biaya etimasiDesain untuk biaya
Merekam danmenganalisa project yang akan dibuat. 
 
2.	Evaluasi project yang ditingkatkan
	Buat metode spesifikasi yang formal
    Survai pengguna
    Buat prototype

**3.4 Mekanisme Monitoring dan Kontroling**

**3.4.1 Monitoring**

	Proses monitoring dilakukan secara tim, adapun proses pelaksanaannya dilakukan setiap hari senin.

**3.4.2 Kontroling**

	Sedangkan proses dilaksanakan setiap hari jumat, hal ini dilakukan agar hasil kerja proyek dapat dievaluasi pada hari terakhir kerja.
**3.5 Perencanaan Staf**

1.	Syahrul Gunawan	(Manager)
2.	Eko Prastyo	(Programer)
3.	Wulan Diani	(Sekretaris)

** Bab 4 Proses teknis ** 

**4.1 moteda , tools , dan teknik 

	4.1.1 Moteda 
	menguunakan Metoda standart UML ( Unified modeling Language ) digunakan untuk mendesain rancangan sistem dari aplikasi 

	4.1.2 tools 
	-

	4.1.2.1 Perangkat Keras `
		1. Laptop 

	4.1.2.2 Perangkat Lunak 
		1. Android studio 
			Android studio adalah lingkungan pengembangan terpadu
		Integrated Development Environment (IDE) untuk pengembangan aplikkasi Android, berdasarkan Intelli J IDEA . Selain merupakan editor kode IntelliJ dan alat pengembang yang berdaya guna, Android Studio menawarkan fitur lebih banyak untuk meningkatkan produktivitas  saat membuat aplikasi android , Misalnya : 
		* Sistem versi berbasis Gradle yang fleksible 
		* Emulator yang cepat dan kaya fitur
		* Lingkungan yang menyatu untuk pengembangan bagi semua perangkat Android
		* Instant Run untuk mendorong perubahan ke aplikasi yang berjalan tanpa membuat APK baru
		* Template kode dan integrasi GitHub untuk membuat fitur aplikasi yang sama dan mengimpor kode contoh
		* Alat pengujian dan kerangka kerja yang ekstensif
		* Alat Lint untuk meningkatkan kinerja, kegunaan, kompatibilitas versi, dan masalah-masalah lain
		* Dukungan C++ dan NDK
		* Dukungan bawaan untuk Google Cloud Platform, mempermudah pengintegrasian Google Cloud Messaging dan App Engine
**4.2 Dokumentasi perngkat lunak 

**4.3 Fungsi-fungsi pendukung proyek 

Sistem versi berbasis Gradle yang fleksibel

**BAB 5 Paket Pekerjaan, Jadwal, dan Budget**

	**5.1 Paket Pekerjaan**
	_________________________________________________________________________
	|    Nama 		 	| Jabatan  			| Modul 			| Pekerjaan  |
	--------------------------------------------------------------------------
	| Syahrul Gunawan  	| Project Manager   | 					|			 |
	--------------------------------------------------------------------------
	| Eko Prastyo   	| Programmer		| 					|			 |
	--------------------------------------------------------------------------
	| Wulan Diani   	| Design 			| 					|			 |
	--------------------------------------------------------------------------


	**5.2 Ketergatungan/Keterkaitan**

	**5.3 Kebutuhan sumber daya**
		Dibawah ini adalah kebutuhan-kebutuhan yang menunjang jalannya projek antara lain : 
											Jenis kebutuhan 					Alasan 
			Sumber Daya Manusia  			3 Orang anggota pekerja 			Mengajukan jumlah 
                                            Projek    							tersebut di 
                                            									dikarenakan agar keseimbangan antara pengerjaan projek, 
                                            									dokumen-dokumen dengan demikian kita dapat mempercepat
                                            									 proses pekerjaan projek.
            Sumber Daya Software  			Android Studio						Pegajuan Software  																	   
																				Android Studio dikarenakan pengerjaan projek melalui 
																				Java dan agar pengerjaan jauh lebih efisien daripada 
																				menggunakan 																			
            																	eclipse.
            								JDK(Java Development Kit)           Digunakan untuk pembuatan system android.
            Sumber Daya Hardware 			Perangkat Komputer   				Perangkat induk yang digunakan dalam pengerjaan projek.
            								Mobile								Sebagai Tester Aplikasi yang sudah dibuat.
											
	**5.4 Alokasi *budget* dan sumber daya**
	 No			Ketergatungan 		Satuan 			Jumlah Barang		Harga			Jumlah Harga
	1.			Gaji Anggota 			hari 			3				Rp 100.000,00 	Rp 300.000,00
	
	2.			WebBrowser				bh			 	1				Rp 20.0000,00	Rp 20.000,00

	3.			Android Studio ,JDK.	Set				1				Rp 50.000,00	Rp 50.000,00

	4.			SewaKomputer			Set				3x6				Rp 500.000,00	Rp 3.000.000,00
	JUMLAH BIAYA																		Rp 3.370.000,00

	**5.5 Jadwal**

	Pembuatan Aplikasi ini dimulai dari Bulan Febuari Sampai  Bulan April.
