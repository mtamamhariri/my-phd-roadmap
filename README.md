# my-phd-roadmap
Belajar Data Science

Berikut adalah Peta Jalan (Roadmap) Anda, yang saya bagi menjadi empat fase utama.

Fase 1: Fondasi Komputasi & Matematika (Perkiraan: 6 Bulan)
Tujuan fase ini adalah membangun fondasi yang kokoh. Seorang pakar tidak pernah goyah pada dasarnya.

Filosofi Harian: Setiap hari, Anda akan menyelesaikan satu set soal matematika dan satu tantangan logika pemrograman dasar.

Modul 1: Arsitektur Komputer & Sistem Operasi

Teori: Cara kerja CPU, Memori (RAM vs Storage), Sistem Operasi (Windows vs UNIX-like).

Hands-on Harian:

Minggu 1: Gunakan command line (Bash/Shell) secara eksklusif. Navigasi file, manajemen proses, permission (chmod).

Minggu 2-3: Instalasi dan konfigurasi virtual machine (misalnya, Ubuntu di VirtualBox). Anda harus nyaman di lingkungan Linux.

Minggu 4: Menulis script shell sederhana untuk mengotomatisasi tugas (misal: backup file harian).

Modul 2: Matematika Esensial untuk Sains Data

Teori:

Aljabar Linear: Vektor, Matriks, Operasi Matriks, Eigenvalues/Eigenvectors.

Kalkulus: Turunan (Derivatif), Aturan Rantai, Gradien (Penting untuk optimization).

Statistika Deskriptif: Mean, Median, Modus, Varians, Standar Deviasi.

Statistika Inferensial & Probabilitas: Distribusi (Normal, Binomial), p-value, Uji Hipotesis (t-test).

Hands-on Harian:

Selesaikan 5 soal Aljabar Linear/Kalkulus setiap pagi (gunakan platform seperti Khan Academy).

Ambil dataset sederhana (misal: data tinggi badan), dan hitung SEMUA statistik deskriptifnya secara manual, lalu verifikasi menggunakan Excel/Google Sheets.

Modul 3: Struktur Data & Basis Data

Teori: Apa itu database? Model Relasional (SQL) vs Non-Relasional (NoSQL).

Hands-on Harian:

Minggu 1-2 (SQL): Instalasi PostgreSQL. Buat database dari nol. Latih SELECT, FROM, WHERE, GROUP BY, JOIN setiap hari.

Minggu 3 (Struktur Data): Pahami konsep Array, List, Stack, Queue, Dictionary/Hash Map.

Fase 2: Penguasaan Python & Ekosistem Data (Perkiraan: 9 Bulan)
Di sini kita beralih dari konsep ke implementasi. Python adalah "pisau bedah" Anda.

Filosofi Harian: "Jangan pernah menutup hari tanpa menulis kode." Selesaikan 1-3 tantangan di platform seperti Codewars atau LeetCode (Easy/Medium) setiap hari.

Modul 1: Python Inti

Teori: Tipe data, loops, conditional, function, error handling.

Hands-on Harian: Otomatisasi tugas-tugas kecil. Tulis skrip untuk mengunduh file dari web, membaca file teks dan menghitung kata, dll.

Modul 2: Python untuk Sains (The 'Stack')

Teori & Hands-on Harian:

NumPy: Ambil semua latihan Aljabar Linear dari Fase 1, dan kerjakan ulang menggunakan NumPy. Rasakan kecepatannya.

Pandas: Ini adalah 'Excel' Anda.

Proyek Mingguan: Ambil dataset kotor (misal: dari Kaggle). Tugas Anda: Load, clean (tangani missing values), filter, group, dan merge data. Lakukan ini setiap minggu dengan dataset baru.

Matplotlib & Seaborn: Visualisasi.

Tugas Harian: Ambil dataset dari Pandas, buat 5 jenis visualisasi berbeda (Histogram, Scatter Plot, Box Plot, Heatmap, Line Plot). Jelaskan insight apa yang Anda dapatkan dari tiap plot.

Modul 3: Alat Bantu Profesional

Teori: Version Control (Git).

Hands-on Harian: Mulai hari ini, semua kode Anda HARUS ada di GitHub.

Buat repository. Lakukan git commit dan git push setiap hari.

Latih branching (buat branch 'development', kerjakan di sana, lalu merge ke 'main').

Fase 3: Spesialisasi Machine Learning (Perkiraan: 12 Bulan)
Ini adalah inti dari "Data Science". Anda tidak hanya menggunakan model, Anda membedahnya.

Filosofi Harian: Ambil satu algoritma, implementasikan dari nol (hanya menggunakan NumPy), baru kemudian gunakan library (Scikit-learn) untuk membandingkan.

Modul 1: Siklus Hidup Proyek Sains Data

Teori: Metodologi (CRISP-DM), Data Collection, Feature Engineering, Modeling, Evaluation, Deployment.

Hands-on: Tulis proposal 1 halaman untuk proyek passion Anda menggunakan kerangka CRISP-DM.

Modul 2: Machine Learning Klasik

Teori & Hands-on (Algoritma per minggu):

Regresi Linear & Logistik: Pahami cost function dan gradient descent.

Decision Trees & Random Forests: Pahami Gini impurity / Entropy.

Support Vector Machines (SVM): Pahami konsep kernel trick.

K-Means Clustering (Unsupervised): Pahami centroid dan inertia.

PCA (Dimensionality Reduction): Hubungkan ini kembali ke Aljabar Linear (Eigenvectors).

Proyek Bulanan: Selesaikan satu proyek end-to-end di Kaggle. Fokus pada Feature Engineering dan Model Evaluation (Pahami beda Akurasi, Presisi, Recall, F1-Score, ROC-AUC).

Modul 3: Pengantar Deep Learning

Teori: Neural Networks, Backpropagation (ini adalah Kalkulus + Aljabar Linear), Activation Functions.

Hands-on Harian: Gunakan TensorFlow/PyTorch.

Minggu 1-2: Bangun neural network sederhana untuk klasifikasi dataset (misal: MNIST).

Minggu 3-4 (CNN): Fokus pada Computer Vision. Bangun klasifikasi gambar (misal: Kucing vs Anjing).

Minggu 5-6 (RNN/LSTM): Fokus pada NLP. Bangun analisis sentimen sederhana.

Fase 4: Menuju Tingkat Pakar & Riset (PhD Level) (Berkelanjutan)
Fase ini tidak memiliki akhir. Ini adalah tentang penguasaan dan kontribusi.

Filosofi Harian: Baca satu paper akademis (misal: dari ArXiv) setiap hari/dua hari. Coba pahami idenya, dan jika mungkin, replikasi hasilnya.

Modul 1: Topik Lanjutan

Teori & Hands-on:

MLOps: Cara mendeploy model Anda. Belajar Docker, FastAPI (untuk membuat API), dan dasar-dasar cloud (AWS/GCP).

Big Data: Kapan Pandas tidak cukup? Belajar Spark (PySpark). Proses dataset berukuran 100GB (bukan 100MB).

NLP Lanjutan: Pahami arsitektur Transformers (Model di balik ChatGPT).

Modul 2: Disertasi (Kontribusi Anda)

Ini adalah puncak "PhD" Anda.

Tugas Anda:

Replikasi: Pilih 3 paper state-of-the-art di bidang yang Anda minati. Replikasi hasil mereka dari nol. Ini sangat sulit dan akan menguji semua yang telah Anda pelajari.

Kontribusi: Temukan celah. Apakah model mereka bisa dibuat lebih efisien? Apakah bisa diterapkan pada dataset baru yang unik (mungkin data dari Indonesia)?

Publikasi: Tuliskan temuan Anda dalam bentuk blog post teknis yang mendalam atau (idealnya) kontribusi ke library open-source atau paper konferensi.

🏛️ Peraturan Harian Laboratorium Kita
Untuk berhasil dalam program ini, "hands-on day by day" adalah hukum.

Pagi (08:00 - 10:00): Teori & Matematika.

Baca konsep baru atau review matematika. Waktu untuk menyerap.

Siang (10:00 - 15:00): Latihan Terfokus.

Ini adalah waktu coding inti. Menerapkan teori pagi hari. (Misal: "Hari ini saya akan mengimplementasikan K-Means dari nol").

Sore (15:00 - 17:00): Proyek & Aplikasi.

Kerjakan proyek jangka panjang Anda (Proyek Kaggle, Proyek Replikasi Paper).

Malam (Opsional, tapi direkomendasikan): Kajian.

Baca artikel, blog teknis, atau satu bagian dari paper.