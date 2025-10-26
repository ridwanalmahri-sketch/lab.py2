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
