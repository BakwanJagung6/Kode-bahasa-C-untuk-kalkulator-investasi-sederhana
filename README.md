# Kode-bahasa-C-untuk-kalkulator-investasi-sederhana
Kode bahasa C untuk kalkulator investasi sederhana

## Identitas Mahasiswa
-	Nama: Dava Algafiri Sidiq
-	NIM:  2404297
-	Kelas: 2B PSTI

## Identitas Kakak Tingkat
-	Nama: Rochaman Bambang Eko Saputro 
-	Angkatan: 2022
-	Program Studi: PSTI

# Mini Proyek – Coding untuk Kakak Tingkat

## Permintaan Program
“nih lu pilih ajaa, mau kalkulator investasi apa rute kereta tercepat.”  
Saya Memilih membuat program kalkulator investasi.
“nah, cari dulu tuh investasi jenis nya apa aja”
“misal kamu mau ambil 3 jenis”
“deposito, saham, reksa dana atau emas sekalian”
“masing-masing berapa keuntungan nya per tahun”
“misal deposito itu dapet bunga 6% per tahun”
“nanti kita bisa masukin jumlah nya misal 100.000, nah trus kita mau berapa lama gitu dalam bulan misal 24 bulan”
“nanti baru keluar jumlah uang kita nambah berapa (keuntungan nya) sama total uang nya jadi berapa”

## Penjelasan Program
Bahasa pemrograman yang digunakan: C
Fitur utama:
-	Kalkulator Investasi, program menyediakan perhitungan investasi seperti deposito, saham, reksadana, dan emas.
-	Setiap kalkulator meminta pengguna untuk menginput seperti modal awal, investasi bulanan, dan harga emas. Validasi input seperti hanya nilai dengan angka positif yang dapat diproses oleh program.
-	Perhitungan otomatis hasil investasi, program mengitung hasil akhir sesuai dengan setiap tipe kalkulator.
-	Output bisa berbeda satu sama lain tergantung kepada fitur kalkulator mana yang dipakai oleh pengguna.
-	Fitur penarikan deposito sebelum jatuh tempo, menjadi fitur yang uni dalam program ini terutama pada kalkulator depostio dimana pengguna dapat melakukan penarikan sebelum tenor terakhir, dan program juga akan menghitung denda serta bunga yang didapat.
Konsep yang digunakan:
-	Input/Output, program menerima input dari pengguna menggunakan scanf dan menampilkan hasil perhitungan menggunakan printf. Contoh penggunaannya seperti berikut:
“ printf(“Masukkan Deposito Awal: Rp”); ”
“ scanf(“%d, &danaAwal); ”
-	Variabel, program menggunakan berbagai variable untuk menyimpan data input, hasil perhitungan, dan parameter investasi. Contoh penggunaannya seperti berikut: 
“ double bungaSebelumPajak, bungaSetelahPajak, pajakBunga, total; ”
“ int danaAwal, tenor, bulanBerjalan; ”
-	If-Else, percabangan digunakan untuk memproses logika berdasarkan input pengguna.
Contoh penggunaannya seperti berikut:
“if (yatidak == ‘Y’ || yatidak == ‘y’){“
“ // kode blok “
“ } else if (yatidak == ‘N’ || yatidak == ‘n’){ “
“ } else { “
“ printf(“Input tidak valid. Tolong Pilih Y atau N\n”); “
“ } “
-	Loop, perulang digunakan sebagai validasi input, agar program hanya dapat menerima data yang benar. Contoh penggunaannya seperti berikut:
“ while (scanf(“%d”, &danaAwal ) != 1 || danaAwal <= 0){ “
“    printf(“Input tidak valid! Masukkan angka positif: “); “
“    while(getchar() != ‘\n’); “
“ } “
-	Fungsi, setiap jenis investasi dibuatkan fungsinya masing-masing agar kode lebih mudah dipahami. Contoh penggunannya seperti berikut:
“ Void kalkulatorDeposito() “
“ Void kalkulatorSaham() “
“ Void kalkulatorReksadana() “
“ Void kalkulatorEmas() “
-	Array, pada program ini terdapat array Bernama counterInvestasi yang digunakn untuk mencatat statistic pengguna setiap penggunaan kalkulator investasi. Contoh penggunaan seperti berikut:
“ int counterInvestasi[4] = {0, 0, 0, 0}; “

## Link video Demo
https://youtu.be/GdRREeKnVls

 

