LANGKAH LANGKAH KONDISI_IF LATIHAN(1)

Klasifikasi Nilai Berdasarkan Angka

Tujuan:

Memahami penerapan struktur percabangan if, elif, dan else.

Mengelompokkan nilai angka ke dalam kategori huruf (A, B, C, D).

Langkah-langkah:

Buka editor Python (seperti IDLE, Thonny, atau VS Code).

Buat folder baru bernama kondisi_if.

Buat file Python dengan nama latihan1.py.

Masukkan kode berikut:
nilai = int(input("Masukkan nilai (0-100): "))

if nilai >= 85:
    print("Nilai A")
elif nilai >= 70:
    print("Nilai B")
elif nilai >= 55:
    print("Nilai C")
else:
    print("Nilai D (Perlu perbaikan)")
    print("Nilai D (Perlu perbaikan)")
Simpan dan jalankan program.

Saat diminta, masukkan nilai (contohnya: 78) dan amati hasilnya di layar.

Penjelasan Program:
Program membaca input angka dari pengguna.

Dengan struktur if–elif–else, sistem memeriksa kondisi dari atas ke bawah.

Setiap kondisi menentukan rentang nilai tertentu dan mencetak kategori huruf yang sesuai.

Jika semua kondisi tidak terpenuhi, bagian else akan dijalankan.
LANGKAH LANGKAH KONDISI_IF LATIHAN (2)
Menentukan Bilangan Genap atau Ganjil

Tujuan:

Mempelajari penggunaan operator modulus % untuk pemeriksaan kondisi numerik.

Menggunakan pernyataan if–else untuk menentukan jenis bilangan (genap atau ganjil).

Langkah-langkah:

Buka folder kondisi_if.

Buat file baru dengan nama latihan2.py.

Masukkan kode berikut:

angka = int(input("Masukkan angka bulat: "))

if angka % 2 == 0:
    print(f"{angka} adalah bilangan genap")
else:
    print(f"{angka} adalah bilangan ganjil")


Simpan dan jalankan file tersebut.

Masukkan angka (contoh: 13) untuk melihat hasilnya.

Penjelasan Program:

Operator % digunakan untuk mendapatkan sisa hasil bagi dari pembagian dua angka.

Jika angka % 2 bernilai 0, maka bilangan tersebut genap.

Jika hasilnya bukan 0, maka bilangan tersebut tergolong ganjil.

LANGKAH LANGKAH PERULANGAN LATIHAN(1)
Langkah-langkah:

Buka folder perulangan di dalam repository labpy2.

Buat file baru bernama latihan1.py.

Ketik kode berikut:

# latihan1.py - menampilkan deret angka
n = int(input("Masukkan angka n: "))

for i in range(1, n + 1):
    print(i)


Simpan dan jalankan program.

Saat diminta, masukkan angka, misalnya 5.

Amati hasil output di layar.

PERULANGAN LATIHAN(2)
Judul:

Menjumlahkan Angka dengan Perulangan while

Tujuan:

Memahami konsep perulangan while.

Menggunakan while untuk menjumlahkan angka yang diinput pengguna hingga nilai tertentu (0).

Langkah-langkah:

Buka folder perulangan.

Buat file baru dengan nama latihan2.py.

Ketik kode berikut:

# latihan2.py - menjumlahkan angka dengan while
total = 0

while True:
    angka = int(input("Masukkan angka (0 untuk selesai): "))
    if angka == 0:
        break
    total += angka

print("Total jumlah angka:", total)


Simpan dan jalankan program.

Masukkan beberapa angka, kemudian ketik 0 untuk mengakhiri input.
Contoh:

Masukkan angka (0 untuk selesai): 5
Masukkan angka (0 untuk selesai): 3
Masukkan angka (0 untuk selesai): 2
Masukkan angka (0 untuk selesai): 0


Output akan menampilkan hasil penjumlahan semua angka yang dimasukkan.

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
