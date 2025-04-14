---
title: Transformasi Matriks

---

# Bab 5.1: Transformasi Matriks

## Definisi Transformasi Matriks

Transformasi matriks adalah fungsi yang memetakan vektor dari ruang \( \mathbb{R}^n \) ke ruang \( \mathbb{R}^m \) menggunakan perkalian matriks. Jika \( A \) adalah matriks berukuran \( m \times n \), maka transformasi \( T \) didefinisikan sebagai:

$$
T(\vec{x}) = A\vec{x}
$$

Transformasi ini disebut **transformasi linear** karena memenuhi dua properti utama:

1. **Penjumlahan vektor**:  
   $$ T(\vec{u} + \vec{v}) = T(\vec{u}) + T(\vec{v}) $$

2. **Skalar**:  
   $$ T(c\vec{v}) = cT(\vec{v}) $$  
   untuk setiap skalar \( c \)

Properti ini memastikan bahwa struktur linear dari ruang vektor dipertahankan setelah transformasi.

---

## Contoh Transformasi Matriks

Beberapa contoh transformasi linear yang umum meliputi:

- **Rotasi**: Memutar vektor di bidang \( \mathbb{R}^2 \) atau ruang \( \mathbb{R}^3 \)
- **Refleksi**: Mencerminkan vektor terhadap garis atau bidang tertentu
- **Skalasi**: Memanjangkan atau memendekkan vektor tanpa mengubah arah
- **Shear**: Menggeser satu komponen vektor sebanding dengan komponen lainnya

Semua transformasi ini dapat direpresentasikan menggunakan **matriks tertentu**, yang ketika dikalikan dengan vektor, menghasilkan transformasi yang diinginkan.

---

## Komposisi Transformasi

Dua transformasi linear dapat dikomposisikan satu sama lain, sehingga menghasilkan **transformasi gabungan** dengan matriks hasil perkalian.

Jika:  
- \( S_1(\vec{x}) = A\vec{x} \)  
- \( S_2(\vec{x}) = B\vec{x} \)

Maka komposisinya:  
$$
T_{S_2 \circ S_1}(\vec{x}) = B(A\vec{x}) = (BA)\vec{x}
$$

Ini menunjukkan bahwa komposisi transformasi linear juga merupakan transformasi linear.

---

## Matriks Identitas dan Transformasi Identitas

**Matriks identitas \( I \)** adalah matriks persegi dengan elemen 1 di diagonal utama dan 0 di tempat lain. Transformasi dengan matriks identitas tidak mengubah vektor input:

$$
T(\vec{x}) = I\vec{x} = \vec{x}
$$

Transformasi ini disebut **transformasi identitas**, karena setiap vektor tetap pada posisinya setelah transformasi.

---



