# Prediksi Churn Pelanggan Menggunakan Machine Learning

## Ringkasan
Proyek ini bertujuan untuk memprediksi churn pelanggan menggunakan teknik machine learning. Dataset yang digunakan berisi berbagai fitur terkait pelanggan, dengan tujuan untuk mengklasifikasikan apakah seorang pelanggan akan tetap atau keluar dari perusahaan.

## Dataset
- **train.csv**: Data pelatihan yang sudah memiliki label churn.
- **test.csv**: Data uji tanpa label.
- **submission.csv**: Hasil prediksi untuk dataset uji.

## Struktur Proyek
```
|-- train.csv
|-- test.csv
|-- Customer_Churn_ML.ipynb
|-- submission.csv
|-- README.md
```

## Langkah-Langkah yang Dilakukan
### 1. Eksplorasi Data (EDA)
- Memeriksa data yang hilang dan duplikasi.
- Visualisasi fitur numerik dan kategorikal.
- Menganalisis korelasi antar fitur.

### 2. Preprocessing Data
- Mengatasi nilai yang hilang dengan **KNN Imputer**.
- Encoding variabel kategorikal menggunakan **Label Encoding** dan **One-Hot Encoding**.
- Normalisasi fitur numerik menggunakan **StandardScaler**.
- Membagi data menjadi **data latih (training)** dan **data validasi (validation)**.

### 3. Pelatihan Model
- Menggunakan **RandomForestClassifier** untuk klasifikasi.
- Melatih model dengan dataset yang sudah diproses.

### 4. Evaluasi Model
- Menghitung metrik evaluasi seperti **Akurasi dan Classification Report**.

### 5. Prediksi dengan Model
- Memastikan data uji memiliki fitur yang sesuai dengan data latih.
- Melakukan prediksi churn pada dataset uji.
- Menyimpan hasil prediksi ke dalam file CSV untuk dikirim.


## Hasil & Analisis
- Model dievaluasi menggunakan berbagai metrik performa.
- Analisis fitur penting membantu memahami faktor utama penyebab churn.

## Peningkatan di Masa Depan
- Mencoba model lain seperti **XGBoost** atau **Neural Networks**.
- Melakukan **feature engineering** untuk meningkatkan performa model.

## Penulis
**Mayhesa Rachmadiharja**

---
**Catatan:** Proyek ini dikembangkan menggunakan **Google Colab**.
