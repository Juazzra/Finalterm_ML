  Transaction Fraud Detection using Deep Learning
Identitas Pengembang

Nama: Juandra Alghifary
NIM: 1103220165
Kelas: TK-46-02

1. Tujuan Repositori
Repositori ini dibuat untuk memenuhi tugas mata kuliah Machine Learning yang berfokus pada implementasi Deep Learning untuk mendeteksi transaksi penipuan (fraud detection). Tujuan utamanya adalah membangun sebuah pipeline end-to-end yang mampu membedakan transaksi normal dari transaksi ilegal dengan akurasi dan performa yang optimal.

2. Ringkasan Proyek
Proyek ini mengimplementasikan klasifikasi biner pada dataset transaksi berskala besar (IEEE-CIS Fraud Detection).
Dataset: Menggunakan train_transaction.csv (±590.000 sampel, 393 fitur) dan test_transaction.csv (±506.000 sampel).
Teknologi Utama: * Polars: Digunakan untuk pemrosesan data yang jauh lebih cepat dan efisien dibandingkan Pandas.
TensorFlow/Keras: Framework utama untuk membangun arsitektur Neural Network.
Scikit-Learn: Untuk scaling data dan evaluasi metrik.
Pipeline: Mencakup pembersihan data, penanganan missing values, feature engineering sederhana, hingga pelatihan model deep learning dengan optimasi arsitektur.

Navigasi Notebook
      Instalasi & Import: Persiapan library (Polars, TensorFlow, dll).
      Data Acquisition: Proses pengunduhan atau pembacaan dataset.
      Data Preprocessing: Pembersihan data, pengisian null values, dan label encoding untuk fitur kategorikal.
      Feature Engineering: Pembuatan fitur statistik tambahan untuk memperkuat sinyal prediksi.
      Model Building: Pendefinisian arsitektur Neural Network menggunakan Batch Normalization dan Dropout untuk mencegah overfitting.
      Hyperparameter Tuning: Eksperimen terhadap berbagai kedalaman jaringan.
      Training & Visualization: Proses melatih model dan menampilkan grafik loss serta accuracy.
      Saving Results: Penyimpanan model dan pembuatan file submission untuk kompetisi/evaluasi akhir.
