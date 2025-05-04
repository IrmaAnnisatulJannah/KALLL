---
title: Tugas Transformasi Matriks

---

## TUGAS TRANSFORMASI MATRIKS
___
### Soal 1

Diketahui:  
\( A = \begin{bmatrix} 1 & 2 \\ 3 & 1 \end{bmatrix} \),  
\( \vec{i} = \begin{bmatrix} 1 \\ 0 \end{bmatrix} \),  
\( \vec{j} = \begin{bmatrix} 0 \\ 1 \end{bmatrix} \)

Hitung \( A\vec{i} \) dan \( A\vec{j} \):

$$
A\vec{i} = \begin{bmatrix} 1 & 2 \\ 3 & 1 \end{bmatrix} \begin{bmatrix} 1 \\ 0 \end{bmatrix} = \begin{bmatrix} 1 \\ 3 \end{bmatrix}
$$

$$
A\vec{j} = \begin{bmatrix} 1 & 2 \\ 3 & 1 \end{bmatrix} \begin{bmatrix} 0 \\ 1 \end{bmatrix} = \begin{bmatrix} 2 \\ 1 \end{bmatrix}
$$

---

### Soal 2

Diketahui:  
\( A = \begin{bmatrix} 2 & 0 \\ 3 & -1 \end{bmatrix} \),  
\( \vec{i} = \begin{bmatrix} 1 \\ 0 \end{bmatrix} \),  
\( \vec{j} = \begin{bmatrix} 0 \\ 1 \end{bmatrix} \)

Hitung \( A\vec{i} \) dan \( A\vec{j} \):

$$
A\vec{i} = \begin{bmatrix} 2 & 0 \\ 3 & -1 \end{bmatrix} \begin{bmatrix} 1 \\ 0 \end{bmatrix} = \begin{bmatrix} 2 \\ 3 \end{bmatrix}
$$

$$
A\vec{j} = \begin{bmatrix} 2 & 0 \\ 3 & -1 \end{bmatrix} \begin{bmatrix} 0 \\ 1 \end{bmatrix} = \begin{bmatrix} 0 \\ -1 \end{bmatrix}
$$

---

### Soal 5

Gambarnya menunjukkan transformasi dari **unit square** menjadi **bangun jajaran genjang** dengan vektor basis baru:

- Ujung dari vektor \( \vec{i} \) sepanjang sumbu-x menjadi \( \begin{bmatrix} 1 \\ 2 \end{bmatrix} \)
- Ujung dari vektor \( \vec{j} \) sepanjang sumbu-y menjadi \( \begin{bmatrix} 2 \\ 3 \end{bmatrix} \)

Berarti kolom-kolom matriks transformasinya adalah vektor hasil transformasi dari \( \vec{i} \) dan \( \vec{j} \):

$$
A = \begin{bmatrix} 1 & 2 \\ 2 & 3 \end{bmatrix}
$$

---

### Soal 6

Unit square diputar hingga membentuk persegi miring (seperti hasil rotasi 45°) tapi ukuran tetap.

Maka ini adalah rotasi 45° **berlawanan arah jarum jam**.  
Matriks rotasi 45°:

$$
A = \begin{bmatrix}
\cos 45^\circ & -\sin 45^\circ \\
\sin 45^\circ & \cos 45^\circ
\end{bmatrix}
= \frac{1}{\sqrt{2}} \begin{bmatrix}
1 & -1 \\
1 & 1
\end{bmatrix}
$$

---

### Ringkasan Jawaban

1.  
\( A\vec{i} = \begin{bmatrix} 1 \\ 3 \end{bmatrix} \),  
\( A\vec{j} = \begin{bmatrix} 2 \\ 1 \end{bmatrix} \)

2.  
\( A\vec{i} = \begin{bmatrix} 2 \\ 3 \end{bmatrix} \),  
\( A\vec{j} = \begin{bmatrix} 0 \\ -1 \end{bmatrix} \)

5.  
\( A = \begin{bmatrix} 1 & 2 \\ 2 & 3 \end{bmatrix} \)

6.  
\( A = \frac{1}{\sqrt{2}} \begin{bmatrix} 1 & -1 \\ 1 & 1 \end{bmatrix} \)

---


