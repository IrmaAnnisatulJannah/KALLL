---
title: Tugas Transformasi Linear

---

## Tugas Transformasi Linear

#### - Pengertian

*Transformasi linear* merupakan fungsi yang memetakan vektor dari satu ruang vektor ke ruang vektor lain dimana memenuhi sifat-sifat tertentu seperti linearitas. Sifat-sifat transformasi linear meliputi kernel yang merupakan himpunan vektor yang dipetakan ke nilai nol, serta jangkauan yang merupakan himpunan bayangan vektor hasil transformasi. Teorema-teorema penting terkait transformasi linear antara lain mengenai dimensi kernel dll.

#### - Tugas
![WhatsApp Image 2025-04-29 at 08.33.03_17c96ffa](https://hackmd.io/_uploads/SyPEhkbgxg.jpg)
![WhatsApp Image 2025-04-29 at 09.08.13_a25f3990](https://hackmd.io/_uploads/BJIEhybele.jpg)

tugas 2 di suruh, buat 2 contoh titik masing - masing dari gambar matrik reflection tersebut

### - Jawaban

### 1. Reflection about the x-axis

**Matriks:**
$$
\begin{bmatrix}
1 & 0 \\
0 & -1
\end{bmatrix}
$$

**Efek:**
$$
(x, y) \rightarrow (x, -y)
$$

| Titik Asal | Titik Hasil |
|------------|-------------|
| (2, 3)     | (2, -3)     |
| (-1, 5)    | (-1, -5)    |
| (4, -1)    | (4, 1)      |

---

### 2. Reflection about the y-axis

**Matriks:**
$$
\begin{bmatrix}
-1 & 0 \\
0 & 1
\end{bmatrix}
$$

**Efek:**
$$
(x, y) \rightarrow (-x, y)
$$

| Titik Asal | Titik Hasil |
|------------|-------------|
| (2, 3)     | (-2, 3)     |
| (4, -1)    | (-4, -1)    |

---

### 3. Reflection about the line $y = x$

**Matriks:**
$$
\begin{bmatrix}
0 & 1 \\
1 & 0
\end{bmatrix}
$$

**Efek:**
$$
(x, y) \rightarrow (y, x)
$$

| Titik Asal | Titik Hasil |
|------------|-------------|
| (2, 3)     | (3, 2)      |
| (5, -4)    | (-4, 5)     |

---

### 4. Reflection about the line $y = -x$

**Matriks:**
$$
\begin{bmatrix}
0 & -1 \\
-1 & 0
\end{bmatrix}
$$

**Efek:**
$$
(x, y) \rightarrow (-y, -x)
$$

| Titik Asal | Titik Hasil |
|------------|-------------|
| (2, 3)     | (-3, -2)    |
| (-1, 4)    | (-4, 1)     |

---

### 5. Reflection about the origin (pusat)

**Matriks:**
$$
\begin{bmatrix}
-1 & 0 \\
0 & -1
\end{bmatrix}
$$

**Efek:**
$$
(x, y) \rightarrow (-x, -y)
$$

| Titik Asal | Titik Hasil |
|------------|-------------|
| (2, 3)     | (-2, -3)    |
| (-5, 1)    | (5, -1)     |

### - Langkah Pembuktian Transformasi Linear

### A. Contoh Titik dan Transformasi
Transformasi:
$$
T(x, y) = (x + y, x - y)
$$

| Titik Asal | Hasil Transformasi |  
|------------|---------------------|  
| (2, 3)     | (5, -1)             |  
| (0, 1)     | (1, -1)             |  
| (1, 0)     | (1, 1)              |  
| (1, 1)     | (2, 0)              |  
| (-2, 3)    | (1, -5)             |

### B. Contoh Titik untuk Refleksi (Gambar Kedua)

Refleksi terhadap:
- $y = x$
- $y = -x$
- $x$-axis
- $y$-axis
- pusat (0,0)

| Refleksi      | Titik Asal | Titik Hasil     |
|---------------|------------|-----------------|
| $y = x$       | (1, 2)     | (2, 1)          |
| $y = -x$      | (1, 2)     | (-2, -1)        |
| $x$-axis      | (1, 2)     | (1, -2)         |
| $y$-axis      | (1, 2)     | (-1, 2)         |
| pusat (0,0)   | (1, 2)     | (-1, -2)        |

---

### Pembuktian bahwa $T(x, y) = (x + y, x - y)$ adalah Transformasi Linier

### Syarat Transformasi Linier

Misal $\vec{u} = (x_1, y_1)$ dan $\vec{v} = (x_2, y_2)$.

Sebuah transformasi $T$ dikatakan linier jika:

1. Penjumlahan vektor:
   $$
   T(\vec{u} + \vec{v}) = T(\vec{u}) + T(\vec{v})
   $$
2. Perkalian skalar:
   $$
   T(c \cdot \vec{v}) = c \cdot T(\vec{v})
   $$

### Definisi Transformasi

Transformasi kita adalah:
$$
T(x, y) = (x + y, x - y)
$$

---

### Bukti 1: Penjumlahan vektor

Ambil dua vektor:  
$\vec{u} = (x_1, y_1)$ dan $\vec{v} = (x_2, y_2)$

Jumlah:
$$
\vec{u} + \vec{v} = (x_1 + x_2, y_1 + y_2)
$$

Hitung:
$$
T(\vec{u} + \vec{v}) = ((x_1 + x_2) + (y_1 + y_2), (x_1 + x_2) - (y_1 + y_2))
$$

Sementara:
$$
T(\vec{u}) = (x_1 + y_1, x_1 - y_1) \\
T(\vec{v}) = (x_2 + y_2, x_2 - y_2) \\
T(\vec{u}) + T(\vec{v}) = ((x_1 + y_1) + (x_2 + y_2), (x_1 - y_1) + (x_2 - y_2))
$$

Sama persis. ✅

---

### Bukti 2: Perkalian skalar

Ambil $c \in \mathbb{R}$ dan $\vec{v} = (x, y)$

$c \cdot \vec{v} = (cx, cy)$

Hitung:
$$
T(c \cdot \vec{v}) = T(cx, cy) = (cx + cy, cx - cy)
$$

Sementara:
$$
c \cdot T(\vec{v}) = c \cdot (x + y, x - y) = (cx + cy, cx - cy)
$$

Sama persis. ✅

---

### Kesimpulan:

Karena kedua syarat (penjumlahan dan perkalian skalar) terpenuhi, maka:  
$$
T(x, y) = (x + y, x - y)
$$  
adalah **transformasi linier**.


