LANGKAH LANGKAH KONDISI_IF LATIHAN (1)
Judul: Klasifikasi Nilai Berdasarkan Angka
Tujuan: Memahami percabangan if–elif–else untuk menentukan nilai huruf.
Langkah-langkah:
1.	Buat folder kondisi_if dan file latihan1.py.
2.	Ketik kode:
3.	nilai = int(input("Masukkan nilai (0-100): "))
4.	if nilai >= 85:
5.	    print("Nilai A")
6.	elif nilai >= 70:
7.	    print("Nilai B")
8.	elif nilai >= 55:
9.	    print("Nilai C")
10.	else:
11.	    print("Nilai D (Perlu perbaikan)")
12.	Jalankan program, masukkan nilai (contoh: 78).
Penjelasan: Program menentukan kategori nilai berdasarkan kondisi yang diuji secara berurutan menggunakan if, elif, dan else.
KONDISI_IF LATIHAN (2)
Judul: Menentukan Bilangan Genap atau Ganjil
Tujuan: Menggunakan operator % dan percabangan if–else.
Langkah-langkah:
1.	Buat file latihan2.py di folder kondisi_if.
2.	Ketik kode:
3.	angka = int(input("Masukkan angka bulat: "))
4.	if angka % 2 == 0:
5.	    print(f"{angka} adalah bilangan genap")
6.	else:
7.	    print(f"{angka} adalah bilangan ganjil")
8.	Jalankan dan masukkan angka (contoh: 13).
Penjelasan: Program memeriksa apakah sisa pembagian angka dengan 2 adalah 0 (genap) atau bukan (ganjil).
LANGKAH LANGKAH PERULANGAN LATIHAN (1)
Judul: Menampilkan Deret Angka
Tujuan: Menerapkan perulangan for.
Langkah-langkah:
1.	Buat folder perulangan dan file latihan1.py.
2.	Ketik kode:
3.	n = int(input("Masukkan angka n: "))
4.	for i in range(1, n + 1):
5.	    print(i)
6.	Jalankan dan masukkan angka (contoh: 5).
Penjelasan: Program menampilkan deret angka dari 1 hingga n menggunakan perulangan for.
 PERULANGAN LATIHAN (2)
Judul: Menjumlahkan Angka dengan while
Tujuan: Memahami perulangan while dan penggunaan break.
Langkah-langkah:
1.	Buat file latihan2.py di folder perulangan.
2.	Ketik kode:
3.	total = 0
4.	while True:
5.	    angka = int(input("Masukkan angka (0 untuk selesai): "))
6.	    if angka == 0:
7.	        break
8.	    total += angka
9.	print("Total jumlah angka:", total)
10.	Jalankan dan masukkan beberapa angka, akhiri dengan 0.
Penjelasan: Program menjumlahkan semua angka yang dimasukkan hingga pengguna mengetik 0 untuk berhenti.



URAIAN LANGKAH LANGKAH CODING 1

Inisialisasi Harga Tiket dan Diskon Tetapkan nilai awal untuk harga tiket reguler (harga_reguler) sebesar Rp50,000 dan harga tiket VIP (harga_vip) sebesar Rp100,000. Tetapkan diskon member (diskon_member) sebesar 20% (0.2).

Meminta Input dari Pengguna Minta pengguna memasukkan tipe tiket yang diinginkan dengan input "reguler" atau "vip", lalu simpan hasil input dalam variabel tipe_tiket. Minta pengguna mengonfirmasi status keanggotaannya dengan input "ya" atau "tidak", dan simpan hasil input di variabel status_member.

Menentukan Harga Berdasarkan Tipe Tiket Cek apakah tipe_tiket yang dimasukkan pengguna adalah "vip". Jika benar, tetapkan total_harga ke nilai harga_vip. Jika salah, tampilkan pesan "Tipe tiket tidak valid." dan hentikan fungsi.

Menghitung Diskon untuk Member Jika pengguna memiliki kartu member (jika status_member adalah "ya"), kurangi total_harga dengan nilai diskon sebesar 20%. Menampilkan Total Harga Tampilkan hasil akhir yang menyatakan "Total harga yang harus dibayar" dengan format dua desimal untuk memudahkan pembacaan.

URAIAN LANGKAH LANGKAH CODING 2

Meminta Input dari Pengguna Program meminta pengguna untuk memasukkan dua angka yang akan digunakan dalam operasi aritmatika, yaitu angka1 dan angka2. Program meminta input operator aritmatika (+, -, *, atau /) yang akan digunakan pada kedua angka tersebut. Operator ini disimpan dalam variabel operator.

Mengecek Operator dan Melakukan Perhitungan Program kemudian mengecek operator yang dimasukkan pengguna: Jika operator adalah + (penjumlahan): Program menghitung hasil dari angka1 + angka2, lalu menampilkan hasil penjumlahan. Jika operator adalah - (pengurangan): Program menghitung hasil dari angka1 - angka2, lalu menampilkan hasil pengurangan. Jika operator adalah * (perkalian): Program menghitung hasil dari angka1 * angka2, lalu menampilkan hasil perkalian. Jika operator adalah / (pembagian): Program memeriksa apakah angka2 adalah nol (untuk menghindari pembagian oleh nol). Jika angka2 bukan nol, program menghitung angka1 / angka2 dan menampilkan hasil pembagian. Jika angka2 adalah nol, program menampilkan pesan error "Error: Pembagian dengan nol tidak diperbolehkan."

Penanganan Operator yang Tidak Valid Jika operator yang dimasukkan bukan salah satu dari +, -, *, atau /, program menampilkan pesan "Operator tidak valid. Silakan gunakan +, -, *, atau /" sebagai petunjuk bagi pengguna.

Menjalankan Fungsi Kalkulator Setelah seluruh kondisi diperiksa, fungsi kalkulator akan selesai dan menampilkan hasil atau pesan error sesuai dengan input pengguna.
