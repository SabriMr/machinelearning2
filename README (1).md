
# Rangkuman Tugas RNN (Recurrent Neural Network) - Analisis Sentimen

Tugas ini merupakan implementasi Recurrent Neural Network (RNN) menggunakan TensorFlow dan Keras untuk melakukan klasifikasi sentimen pada dataset teks.

## Tujuan

- Menerapkan model RNN untuk tugas klasifikasi teks.
- Melatih dan mengevaluasi model terhadap dataset.
- Menampilkan hasil akurasi dan visualisasi proses training.

##  Model yang Digunakan

- Embedding Layer
- Simple RNN Layer
- Dense Layer (output)

##  Dataset

Dataset yang digunakan diambil dari kaggle.

---

##  Cara Menjalankan

### 1. Persiapan Lingkungan

Pastikan kamu memiliki Python 3.x dan beberapa library berikut:

```bash
pip install tensorflow pandas numpy matplotlib
```

### 2. Menjalankan Notebook

- Jalankan notebook `tugasmlRNN.ipynb` menggunakan Jupyter Notebook atau Google Colab.
- Langkah-langkah dalam notebook mencakup:
  1. **Import library** penting seperti `tensorflow`, `numpy`, dan `matplotlib`.
  2. **Load dan preprocessing** data teks.
  3. **Pembuatan model RNN** dengan Keras Sequential.
  4. **Training model** dan visualisasi hasilnya.
  5. **Evaluasi model** terhadap data uji.

---

##  Hasil

Model ditraining dalam beberapa epoch dan menghasilkan akurasi terhadap data uji. Hasil grafik loss dan akurasi ditampilkan untuk analisis performa model.

---

##  Catatan

- download dataset dari kaggle.
- Jika menggunakan Google Colab, upload dataset secara manual jika diperlukan.