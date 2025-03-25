---
title: Tugas 3 Persamaan dengan 3 var

---

### **Tugas 3 Persamaan 3 Variabel dengan hasil 1,0,0** 
- **Langkah 1: Menyusun Sistem Persamaan**

*Kita memilih tiga persamaan linear dengan tiga variabel:*

5x+2y+3z=1

3x+4y+2z=0

2x+3y+5z=0
 
*Ini dapat ditulis dalam bentuk matriks sebagai:*

$$
A =
\begin{bmatrix}
5 & 2 & 3 \\
3 & 4 & 2 \\
2 & 3 & 5
\end{bmatrix}, \quad
B =
\begin{bmatrix}
1 \\
0 \\
0
\end{bmatrix}
$$

- **Langkah 2: Mencari Invers Matriks A**

Untuk menemukan \( A^{-1} \), kita menggunakan rumus invers matriks:

$$
A^{-1} = \frac{1}{\det(A)} \cdot \text{adj}(A)
$$

#*Hitung Determinan 𝐴*

$$
\det(A) =
\begin{vmatrix} 
5 & 2 & 3 \\ 
3 & 4 & 2 \\ 
2 & 3 & 5 
\end{vmatrix}
$$

menghitung determian menggunakan ekspansi kofaktor:

det(A)=5(4×5−2×3)−2(3×5−2×2)+3(3×3−4×2)
=5(20−6)−2(15−4)+3(9−8)
=5(14)−2(11)+3(1)=5(14)−2(11)+3(1)
=70−22+3=51

#*Hitung Adjoin(Adj A)*
1. Caranya dengan menghitung matriks kofaktor dan mentransposenya.
2. Setelah didapat, bagi setiap elemen dengan 
det(𝐴).

- **Langkah 3: Menhitung \( A^{-1} B \)**

Dengan menggunakan metode matriks:

$$
X = A^{-1} B
$$

Setelah menghitung \( A^{-1} \), hasilnya:

$$
A^{-1} B =
\begin{bmatrix} 
0.2745 \\ 
-0.2157 \\ 
0.0196 
\end{bmatrix}
$$

- **Kesimpulan**

Hasil yang diperoleh bukan 
$$
\begin{bmatrix} 
1 \\ 
0 \\ 
0 
\end{bmatrix}
$$
sehingga sistem ini tidak memenuhi syarat yang diminta. Saya akan mencoba sistem persamaan lain untuk memastikan hasilnya benar.

Mari kita buat sistem persamaan baru dan memastikan bahwa hasil \( A^{-1} B \) benar-benar
$$
\begin{bmatrix} 
1 \\ 
0 \\ 
0 
\end{bmatrix}.
$$

- **Sistem Persamaan Baru**
Misalkan:

$$
\begin{cases} 
1x + 2y + 3z = 1 \\ 
0x + 1y + 4z = 0 \\ 
0x + 0y + 1z = 0 
\end{cases}
$$

Dalam bentuk matriks:

$$
A =
\begin{bmatrix} 
1 & 2 & 3 \\ 
0 & 1 & 4 \\ 
0 & 0 & 1 
\end{bmatrix}, \quad
B =
\begin{bmatrix} 
1 \\ 
0 \\ 
0 
\end{bmatrix}
$$

Saya akan menghitung \( A^{-1} B \) sekarang.

$$
\begin{bmatrix} 
1 \\ 
0 \\ 
0 
\end{bmatrix}.
$$

Ini sesuai dengan yang diminta.

Jadi, sistem persamaan berikut memenuhi syarat:
