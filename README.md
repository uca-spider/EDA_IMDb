#📊 Analisis Data Eksploratif (EDA) pada Dataset Film IMDb
Sebuah proyek analisis data untuk menggali tren, pola, dan wawasan tersembunyi dari dataset Top 1000 Film di IMDb. Proyek ini mendemonstrasikan proses lengkap dari pembersihan data, analisis eksploratif, hingga visualisasi untuk menjawab pertanyaan-pertanyaan kunci seputar dunia perfilman.

Latar Belakang
Industri film sangat kompetitif dan didorong oleh data. Memahami faktor-faktor apa yang berkontribusi terhadap kesuksesan sebuah film—baik secara komersial maupun rating—adalah hal yang esensial bagi para produser, sutradara, dan investor. Proyek ini bertujuan untuk menganalisis data historis dari film-film terbaik untuk menemukan pola-pola tersebut.

Dataset: IMDb Dataset of top 1000 Movies and TV shows by Akshay Dattatray Khare

🎯 Tujuan Proyek
Pembersihan Data: Mempersiapkan dataset mentah agar siap untuk dianalisis.

Analisis Genre: Mengidentifikasi genre film yang paling umum diproduksi dan paling sukses.

Analisis Rating: Membandingkan bagaimana audiens umum dan kritikus profesional menilai film.

Analisis Korelasi: Menyelidiki hubungan antara variabel kunci seperti rating, pendapatan, jumlah suara, dan durasi.

Analisis Sertifikasi Usia: Melihat apakah ada pengaruh sertifikasi usia terhadap rating sebuah film.

🛠️ Teknologi yang Digunakan
Python 3.11

Jupyter Notebook

Library Analisis Data: Pandas, NumPy

Library Visualisasi Data: Matplotlib, Seaborn

📈 Temuan Utama & Wawasan Kunci
Berikut adalah rangkuman temuan dan wawasan paling menarik dari analisis ini:

1. Genre Drama Mendominasi Lanskap Film Berkualitas
Analisis frekuensi menunjukkan bahwa genre Drama secara signifikan lebih sering muncul di daftar film-film terbaik dibandingkan genre lainnya. Ini mengindikasikan bahwa narasi yang kuat dan berfokus pada karakter adalah fondasi paling umum untuk sebuah karya yang diakui.
(assets/img/frekuensi_genre.png)

3. Perbedaan Cara Pandang Antara Audiens dan Kritikus
Saat membandingkan distribusi rating, terlihat jelas bahwa audiens dan kritikus memiliki cara menilai yang berbeda.

Audiens (IMDb) cenderung memberikan rating yang sangat terkonsentrasi di rentang nilai tinggi (sekitar 7.8 - 8.0), menunjukkan adanya konsensus yang kuat untuk film-film yang dianggap hebat.

Kritikus (Metascore) menunjukkan variasi opini yang jauh lebih besar, dengan sebaran skor yang lebih lebar dan tidak seketat audiens.

3. Opini Audiens dan Kritikus Seringkali Sejalan, Tapi Tidak Selalu
Meskipun cara menilai mereka berbeda, secara umum film yang disukai audiens juga disukai kritikus. Terdapat korelasi positif yang jelas antara Rating IMDb dan Metascore. Namun, banyaknya sebaran data menunjukkan masih banyak film di mana kedua pihak memiliki pendapat yang berbeda.

4. Kualitas Film Tidak Terikat pada Sertifikasi Usia
Analisis menunjukkan bahwa tidak ada sertifikasi usia tertentu yang secara konsisten menghasilkan film dengan rating lebih tinggi. Film untuk semua umur hingga film untuk penonton dewasa memiliki distribusi rating yang sangat mirip. Ini membuktikan bahwa kualitas sebuah karya bersifat universal dan tidak dibatasi oleh target demografi usianya.

5. Popularitas vs. Kualitas: Apa yang Mendorong Pendapatan?
Heatmap korelasi memberikan wawasan bisnis yang sangat penting:

Korelasi terkuat adalah antara Jumlah Suara (No_of_Votes) dan Pendapatan (Gross) (0.57). Ini logis: semakin populer sebuah film, semakin banyak orang yang menonton dan memberikan suara.

Yang paling menarik, korelasi antara skor kritikus (Meta_score) dan Pendapatan (Gross) hampir tidak ada (-0.03). Ini membuktikan bahwa pujian dari kritikus tidak menjamin kesuksesan sebuah film di box office.
