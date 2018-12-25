# Marwah-Zulfanny-Alief_Indira-Insiyah_Final-Project
Program Aplikasi Ojek dengan bahasa C
Oleh Kelompok 16
Marwah Zulfanny Alief_1706986025
Indira Insiyah Nastiti_1706986006

Deskripsi: Final Project 2 Proglan merupakan pengembangan lebih lanjut dari program Yogs Gojekin Ajs Brads di Final Project 1 Proglan, dimana program ini merupakan sebuah aplikasi. Aplikasi Ojekin Ajs Brads merupakan aplikasi jasa Transportasi Online yang menyediakan tiga fungsi Ojek media transportasi atau mobilisasi yang disebut KuyJek, media pemesanan makanan dan minuman yang disebut KanJek, serta media pemesanan tiket bioskop, yaitu KetJek.
Fitur yang terdapat pada Aplikasi kami, yaitu sebagai berikut

I. KuyJek : Fitur KuyJek merupakan program pemesanan Ojek untuk berpergian dari satu tempat ke tempat lain di dalam Universitas Indonesia. Tempat-tempat tersebut dibagi menjadi 4 zona yang berbeda. Sehingga, tarif yang dikenakan sesuai dengan banyaknya zona yang ditempuh.

II. KanJek : Fitur ini berfungsi untuk memesan makanan maupun minuman dari enam restoran berbeda. Program menampilkan keenam menu makanan dan minuman dari restoran-restoran tersebut. User dapat memilih makanan dan minuman sesuai keinginan dan dapat membayar menggunakan Saldo KanJek, yaitu fitur yang bekerja sebagai bentuk E-money pada aplikasi kami.

III. KetJek : Fitur Ketjek adalah program pemesanan tiket bioskop di empat mall bioskop berbeda. Program akan menampilkan film-film yang berbeda di setiap bioskop. User dapat memilih film dan jadwal pemutaran sesuai keinginan.

IV. About : Fitur tersebut berfungsi untuk menjelaskan kepada User mengenai fungsi dan manfaat aplikasi kami.

V. Help : Fitur ini berfungsi untuk membantu User dalam memahami dan menggunakan aplikasi kami. Beirkut ini merupakan langkah-langkah menggunakan aplikasi Ojekin Ajs Brads: a. user memilih fasilitas yang akan digunakan (Kuyjek/Kanjek/Ketjek) b. user memilih jarak (Kuyjek), resto (Kanjek), dan mall(Ketjek) yang diinginkan c. user memilih menu yang ditampilkan d. user memesan e. user menerima pesanan f. warning : user salah menginput angka sesuai pilihan g. about : penjelasan tentang program h. help : penjelasan mekanisme berjalannya program i. logout : keluar dari akun program, seluruh history akan dihapus j. exit : menu untuk keluar dari program

VI. Log Out : Fitur ini berfungsi untuk keluar dari akun program secara permanen, sehingga data-data yang ada akan dihapus seluruhnya termasuk e-money

VII. Exit : Menu untuk keluar dari program.

Variasi Menu dan Background yang disediakan program ini tidak menjenuhkan dan selain itu pengguna dapat bebas menentukan apasaja yang dikehendakinya dalam program sesuai dengan pilihan yang ada.

Pada program terdapat implementasi pointer untuk menunjukkan jumlah pemakaian/order history dari user terhadap program kami serta sebagai fitur E-money penyimpan saldo user (ADDITONAL FITUR) juga implementasi untuk user dapat keluar dari akun program dengan mudah sehingga data privasi dapat dijaga dengan aman. Program juga menggunakan implementasi fungsi modular agar memudahkan dan menyederhanakan source code. Pada fungsi modular KuyJek, kami menggunakan array 2 dimensi untuk menentukan zona dari suatu tempat sehingga, terbentuk tabel berupa hubungan antara tempat jemput/tempat tujuan dengan zona. Juga struct untuk penulisan nama tempat pada fungsi modular bill. Pada fungsi modular KanJek, kami menggunakan array 1 dimensi untuk data harga makanan dan minuman dari setiap restoran. Pada modular ini terdapat implementasi pointer untuk menunjukkan jumlah uang atau saldo user yang dapat digunakan untuk membayar pesanan. Saldo tersebut juga dapat ditambahkan(top-up). Pada modular fungsi KetJek, program menggunakan implementasi struct untuk data jadwal film, penulisan nama film dan mall pada fungsi modular bill. Program ini didesign sangat fleksibel, membuat user dapat memilih pilihan sesuai kehendaknya (memilih, kembali ke menu sebelumnya ataupun mengakhiri program). Pemrogram membuat fitur ini murni berasal dari inspirasi diri dan pengaplikasian modul-modul pembelajaran perkulian Pemrograman Lanjut. Program ini kami buat mengacu pada imajinasi diri dan keserupaan aplikasi Gojek namun dalam bentuk penerapan Bahasa C. Kami tidak mengambil sumber manapun dari internet dalam mencontoh program kecuali mengenai teori-teori fungsi yang ada dalam Bahasa C untuk penerapan program kami.
