# Proyek-Array-C-C2583207055
Sistem Monitoring Stok dan Penjualan Kantin Kampus merupakan aplikasi berbasis console yang dibuat menggunakan bahasa pemrograman C. Program ini bertujuan untuk membantu pengelola kantin dalam mengelola data produk, memantau ketersediaan stok, serta mencatat transaksi penjualan agar lebih mudah dan teratur. Aplikasi ini dibuat sebagai solusi sederhana untuk mengurangi kesulitan dalam pencatatan stok dan perhitungan penjualan yang sebelumnya dilakukan secara manual.Program ini memiliki beberapa fitur, seperti menampilkan dan menambahkan produk, mengubah harga dan stok, melakukan transaksi penjualan, mencari serta mengurutkan produk, dan menampilkan laporan penjualan. Dalam pembuatannya, program menerapkan array satu dimensi dan array karakter dua dimensi sebagai tempat penyimpanan data, serta menggunakan percabangan, perulangan, dan fungsi. Dengan adanya program ini, diharapkan pengelolaan stok dan penjualan kantin kampus menjadi lebih praktis, terstruktur, dan mudah dilakukan.
# Identitas Mahasiswa
Nama: Nabil Muhammad Rivan 
NIM:  C2583207055
Kelas: PTI 3A
Mata Kuliah: Algoritma dan Pemrograman Lanjutan
Dosen Pengampu: Taofik Muhammad, M.Kom
# Fitur Program
1. Menampilkan daftar produk.
2. Menambahkan produk baru.
3. Mengubah harga dan stok produk.
4. Melakukan transaksi penjualan beberapa produk.
5. Menambahkan stok produk.
6. Mencari produk berdasarkan nama.
7. Mengurutkan produk berdasarkan harga dan jumlah terjual.
8. Menampilkan laporan penjualan.
9. Mengecek stok produk yang kurang dari 5.
# Penerapan Array
Pada program Sistem Monitoring Stok dan Penjualan Kantin Kampus, array digunakan sebagai tempat untuk menyimpan dan mengelola seluruh data produk. Program ini menggunakan dua jenis array, yaitu array satu dimensi dan array karakter dua dimensi. Array karakter dua dimensi digunakan untuk menyimpan nama produk dengan deklarasi char namaProduk[50][50];. Artinya, program dapat menyimpan maksimal 50 nama produk dengan panjang maksimal 50 karakter untuk setiap nama produk.
Selain itu, program menggunakan array satu dimensi untuk menyimpan informasi setiap produk, yaitu int harga[50]; untuk menyimpan harga produk, int stok[50]; untuk menyimpan jumlah persediaan barang, dan int jumlahTerjual[50]; untuk mencatat jumlah produk yang sudah terjual. Setiap array menggunakan indeks yang sama sehingga data nama, harga, stok, dan jumlah terjual saling berhubungan. Sebagai contoh, indeks ke-0 digunakan untuk menyimpan seluruh informasi produk pertama, indeks ke-1 untuk produk kedua, dan seterusnya.
Program juga menggunakan variabel jumlahProduk untuk mengetahui jumlah produk yang sudah dimasukkan ke dalam array. Kapasitas maksimal yang disediakan adalah 50 produk. Ketika pengguna menambahkan produk baru, jumlah data akan bertambah, sedangkan ketika melakukan transaksi penjualan, stok produk akan berkurang dan jumlah produk terjual akan bertambah. Dengan penerapan array tersebut, pengelolaan data menjadi lebih teratur dan memudahkan program dalam menjalankan fitur penambahan produk, perubahan harga dan stok, transaksi penjualan, pencarian, pengurutan, serta laporan penjualan.
# Cara Menjalankan Program
Program Sistem Monitoring Stok dan Penjualan Kantin Kampus dibuat menggunakan bahasa pemrograman C dan dapat dijalankan melalui terminal atau Command Prompt dengan bantuan compiler GCC. Sebelum menjalankan program, pengguna harus memastikan bahwa GCC sudah terpasang pada komputer serta file source code yang digunakan sudah tersedia dengan nama main.c.
Langkah pertama adalah membuka folder proyek yang berisi file main.c menggunakan Visual Studio Code atau Command Prompt. Setelah itu, buka terminal dan periksa apakah compiler GCC sudah tersedia dengan mengetik perintah gcc --version. Jika informasi versi GCC muncul, berarti compiler sudah siap digunakan.
Selanjutnya, lakukan proses kompilasi dengan mengetik perintah gcc main.c -o kantin pada terminal. Perintah tersebut digunakan untuk menerjemahkan kode program bahasa C menjadi file yang dapat dijalankan. Jika proses kompilasi berhasil tanpa menampilkan kesalahan, program sudah siap dijalankan.
Untuk pengguna Windows, jalankan program dengan mengetik perintah kantin.exe, sedangkan pengguna Linux atau macOS dapat menggunakan perintah ./kantin. Setelah program berhasil dijalankan, menu utama Sistem Monitoring Stok dan Penjualan Kantin Kampus akan muncul pada layar terminal. Pengguna dapat memilih menu sesuai kebutuhan, seperti melihat daftar produk, menambahkan produk, mengubah data produk, melakukan transaksi penjualan, menambahkan stok, mencari produk, mengurutkan data, melihat laporan penjualan, dan mengecek stok yang menipis.
Dengan mengikuti langkah-langkah tersebut, pengguna dapat menjalankan dan menggunakan seluruh fitur program melalui terminal atau Command Prompt.
# Dokumentasi Pengujian
# Pengujian 1 – Tambah Produk
Produk baru berhasil ditambahkan dan muncul dalam daftar produk.
<img width="685" height="393" alt="Screenshot 2026-11-17 210704" src="https://github.com/user-attachments/assets/a904b139-16b2-4c89-babc-a16263d421d8" />
# Pengujian 2 – Transaksi
Program berhasil menghitung subtotal dan total pembayaran beberapa produk.
<img width="703" height="402" alt="Screenshot 2026-11-17 211112" src="https://github.com/user-attachments/assets/2bad6fff-f905-4579-9d1f-fe50230ad07d" />
# Pengujian 3 – Pembaruan Stok
Stok produk berkurang dan jumlah produk terjual bertambah setelah transaksi berhasil.
<img width="685" height="405" alt="Screenshot 2026-11-17 211321" src="https://github.com/user-attachments/assets/16fb2ee6-b0b1-48d8-995c-7852a5f744f9" />
# Pengujian 4 – Stok Tidak Cukup
Program menolak pembelian yang melebihi stok tersedia.
<img width="687" height="399" alt="Screenshot 2026-11-17 211539" src="https://github.com/user-attachments/assets/097cbda2-e6eb-4878-ba42-46621084dda8" />
# Pengujian 5 – Laporan Penjualan
Program menampilkan jumlah unit terjual, total pendapatan, dan produk terlaris.
<img width="690" height="400" alt="Screenshot 2026-11-17 211637" src="https://github.com/user-attachments/assets/7457fd95-09fb-40a1-afef-dd1e49021451" />
# Pengujian 6 – Pengurutan
Program berhasil mengurutkan produk berdasarkan harga dari yang terkecil sampai terbesar
<img width="692" height="404" alt="Screenshot 2026-11-17 211757" src="https://github.com/user-attachments/assets/6afddd13-1d35-48d2-bc55-7f83a74fca79" />
# Pengujian 7 – Pencarian dan Stok Menipis
Program berhasil mencari produk berdasarkan nama dan menampilkan produk dengan stok kurang dari 5.
<img width="696" height="407" alt="Screenshot 2026-11-17 213414" src="https://github.com/user-attachments/assets/3f51d383-aa8e-486d-be47-8f01d5dd8fb2" />
