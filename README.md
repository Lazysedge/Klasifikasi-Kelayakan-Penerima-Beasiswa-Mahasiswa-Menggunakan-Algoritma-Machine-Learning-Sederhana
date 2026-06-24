# Klasifikasi-Kelayakan-Penerima-Beasiswa-Mahasiswa-Menggunakan-Algoritma-Machine-Learning-Sederhana
Proyek ini bertujuan untuk membangun sistem sederhana berbasis Kecerdasan Buatan (Artificial Intelligence) yang dapat membantu proses seleksi awal penerima beasiswa mahasiswa secara objektif berdasarkan data akademik dan kondisi ekonomi.
Klasifikasi Kelayakan Penerima Beasiswa Menggunakan Decision Tree
Deskripsi Proyek

Proyek ini bertujuan untuk membangun sistem sederhana berbasis Kecerdasan Buatan (Artificial Intelligence) yang dapat membantu proses seleksi awal penerima beasiswa mahasiswa secara objektif berdasarkan data akademik dan kondisi ekonomi.

Sistem menggunakan algoritma Decision Tree untuk mengklasifikasikan mahasiswa ke dalam dua kategori:

Layak
Tidak Layak
Tujuan Proyek
Memahami konsep dasar Artificial Intelligence (AI).
Menerapkan Machine Learning untuk klasifikasi data.
Mengolah dan membersihkan data sebelum digunakan.
Membangun model Decision Tree menggunakan Python.
Mengevaluasi performa model menggunakan berbagai metrik evaluasi.
Menganalisis faktor yang paling berpengaruh terhadap kelayakan beasiswa.
Dataset

Dataset yang digunakan merupakan data simulasi mahasiswa yang dibuat sendiri sebanyak 200 data.

Variabel Dataset
Variabel	Keterangan
IPK	Indeks Prestasi Kumulatif mahasiswa
Penghasilan	Penghasilan orang tua per bulan (Rp)
Tanggungan	Jumlah tanggungan keluarga
Prestasi	Prestasi akademik/non-akademik
Semester	Semester aktif mahasiswa
Status_Beasiswa	Target klasifikasi (Layak / Tidak Layak)
Metode yang Digunakan

Algoritma Machine Learning:

Decision Tree Classifier

Library yang digunakan:

pandas
numpy
matplotlib
scikit-learn
joblib
graphviz
Tahapan Pengerjaan
1. Identifikasi Masalah

Membantu proses seleksi awal penerima beasiswa secara lebih objektif berdasarkan data mahasiswa.

2. Pengumpulan Data

Membuat dataset simulasi mahasiswa dalam format CSV.

Jumlah data:

5000 Mahasiswa
3. Preprocessing Data

Tahapan yang dilakukan:

Mengecek data kosong
Memperbaiki format data
Mengubah data kategori menjadi numerik
Memisahkan fitur dan target

Encoding:

Prestasi:
Ada → 1
Tidak Ada → 0

Status_Beasiswa:
Layak → 1
Tidak Layak → 0
4. Pembuatan Model

Model dibangun menggunakan:

DecisionTreeClassifier()

Data dibagi menjadi:

80% Data Training
20% Data Testing

**Cara Menjalankan**
1. Install Library
pip install pandas numpy matplotlib scikit-learn graphviz joblib
2. Jalankan Notebook

Buka:

Project_Beasiswa.ipynb

di:

Google Colab
Jupyter Notebook
VS Code
3. Training Model

Jalankan seluruh cell secara berurutan mulai dari:

Import Dataset
↓
Preprocessing
↓
Training Model
↓
Evaluasi
↓
Feature Importance
