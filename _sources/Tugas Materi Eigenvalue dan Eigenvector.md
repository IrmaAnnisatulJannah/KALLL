---
title: 1. Apa itu Eigenvalue dan Eigenvector?

---

# 1. Apa itu Eigenvalue dan Eigenvector?

## Definisi:

- **Eigenvector** adalah vektor yang, ketika dikalikan dengan suatu matriks **A**, hanya berubah skalanya (besarannya), **tidak berubah arah**.
- **Eigenvalue** adalah nilai skalar **λ** yang menunjukkan seberapa besar perubahan skala tersebut.

Secara matematis:


Di mana:
- **A** adalah matriks persegi,
- **x** adalah eigenvector (vektor tak nol),
- **λ** adalah eigenvalue.

---

## Cara Mencari Eigenvalue dan Eigenvector:

### Langkah 1: Cari eigenvalue
- Gunakan rumus:

det(A - λI) = 0

- Ini akan menghasilkan **persamaan karakteristik** yang bisa diselesaikan untuk mendapatkan nilai **λ**.

### Langkah 2: Cari eigenvector
- Setelah menemukan **λ**, substitusikan ke persamaan:

(A - λI)x = 0

- Lalu selesaikan sistem persamaan linear tersebut untuk mendapatkan vektor **x** (eigenvector).

---

# 2. Apa itu Ortogonal dan Ortonormal?

## Ortogonal
- Dua vektor dikatakan **ortogonal** jika hasil kali dalam (dot product) antara keduanya = **0**.
- Artinya, kedua vektor tersebut **saling tegak lurus** di ruang vektor.

## Ortonormal
- Sekumpulan vektor disebut **ortonormal** jika:
  1. Masing-masing vektor **ortogonal** terhadap yang lain.
  2. Panjang (norma) setiap vektor = **1**.

---

## Contoh:

Misalnya kita punya dua vektor di **R²**:

u = [1, 0]
v = [0, 1]


- **Dot product**:  
  `u · v = 1 · 0 + 0 · 1 = 0` → berarti **ortogonal**

- **Norma masing-masing vektor** = 1 → berarti **ortonormal**

