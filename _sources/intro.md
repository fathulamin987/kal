# Komputasi Aljabar Linier

#### sistem linier
sistem linier adalah sistem yang beroperasi dengan cara yang proporsional dan terukur, di mana perubahan pada input menghasilkan perubahan yang sebanding pada output.

#### Persamaan linier
Persamaan linier adalah persamaan matematika yang menggambarkan hubungan antara variabel yang memiliki pangkat tertinggi 1 (linear)

Contoh persamaan linier dengan satu variabel adalah :
*2𝑥+ 3 = 7*

Contoh persamaan dengan dua variabel, seperti :
*3𝑥 + 4𝑦 =12*

𝑥 dan 𝑦 tersebut adalah variabel, dan grafiknya akan membentuk garis lurus di bidang koordinat dua dimensi.

#### Sistem persamaan linier
Sistem persamaan linier adalah kumpulan dua atau lebih persamaan linier yang melibatkan variabel yang sama.

 contoh sebuah sistem persamaan linier dengan dua variabel bisa berbentuk seperti ini:


2𝑥+3𝑦=8

4𝑥−𝑦=2

​
 
Dalam contoh ini, kita memiliki dua persamaan linier yang melibatkan dua variabel, 
𝑥 dan 𝑦 Sistem ini mencari nilai-nilai 𝑥 dan 𝑦 yang memenuhi kedua persamaan sekaligus.

##### penyelesaian tunggal
Penyelesaian tunggal berarti ada satu nilai unik ( terdapat hanya satu solusi yang memenuhi semua persamaan dalam sistem tersebut ) 𝑥 dan 𝑦 yang membuat kedua persamaan ini benar pada saat bersamaan.

Contoh :

2𝑥+3=8

4𝑥−𝑦=2


<iframe scrolling="no" title="Simultaneous Equations:Elimination" src="https://www.geogebra.org/material/iframe/id/MXa3HKy3/width/977/height/574/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" width="977px" height="574px" style="border:0px;"> </iframe>

![plot](penyelesaian_tunggal.png)
​
 

##### Tidak memiliki penyelesaian
 dalam sistem persamaan linier terjadi ketika sistem tersebut bertentangan, yang berarti tidak ada kombinasi nilai variabel yang dapat memenuhi semua persamaan dalam sistem tersebut secara bersamaan.

 Contoh :
 
2𝑥+3𝑦=6

4𝑥+6𝑦=15


<iframe scrolling="no" title="Simultaneous Equations:Elimination" src="https://www.geogebra.org/material/iframe/id/MXa3HKy3/width/977/height/574/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" width="977px" height="574px" style="border:0px;"> </iframe>
​

![plot](no/solusi.png)
 
Jika kita mencoba menyelesaikan sistem ini, kita akan melihat bahwa kedua persamaan ini saling bertentangan. Dalam hal ini, meskipun koefisien dari 𝑥 dan 𝑦 dalam kedua persamaan tampak berhubungan, konstanta di sisi kanan berbeda, yang berarti kedua garis akan berparalel dan tidak akan berpotongan.

##### Memiliki banyak penyelesaian
disebut memiliki banyak penyelesaian dikarenakan semua persamaan dalam sistem tersebut menggambarkan hubungan yang sama, sehingga tidak ada batasan unik untuk nilai variabel. Dalam hal ini, solusi sistem tersebut bukan hanya satu titik, melainkan seluruh himpunan titik yang terletak pada satu garis atau lebih (tergantung pada jumlah variabel dalam sistem).

Contoh : 

𝑥+2𝑦=4

<iframe scrolling="no" title="Simultaneous Equations:Elimination" src="https://www.geogebra.org/material/iframe/id/MXa3HKy3/width/977/height/574/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" width="977px" height="574px" style="border:0px;"> </iframe>


![plot](banyak_penyelesaian.png)

Jika kita melihat persamaan kedua, kita dapat melihat bahwa persamaan kedua sebenarnya adalah kelipatan dua dari persamaan pertama. Oleh karena itu, kedua persamaan ini menggambarkan garis yang sama dalam sistem koordinat, yang berarti sistem ini memiliki tak terhingga banyak solusi (seluruh garis tersebut adalah solusi).

# contoh soal eliminasi gaus 

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

### contoh soal nomer 1 sistem persamaan:


Contoh Soal 1

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

### Langkah 1: Eliminasi Baris

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

### contoh soal nomer 2 sistem persamaan:

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


### Langkah 1: Eliminasi Baris

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
