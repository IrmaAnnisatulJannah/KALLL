---
title: Perkalian Titik (Doctproduct)

---

# Perkalian Titik (Doctproduct)
### Dot Product, Orthogonal, dan Ortonormal

---

## Pengertian Dot Product (Perkalian Titik)

#### Definisi:

Dot product (atau **perkalian skalar**) adalah operasi antara dua vektor yang menghasilkan **angka (skalar)**, bukan vektor.

Jika:

$$\mathbf{u} = (u_1, u_2), \quad \mathbf{v} = (v_1, v_2)$$

Maka:

$$\mathbf{u} \cdot \mathbf{v} = u_1 v_1 + u_2 v_2$$
---

###  Fungsi utama:

- Menentukan apakah dua vektor **tegak lurus (orthogonal)**.  
- Menghitung **sudut** antara dua vektor.  
- Dipakai dalam banyak aplikasi: fisika, grafik komputer, machine learning, dll.

---

### Sifat penting:

- Kalau $(\mathbf{u} \cdot \mathbf{v} = 0)$, berarti **vektor saling tegak lurus** (orthogonal).

---

##  Pengertian Ortonormal

### Definisi:

Sebuah himpunan vektor dikatakan **ortonormal** jika:

1. **Orthogonal**: Semua vektor saling tegak lurus  
   (dot product = 0 antar vektor berbeda).

2. **Normalized**: Setiap vektor punya panjang (norma) = 1.

---

### Contoh:

Di ruang 2D, dua vektor berikut adalah ortonormal:

$$\mathbf{e}_1 = (1, 0), \quad \mathbf{e}_2 = (0, 1)$$

- $(\mathbf{e}_1 \cdot \mathbf{e}_2 = 0 \Rightarrow\)$ orthogonal
- $(|\mathbf{e}_1| = \sqrt{1^2 + 0^2} = 1\)$  
- $(|\mathbf{e}_2| = \sqrt{0^2 + 1^2} = 1\)$

 Maka: **ortonormal!**

---

##  BAGIAN 5: Contoh Vektor 3D dan Dot Product-nya

###  Contoh vektor:

$$
\mathbf{u} = (2, 1), \quad \mathbf{v} = (-2, 4)
$$

---

###  Panjang $(\mathbf{v})$:

$$
\mathbf{v} = \sqrt{(-2)^2 + 4^2} = \sqrt{4 + 16} = \sqrt{20}
$$

---

###  Dot Product:

$$
\mathbf{u} \cdot \mathbf{v} = 2 \cdot (-2) + 1 \cdot 4 = -4 + 4 = 0$$

 Lagi-lagi: **orthogonal!**

---

##  Inti Materinya:

| **Konsep**           | **Penjelasan**                                                                 |
|----------------------|--------------------------------------------------------------------------------|
| **Basis**            | Vektor-vektor pembentuk ruang                                                  |
| **Orthonormal**      | Vektor yang saling tegak lurus dan panjangnya 1                                |
| **Dot product = 0**  | Vektor saling tegak lurus                                                      |
| **Norma vektor**     | Panjang vektor, rumus: $$\sqrt{x^2 + y^2}$$                                    |
