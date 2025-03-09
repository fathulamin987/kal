# Penyelesaian Sistem persamaan Linier
## Menyelesaikan Sistem Persamaan Linear menggunakan Eliminasi

pembelajaran:

• Memahami Konsep dasar Operasi Baris Elementer.

• Mengetahui Tiga jenis operasi baris elementer.

• Mengetahui Aplikasi OBE dalam aljabar linear.

• Mengetahui Algoritma Eliminasi Gauss


> Matriks adalah kumpulan bilangan yang disusun dalam baris dan kolom.


Tiga operasi baris elementer :
1. Menukar Dua Baris
2.Mengalikan baris dengan skalar non-nol
3.Menambahkan Kelipatan Satu Baris ke Baris Lain


*Bentuk Eselon Baris dan Eselon Baris Tereduksi :*

*Bentuk Eselon Baris:*

• Baris nol berada di bawah baris non-nol.

• Elemen pivot (elemen pertama non-nol pada suatu baris) berada di kanan elemen pivot baris sebelumnya.


*Bentuk Eselon Baris Tereduksi:*

• Memenuhi semua syarat bentuk eselon baris.

• Setiap elemen pivot bernilai 1.

• Kolom yang mengandung elemen pivot hanya memiliki satu elemen non-nol (yaitu pivot).


> OBE : Operasi baris elementer

*Aplikasi operasi baris elementer :*
• Menyelesaikan system persamaan linier
Menggunakan eliminasi gauss atau gauss-

• Mencari invest matriks
Menggabungkan matriks dengan matriks identitas dan melakukan

• Menghitung determinan
Menggunakan reduksi baris untuk menyederhanakan perhitungan determinan.


> Kofiseien : nilai yang melekat pada suatu variable


> ### Eliminasi gauss
> adalah metode yang digunakan untuk menyelesaikan sistem persamaan linear. Metode ini mengubah sistem persamaan linear ke dalam bentuk yang lebih mudah dipecahkan, biasanya dalam bentuk segitiga atas, dan kemudian menggunakan substitusi mundur untuk menemukan solusi.

Langkah-langkah Eliminasi Gauss :
1. Penyusunan Matriks Augmented
Sistem persamaan linear diubah menjadi matriks augmented. Misalnya, untuk sistem persamaan berikut:

2. Transformasi ke Bentuk Segitiga Atas
Proses utama dalam eliminasi Gauss adalah membuat matriks menjadi matriks segitiga atas, yaitu bentuk di mana semua elemen di bawah diagonal utama menjadi nol. Ini dicapai dengan melakukan operasi baris elementer, yang meliputi:

• Pertukaran baris (swap rows),

• Perkalian baris dengan konstanta (scaling a row),

• Penjumlahan atau pengurangan kelipatan baris (adding/subtracting multiples of one row to another).

Misalnya, kita akan mengubah elemen-elemen di bawah diagonal utama menjadi nol dengan cara mengganti baris menggunakan operasi aritmatika pada baris-baris yang ada.

3. Substitusi Mundur
Setelah kita mendapatkan matriks dalam bentuk segitiga atas, kita dapat menggunakan substitusi mundur untuk menemukan solusi sistem persamaan. Proses substitusi mundur dimulai dari persamaan terakhir, dan solusi ditemukan secara bertahap dengan menggantikan nilai-nilai yang telah ditemukan ke persamaan sebelumnya.


> ### Eliminasi Gauss-Jordan 
> adalah metode untuk menyelesaikan sistem persamaan linear dengan mengubah matriks augmented menjadi bentuk matriks identitas di sisi kiri. Setelah itu, solusi sistem langsung dapat dibaca dari kolom kanan.

Langkah-langkah:

1. Penyusunan Matriks Augmented: Gabungkan matriks koefisien dan hasilnya menjadi matriks augmented.

2. Membuat Elemen Diagonal Menjadi 1: Kalikan baris dengan faktor yang sesuai agar elemen diagonal utama menjadi 1.

3. Membuat Elemen Selain Diagonal Menjadi Nol: Gunakan operasi baris elementer (penjumlahan atau pengurangan kelipatan baris) untuk membuat semua elemen selain diagonal utama menjadi nol.

4. Hasil: Setelah matriks diubah menjadi bentuk identitas di sisi kiri, solusi sistem dapat langsung dibaca di sisi kanan.