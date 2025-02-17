# Aplilasi Kalkulator Sederhana
Kalkulator sederhana adalah alat elektronik atau perangkat lunak yang dirancang untuk melakukan operasi matematika dasar, seperti penjumlahan, pengurangan, perkalian, dan pembagian. Biasanya, kalkulator ini memiliki tampilan angka dan tombol untuk memasukkan angka serta memilih operasi yang diinginkan. Kalkulator sederhana sangat berguna untuk keperluan sehari-hari, seperti menghitung total belanja, atau menyelesaikan masalah matematika dasar lainnya. Meskipun fungsinya terbatas pada operasi dasar, kalkulator ini sangat efisien dan mudah digunakan oleh berbagai kalangan, dari pelajar hingga profesional.Aplikasi ini di buat untuk UKK RPL 2 pada 21 Februari 2025

# Fitur Kalkulator
1. Tampilan Hasil Perhitungan
Fitur: Menampilkan angka atau hasil perhitungan.
Penjelasan: Bagian atas kalkulator memiliki sebuah input field yang digunakan untuk menampilkan angka yang dimasukkan atau hasil perhitungan. Input ini hanya bisa dilihat (read-only) karena menggunakan atribut disabled. Pengguna dapat melihat ekspresi yang dimasukkan dan hasil akhir setelah perhitungan dilakukan.
2. Tombol Angka (0-9)
Fitur: Menambahkan angka ke tampilan kalkulator.
Penjelasan: Tombol angka dari 0 hingga 9 memungkinkan pengguna untuk memasukkan angka-angka yang ingin dihitung. Setiap angka yang ditekan akan muncul di tampilan kalkulator.
3. Tombol Operasi Matematika (+, -, x, /)
Fitur: Menambahkan operator matematika dasar.
Penjelasan: Tombol operasi ini memungkinkan pengguna untuk memilih operasi aritmatika yang diinginkan:
+ (Penjumlahan)
- (Pengurangan)
x (Perkalian)
/ (Pembagian)
Setelah memilih angka dan operator, pengguna dapat melanjutkan ke angka berikutnya atau menekan tombol "=" untuk menghitung hasilnya.
4. Tombol "C" (Clear All)
Fitur: Menghapus seluruh input di tampilan kalkulator.
Penjelasan: Tombol "C" digunakan untuk menghapus semua angka dan operator yang ada di tampilan kalkulator. Ini berguna jika pengguna ingin memulai perhitungan baru tanpa input sebelumnya mengganggu.
5. Tombol "Del" (Delete)
Fitur: Menghapus satu karakter terakhir dari tampilan.
Penjelasan: Tombol ini memungkinkan pengguna untuk menghapus satu karakter terakhir dari input yang dimasukkan di tampilan kalkulator. Jika pengguna memasukkan angka atau operator yang salah, mereka bisa menggunakan tombol "Del" untuk memperbaikinya dengan menghapus satu karakter saja.
6. Tombol "00"
Fitur: Menambahkan angka "00" ke tampilan.
Penjelasan: Tombol ini berguna untuk memasukkan angka "00", yang sering digunakan untuk memasukkan angka besar seperti 100 atau 1000. Ini memudahkan dalam mengetik angka dengan lebih cepat.
7. Tombol "=" (Sama Dengan)
Fitur: Menghitung hasil dari ekspresi yang ada di tampilan.
Penjelasan: Tombol ini digunakan untuk menghitung hasil dari ekspresi matematika yang telah dimasukkan oleh pengguna. Setelah angka dan operator dipilih dan tombol "=" ditekan, aplikasi akan menghitung dan menampilkan hasilnya di tampilan kalkulator. Proses ini dilakukan menggunakan fungsi eval(), yang mengeksekusi ekspresi matematika di dalam tampilan.
8. Validasi Input
Fitur: Menangani kesalahan input.
Penjelasan: Aplikasi memiliki mekanisme untuk menangani input yang tidak valid menggunakan blok try-catch pada fungsi hitunghasil(). Jika pengguna memasukkan ekspresi yang tidak dapat dihitung (misalnya, pembagian dengan nol atau karakter yang tidak valid), aplikasi akan memberikan peringatan berupa pesan "input tidak valid". Fitur ini membantu menghindari kegagalan aplikasi saat terjadi kesalahan perhitungan.
9. Desain Responsif
Fitur: Tampilan yang sesuai dengan berbagai perangkat.
Penjelasan: Aplikasi ini menggunakan meta tag viewport yang memastikan kalkulator ini dapat digunakan dengan baik di perangkat mobile maupun desktop. Tampilan kalkulator menyesuaikan lebar layar perangkat, sehingga pengguna dapat dengan mudah mengakses kalkulator di berbagai ukuran layar.
10. Desain dan Antarmuka Pengguna
Fitur: Tampilan visual yang menarik dan mudah digunakan.
Penjelasan: Kalkulator ini memiliki desain yang sederhana dan bersih dengan kombinasi warna emas, biru, hijau, dan pink untuk tombol. Desain ini memberikan kenyamanan visual bagi pengguna. Tombol-tombolnya cukup besar dan mudah dijangkau, menjadikannya nyaman untuk digunakan, terutama pada perangkat mobile.
11. Fitur Keamanan Sederhana
Fitur: Menggunakan eval() dengan pengecekan kesalahan.
Penjelasan: Walaupun menggunakan eval() untuk menghitung hasil perhitungan, aplikasi ini memiliki pengecekan untuk menangani ekspresi yang tidak valid, yang mencegah aplikasi menampilkan hasil yang salah atau menyebabkan kesalahan. Jika terjadi kesalahan input, aplikasi akan memberi tahu pengguna melalui alert.

# Panduan Pengguna
1. Menyalakan Aplikasi Kalkulator
Langkah 1: Buka aplikasi kalkulator di browser Anda. Anda akan melihat tampilan kalkulator yang memiliki tombol-tombol angka dan operator matematika di layar.
2. Memasukkan Angka
Langkah 2: Klik pada tombol angka (0-9) sesuai dengan angka yang ingin Anda masukkan.
Misalnya, jika Anda ingin memasukkan angka 5, cukup klik tombol angka 5.
Anda dapat memasukkan beberapa angka berturut-turut untuk membentuk angka yang lebih besar, seperti 25, 153, dan sebagainya.
3. Memilih Operator Matematika
Langkah 3: Klik tombol operator matematika (+, -, x, /) yang sesuai dengan operasi yang ingin Anda lakukan.
+ untuk penjumlahan.
- untuk pengurangan.
x untuk perkalian.
/ untuk pembagian.
Misalnya, jika Anda ingin menjumlahkan angka 5 dan 3, tekan tombol 5, kemudian tombol +, lalu tekan tombol 3.
4. Menggunakan Tombol "00"
Langkah 4: Jika Anda ingin menambahkan angka 00 (misalnya untuk 100 atau 1000), tekan tombol 00.
5. Menghitung Hasil
Langkah 5: Setelah memasukkan angka dan operator yang diinginkan, tekan tombol = untuk menghitung hasilnya.
Misalnya, jika Anda telah memasukkan ekspresi 5 + 3, klik tombol =, dan hasil 8 akan ditampilkan di tampilan kalkulator.
6. Menghapus Input
Langkah 6: Jika Anda ingin menghapus input atau perhitungan yang telah dimasukkan, Anda memiliki dua pilihan:
Tombol "C" (Clear All): Klik tombol C untuk menghapus seluruh input yang ada di tampilan kalkulator. Ini akan mengembalikan tampilan kalkulator ke keadaan kosong.
Tombol "Del" (Delete): Klik tombol Del untuk menghapus satu karakter terakhir dari input. Misalnya, jika Anda telah mengetik 123+, Anda bisa menekan tombol Del untuk menghapus satu karakter, seperti menghapus tanda +.
7. Menangani Kesalahan Input
Langkah 7: Jika Anda memasukkan ekspresi yang tidak valid atau salah (misalnya pembagian dengan nol atau karakter yang tidak sesuai), aplikasi akan memberi peringatan berupa pesan "input tidak valid". Anda dapat memperbaiki input dan mencoba lagi.
8. Mengulangi Perhitungan
Langkah 8: Setelah mendapatkan hasil perhitungan, Anda bisa melanjutkan perhitungan dengan memasukkan angka atau operator baru, atau menghapus hasil yang ada dan memulai perhitungan baru dengan menekan tombol C.
Contoh Penggunaan:
Contoh 1: Penjumlahan
Tekan tombol 2, kemudian tombol +, lalu tombol 3.
Tekan tombol =.
Hasil yang ditampilkan di tampilan kalkulator adalah 5.
Contoh 2: Perkalian
Tekan tombol 4, kemudian tombol x, lalu tombol 5.
Tekan tombol =.
Hasil yang ditampilkan adalah 20.
Contoh 3: Menghapus Input
Setelah memasukkan 8 + 2, jika Anda ingin menghapus +, tekan tombol Del.
Setelah itu, Anda bisa mengganti operator atau menambahkan angka lainnya.

