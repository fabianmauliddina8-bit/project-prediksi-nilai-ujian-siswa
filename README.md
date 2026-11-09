# PREDIKSI NILAI SISWA

## 1. Identitas Kelompok

- **Nama Project:** Prediksi Nilai Siswa
- **Nama Kelompok:** Kelompok 8

---

## 2. Anggota Kelompok

1. Zihni Ahmad Alrafi
2. Carissa Anasytasya Saputri
3. Selvi Mahagresi
4. Lovely Juwina Putri
5. Fabian Mauliddina
6. Muhammad Aria Raga
7. Imran Fernando Nainggolan
8. Adam Nur Saefulloh
9. Ananda Samuel Jordy
10. Adel Naysila Ali
11. Estrela Amor
12. Andi Adam Alfatih
13. Aufa Zuhdi Syakir

---

## 3. Deskripsi Project

Project ini bertujuan untuk membangun model machine learning yang dapat memprediksi nilai siswa berdasarkan data dan atribut yang tersedia.

---

## 4. Jenis Permasalahan

Prediksi nilai siswa termasuk permasalahan supervised learning dengan pendekatan regresi apabila target yang diprediksi berupa nilai numerik.

---

## 5. Dataset

Dataset yang digunakan berisi informasi siswa yang akan digunakan sebagai dasar analisis dan proses prediksi.

---

## 6. Algoritma

Algoritma yang digunakan:
Linear Regression  untuk memprediksi nilai siswa berdasarkan hubungan antara variabel, misalnya waktu belajar, kehadiran, dan nilai sebelumnya.

---

## 7. Ringkasan Hasil

7. Ringkasan Hasil

Dataset Student Performance Factors terdiri dari 6.607 data dengan 20 kolom. Data diproses dengan mengisi missing value (median untuk fitur numerik dan modus untuk fitur kategorikal) serta mengubah fitur kategorikal menjadi angka menggunakan One-Hot Encoding. Model Linear Regression kemudian dilatih untuk memprediksi Exam_Score.

Hasil evaluasi pada data uji:

| Metrik | Nilai |
|---|---|
| MAE | 0,4524 |
| RMSE | 1,8044 |
| R-squared (R²) | 0,7696 |

Interpretasi:
- MAE sebesar 0,45 berarti rata-rata prediksi meleset sekitar 0,45 poin dari nilai sebenarnya.
- RMSE sebesar 1,80 lebih besar dari MAE karena terdapat beberapa siswa dengan nilai ekstrem yang sulit diprediksi.
- R² sebesar 0,77 berarti model mampu menjelaskan sekitar 77% variasi nilai ujian siswa.

Berdasarkan analisis korelasi, faktor yang paling berhubungan dengan nilai ujian adalah kehadiran (Attendance) dan jam belajar (Hours_Studied). Secara keseluruhan, Linear Regression bekerja dengan baik untuk memprediksi nilai ujian siswa pada dataset ini.

---

## 8. Cara Menjalankan Project

1. Buka folder `notebook/`.
2. Jalankan file notebook (berformat `.ipynb`) menggunakan **Google Colab** atau **Jupyter Notebook**.
3. Jalankan setiap *cell* secara berurutan dari atas ke bawah.
