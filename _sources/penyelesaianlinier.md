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


### Tugas soal eliminasi gaus 
### contoh soal nomer 1 :

Diberikan sistem persamaan:

$$
x_1 + 2x_2 + 3x_3 = 6
$$
$$
2x_1 + 4x_2 + 6x_3 = 12
$$
$$
x_3 + x_2 = 2
$$

Kita akan menyelesaikannya menggunakan metode eliminasi Gauss. Pertama, kita tuliskan sistem ini dalam bentuk matriks augmented:

$$
\begin{bmatrix}
1 & 2 & 3 & | & 6 \\
2 & 4 & 6 & | & 12 \\
0 & 1 & 1 & | & 2
\end{bmatrix}
$$

Langkah 1: Eliminasi Baris

Langkah pertama adalah membuat elemen di bawah pivot (elemen pertama di kolom pertama) menjadi nol. Kita lakukan operasi berikut:

$$
R_2 \leftarrow R_2 - 2R_1
$$

Setelah melakukan perhitungan, kita mendapatkan:

$$
\begin{bmatrix}
1 & 2 & 3 & | & 6 \\
0 & 0 & 0 & | & 0 \\
0 & 1 & 1 & | & 2
\end{bmatrix}
$$

Dari hasil tersebut tidak diperlukan langkah selanjutnya karena elemen di bawah pivot sudah 1 kolom ke 2

Selanjutnya, menyelesaikan sistem persamaan 

dari persamaan 1 diperoleh: 

$$x_1 + x_2 + x_3 = 6$$

untuk persamaan 2 tidak diperoleh informasi karena 0=0

dari persamaan 3 diperoleh:

$$x_2 + x_3 = 2$$

dari persamaan 3 dapat diselesaikan untuk $x_2$:

$$x_2 = 2 - x_3$$

maka, untuk $x_2$ ini bisa disubtitusikan pada persamaan pertama, maka diperoleh:

$$x_1 + 2x_2 + 3x_3 = 6$$
$$x_1 + 2x_2 (2-x_3) + 3x_3 = 6$$
$$x_1 + 4-2x_3 + x_3 = 6$$
$$x_1 + 4 + x_3 = 6$$
$$x_1 = 6 - 4 - x_3$$
$$x_1 = 2 - x_3$$

kesimpulan solusi:
$$x_1 = 2- x_3$$
$$x_2 = 2 - x_3$$
$$x_3=x_3$$

untuk $x_3$ parameter bebas tidak ada yang membatasi.

### contoh soal nomer 2 :

$$
x_1 + x_2 + x_3 = 3
$$
$$
2x_1 + x_3 = 5
$$
$$
x_1 + 2x_2 = 3
$$

Kita akan menyelesaikannya menggunakan metode eliminasi Gauss. Pertama, kita tuliskan sistem ini dalam bentuk matriks augmented:

$$
\begin{bmatrix}
1 & 1 & 1 & | & 3 \\
2 & 0 & 1 & | & 5 \\
1 & 2 & 0 & | & 3
\end{bmatrix}
$$


Langkah 1: Eliminasi Baris

Langkah pertama adalah membuat elemen di bawah pivot (baris 2 kolom 1 dan baris 3 kolom 1) menjadi nol. Kita lakukan operasi berikut:

$$
R_2 \leftarrow R_2 - 2R_1
$$

$$R_3 \leftarrow R_3 - R_1$$

Setelah melakukan perhitungan, kita mendapatkan:

$$
\begin{bmatrix}
1 & 2 & 3 & | & 6 \\
0 & -2 & -1 & | & -1 \\
0 & 1 & -1 & | & 0
\end{bmatrix}
$$

selanjutnya jadikan 0 pada baris ke 3 kolom ke 2

$$R_3 \leftarrow R_3 + 1/2R_2$$

maka akan menjadi 

$$
\begin{bmatrix}
1 & 2 & 3 & | & 6 \\
0 & -2 & -1 & | & -1 \\
0 & 0 & -3/2 & | & -1/2
\end{bmatrix}
$$

selanjutnya rubah elemen baris ke 3 kolom ke 3 menjadi 1

$$R_3 \rightarrow -2/3R_3$$

maka menjadi

$$
\begin{bmatrix}
1 & 2 & 3 & | & 6 \\
0 & -2 & -1 & | & -1 \\
0 & 0 & 1 & | & 1/3
\end{bmatrix}
$$

langkah selanjutnya yaitu subtitusi:

dari persamaan 3 diperoleh:
$$x_3 = 1/3$$


dari persamaan 2 diperoleh:
$$-2x_2 - 1x_3 = -1$$


kita subtitusikan dari persamaan 3:
$$-2x_2 - 1x_3 = -1$$
$$-2x_2 - 1/3 = -1 $$
$$-2x_2 = -1 + 1/3 = -2/3$$
$$x_2 = -2/3 + 2$$
$$x_2 = 1/3$$

sekarang memiliki $x_2= 1/3$ dan $x_3= 1/3$ maka subtitusi di baris pertama, akan diperoleh


$$x_1 + x_2 + x_3 = 3$$
$$x_1 + 1/3 + 1/3 = 3$$
$$x_1 + 2/3 = 3$$
$$x_1 = 3 - 2/3$$
$$x_1 = 7/3$$

jadi, solusi penyelesaiannya adalah:

$$x_1 = 7/3$$
$$x_2= 1/3$$
$$x_3 = 1/3$$

<iframe src="https://www.geogebra.org/3d/m9uqkygu?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## contoh soal nomer 3 :

Diberikan sistem persamaan:

$$
2x_1 + 2x_2 = 4
$$
$$
x_1 + x_2 = 2
$$

Kita akan menyelesaikannya menggunakan metode eliminasi Gauss. Pertama, kita tuliskan sistem ini dalam bentuk matriks augmented:

$$
\begin{bmatrix}
2 & 2 & | & 4 \\
1 & 1 & | & 2
\end{bmatrix}
$$

Langkah pertama adalah membuat elemen di bawah pivot menjadi nol. Kita lakukan operasi berikut:

$$
R_1 \leftarrow R_1 - 2R_2
$$

Setelah melakukan perhitungan, kita mendapatkan:

$$
R_1: \quad 2 - 2 \cdot 1 = 0 \\
2 - 2 \cdot 1 = 0 \\
4 - 2 \cdot 2 = 0
$$

Sehingga, matriks augmented menjadi:

$$
\begin{bmatrix}
0 & 0 & | & 0 \\
1 & 1 & | & 2
\end{bmatrix}
$$

Dari baris kedua, kita dapat mengekspresikan \(x_1\) dalam bentuk \(x_2\):

$$
x_1 + x_2 = 2 \implies x_1 = 2 - x_2
$$

Karena kita memiliki satu persamaan dengan dua variabel, kita dapat menyatakan solusi dalam bentuk parameter. Misalkan \(x_2 = t\), maka:

$$
x_1 = 2 - t
$$

Jadi, solusi umum dari sistem persamaan ini adalah:

$$
\begin{cases}
x_1 = 2 - t \\
x_2 = t
\end{cases}
$$

di mana \(t\) adalah parameter bebas.

## contoh soal nomer 4 :

Diberikan sistem persamaan:

$$
x_1 + x_2 = 5
$$
$$
x_1 + 2x_3 = 6
$$

Kita akan menyelesaikannya menggunakan metode eliminasi Gauss. Pertama, kita tuliskan sistem ini dalam bentuk matriks augmented:

$$
\begin{bmatrix}
1 & 1 & 0 & | & 5 \\
1 & 0 & 2 & | & 6
\end{bmatrix}
$$

Langkah pertama adalah membuat elemen di bawah pivot (elemen pertama di kolom pertama) menjadi nol. Kita lakukan operasi berikut:

$$
R_2 \leftarrow R_2 - R_1
$$

Setelah melakukan perhitungan, kita mendapatkan:

$$
R_2: \quad 1 - 1 = 0 \\
0 - 1 = -1 \\
2 - 0 = 2 \\
6 - 5 = 1
$$

Sehingga, matriks augmented menjadi:

$$
\begin{bmatrix}
1 & 1 & 0 & | & 5 \\
0 & -1 & 2 & | & 1
\end{bmatrix}
$$

Selanjutnya, kita dapat menyelesaikan baris kedua untuk mengekspresikan \(x_2\) dalam bentuk \(x_3\):

$$
-1x_2 + 2x_3 = 1 \implies x_2 = 2x_3 - 1
$$

Sekarang kita substitusi \(x_2\) ke dalam persamaan pertama:

$$
x_1 + (2x_3 - 1) = 5
$$

Maka kita dapatkan:

$$
x_1 + 2x_3 - 1 = 5 \implies x_1 = 6 - 2x_3
$$

Karena kita memiliki dua persamaan dengan tiga variabel, kita dapat menyatakan solusi dalam bentuk parameter. Misalkan \(x_3 = p\), maka:

$$
x_1 = 6 - 2p
$$
$$
x_2 = 2p - 1
$$
$$
x_3 = p
$$

Jadi, solusi umum dari sistem persamaan ini adalah:

$$
\begin{cases}
x_1 = 6 - 2p \\
x_2 = 2p - 1 \\
x_3 = p
\end{cases}
$$

di mana \(p\) adalah parameter bebas.



