# Titanic Data Preprocessing Portfolio

## Deskripsi Proyek
Proyek ini menampilkan proses preprocessing dan modeling awal pada dataset Titanic. Tujuannya adalah mempersiapkan data untuk machine learning dengan pembersihan, imputasi nilai hilang, encoding fitur kategorikal, dan evaluasi model.

## Isi Proyek
- `preprocessing/data_preprocessing.ipynb` — Notebook utama untuk preprocessing data dan pelatihan model Random Forest.
- `EDA/exploratory.ipynb` — Notebook exploratory data analysis untuk memahami distribusi dan korelasi fitur.
- `data/titanic/train.csv` — Dataset Titanic untuk pelatihan.
- `data/titanic/test.csv` — Dataset Titanic untuk prediksi final.

## Langkah Utama
1. Membaca dataset Titanic.
2. Memisahkan fitur (`X`) dan target (`Survived`).
3. Memeriksa nilai hilang dan tipe data.
4. Menyusun pipeline preprocessing:
   - Imputasi nilai median untuk fitur numerik (`Age`, `Fare`).
   - Standarisasi numerik.
   - Imputasi nilai paling sering dan one-hot encoding untuk fitur kategorikal.
5. Menggunakan `RandomForestClassifier` sebagai model prediksi.
6. Mengevaluasi model dengan akurasi, classification report, dan confusion matrix.

## Tools dan Library
- Python
- pandas
- scikit-learn
- matplotlib
- seaborn

## Cara Menjalankan
1. Aktifkan environment Python (jika ada):
   ```bash
   source venv/bin/activate
   ```
2. Jalankan notebook:
   ```bash
   jupyter notebook preprocessing/data_preprocessing.ipynb
   ```
3. Ikuti langkah di dalam notebook untuk melihat preprocessing dan evaluasi model.
