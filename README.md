# 📊 Analisis Data Eksploratif (EDA) pada Dataset Film IMDb

![IMDb Project Banner](https://user-images.githubusercontent.com/26179770/121377821-b33f3d80-c97b-11eb-818a-e391b5c96c4e.png) 
Sebuah proyek analisis data untuk menggali tren, pola, dan wawasan tersembunyi dari dataset Top 1000 Film di IMDb. Proyek ini mendemonstrasikan proses lengkap dari pembersihan data, analisis eksploratif, hingga visualisasi untuk menjawab pertanyaan-pertanyaan kunci seputar dunia perfilman.

---

###  latar Belakang

Industri film sangat kompetitif dan didorong oleh data. Memahami faktor-faktor apa yang berkontribusi terhadap kesuksesan sebuah film—baik secara komersial maupun rating—adalah hal yang esensial bagi para produser, sutradara, dan investor. Proyek ini bertujuan untuk menganalisis data historis dari film-film terbaik untuk menemukan pola-pola tersebut.

---

### 🎯 Tujuan Proyek

1.  **Pembersihan Data:** Mempersiapkan dataset mentah agar siap untuk dianalisis, termasuk menangani data yang hilang dan memperbaiki tipe data.
2.  **Analisis Tren:** Menganalisis tren jumlah film yang dirilis dari tahun ke tahun.
3.  **Analisis Genre:** Mengidentifikasi genre film yang paling umum diproduksi serta genre yang paling menguntungkan secara finansial.
4.  **Analisis Korelasi:** Menyelidiki hubungan antara berbagai variabel seperti `Rating IMDb`, `Pendapatan Kotor (Gross)`, dan `Durasi Film (Runtime)`.
5.  **Identifikasi Aktor & Sutradara Top:** Menemukan sutradara dan aktor yang paling sering muncul di daftar film-film terbaik.

---

### 🛠️ Teknologi yang Digunakan

* **Python 3.11**
* **Jupyter Notebook**
* **Library Analisis Data:** Pandas, NumPy
* **Library Visualisasi Data:** Matplotlib, Seaborn

---

### 📈 Temuan Utama (Key Findings)

Berikut adalah beberapa wawasan kunci yang ditemukan dari analisis ini:

1.  **Genre Drama Mendominasi:** Genre `Drama` adalah yang paling banyak muncul dalam daftar top 1000, namun genre `Animation` dan `Adventure` memiliki rata-rata pendapatan kotor tertinggi per film.

    *[Masukkan gambar grafik "Rata-Rata Pendapatan per Genre" Anda di sini]*

2.  **Rating Bukan Penentu Utama Pendapatan:** Terdapat korelasi positif yang lemah antara rating IMDb dan pendapatan kotor. Banyak film dengan rating sedang yang justru meraih kesuksesan komersial luar biasa, menunjukkan pentingnya faktor lain seperti pemasaran.

    *[Masukkan gambar grafik scatter plot "Rating vs. Gross" Anda di sini]*

3.  **Durasi Ideal:** Mayoritas film dengan rating tertinggi memiliki durasi antara 90 hingga 140 menit. Film yang terlalu pendek atau terlalu panjang jarang mencapai rating puncak.

---

