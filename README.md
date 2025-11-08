# UTS Data Mining: Klasifikasi Kualitas Anggur

Proyek ini adalah pengerjaan UTS Data Mining untuk membuat model klasifikasi yang memprediksi `quality` (kualitas anggur) berdasarkan fitur-fitur kimiawi.

## Alur Proyek

1.  **Data:** Menggunakan `data_training.csv` untuk melatih model dan `data_testing.csv` untuk prediksi.
2.  **Preprocessing:** Data fitur disiapkan dan di-scaling menggunakan `StandardScaler` dari Scikit-learn.
3.  **Modeling:** Model klasifikasi (`RandomForestClassifier`) dilatih pada data training untuk memprediksi `quality`.
4.  **Hasil:** Prediksi untuk data testing disimpan dalam file sesuai format yang diminta.
