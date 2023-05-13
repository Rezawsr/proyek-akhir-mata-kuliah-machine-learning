# proyek-akhir-mata-kuliah-machine-learning

> Nama : Muhammad Reza Abdillah
> NIM : 200907501018
> Kelas : Bisnis Digital B
> Mata Kuliah : Machine Learning


Struktur Proyek Akhir Matakuliah Machine Learning Sentimen Ulasan pada Restoran di Makassar

Proyek akhir ini bertujuan untuk melakukan analisis sentimen pada ulasan restoran di Makassar menggunakan teknik machine learning. Data yang digunakan dalam proyek ini diambil melalui teknik web scraping pada Google Maps menggunakan library SerpApi. Restoran yang menjadi fokus dalam analisis sentimen adalah Hongkong Restaurant, RM Pallu Kaloa, Rumah Makan Pattene, dan Rich Taste.

Struktur proyek akhir terdiri dari beberapa tahapan, antara lain:

Web Scraping
Pada tahapan ini dilakukan pengambilan data ulasan restoran dari Google Maps menggunakan library SerpApi. Data yang diambil antara lain adalah teks ulasan, rating, dan tanggal ulasan.

Data Preprocessing
Pada tahapan ini dilakukan preprocessing terhadap data ulasan yang telah diambil. Preprocessing meliputi pembersihan data, tokenisasi, stopword removal, dan stemming.

Data Labelling
Pada tahapan ini dilakukan labelisasi pada data ulasan. Labelisasi dilakukan dengan mengkategorikan ulasan menjadi positif, negatif, atau netral berdasarkan rating yang diberikan oleh pengguna. Ulasan dengan rating 1-2 dikategorikan sebagai negatif, rating 3 dikategorikan sebagai netral, dan rating 4-5 dikategorikan sebagai positif.

Pembuatan Model
Pada tahapan ini dilakukan pembuatan model machine learning untuk mengklasifikasikan ulasan menjadi positif, negatif, atau netral. Beberapa model yang digunakan antara lain Naive Bayes, Decision Tree, dan Random Forest.

-Evaluasi Model

Pada tahapan ini dilakukan evaluasi terhadap model machine learning yang telah dibuat. Evaluasi dilakukan dengan membandingkan performa model berdasarkan metrik evaluasi seperti akurasi, presisi, recall, dan F1-score.
