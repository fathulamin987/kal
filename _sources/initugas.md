# Tugas

Dari slide yang Anda lampirkan, soal yang dimaksud adalah membuktikan bahwa transformasi linier rotasi di bidang 2 dimensi (rotasi dalam 
𝑅
2
R 
2
 ) dengan matriks:

𝐴
=
[
cos
⁡
𝜃
−
sin
⁡
𝜃
sin
⁡
𝜃
cos
⁡
𝜃
]
A=[ 
cosθ
sinθ
​
  
−sinθ
cosθ
​
 ]
merupakan transformasi rotasi berlawanan arah jarum jam sebesar sudut 
𝜃
θ.

Bukti:
Misalkan suatu vektor 
𝑣
=
(
𝑥
,
𝑦
)
v=(x,y) dalam koordinat kartesian. Kita dapat menyatakannya dalam koordinat polar sebagai:

𝑣
=
(
𝑥
,
𝑦
)
=
(
𝑟
cos
⁡
𝛼
,
𝑟
sin
⁡
𝛼
)
v=(x,y)=(rcosα,rsinα)
dengan:

𝑟
=
∥
𝑣
∥
r=∥v∥ (panjang vektor),

𝛼
α adalah sudut antara vektor 
𝑣
v dengan sumbu-x positif.

Transformasi 
𝐴
A bertindak pada 
𝑣
v sebagai berikut:

𝐴
⋅
𝑣
=
[
cos
⁡
𝜃
−
sin
⁡
𝜃
sin
⁡
𝜃
cos
⁡
𝜃
]
[
𝑟
cos
⁡
𝛼
𝑟
sin
⁡
𝛼
]
=
𝑟
[
cos
⁡
𝜃
cos
⁡
𝛼
−
sin
⁡
𝜃
sin
⁡
𝛼
sin
⁡
𝜃
cos
⁡
𝛼
+
cos
⁡
𝜃
sin
⁡
𝛼
]
A⋅v=[ 
cosθ
sinθ
​
  
−sinθ
cosθ
​
 ][ 
rcosα
rsinα
​
 ]=r[ 
cosθcosα−sinθsinα
sinθcosα+cosθsinα
​
 ]
Gunakan identitas trigonometri:

cos
⁡
(
𝛼
+
𝜃
)
=
cos
⁡
𝛼
cos
⁡
𝜃
−
sin
⁡
𝛼
sin
⁡
𝜃
sin
⁡
(
𝛼
+
𝜃
)
=
sin
⁡
𝛼
cos
⁡
𝜃
+
cos
⁡
𝛼
sin
⁡
𝜃
cos(α+θ)=cosαcosθ−sinαsinθ
sin(α+θ)=sinαcosθ+cosαsinθ
Sehingga:

𝐴
⋅
𝑣
=
𝑟
(
cos
⁡
(
𝛼
+
𝜃
)
,
sin
⁡
(
𝛼
+
𝜃
)
)
A⋅v=r(cos(α+θ),sin(α+θ))
Artinya, vektor hasil adalah vektor dengan panjang yang sama (karena rotasi mempertahankan panjang), dan sudut terhadap sumbu-x sebesar 
𝛼
+
𝜃
α+θ, yaitu berputar berlawanan arah jarum jam sebesar 
𝜃
θ.

Kesimpulan:
Transformasi linier dengan matriks rotasi 
𝐴
A tersebut memang merepresentasikan rotasi sebesar sudut 
𝜃
θ berlawanan arah jarum jam di bidang 
𝑅
2
R 
2
 .