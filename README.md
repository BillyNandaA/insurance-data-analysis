# Analisis Biaya Asuransi dengan Machine Learning

**Nama:** Billy Nanda Alfahrizi  
**NIM:** 241011403022  
**Mata Pelajaran:** Machine Learning

## Deskripsi Proyek

Proyek ini menganalisis data biaya asuransi menggunakan pendekatan Machine Learning. Notebook mencakup proses pemuatan dan pembersihan data, eksplorasi data, visualisasi, persiapan fitur, serta pemodelan regresi untuk memperkirakan biaya asuransi.

## Dataset

Dataset yang digunakan adalah `insurance.csv`.

## Tahapan Pengerjaan

1. Memuat dataset dan memeriksa struktur data.
2. Membersihkan data, termasuk pemeriksaan nilai kosong dan data duplikat.
3. Melakukan eksplorasi data dan visualisasi untuk memahami pola pada dataset.
4. Menyiapkan fitur kategorikal dengan teknik encoding serta membagi data menjadi data latih dan data uji.
5. Melakukan penskalaan fitur sesuai alur pada notebook.
6. Melatih model `DecisionTreeRegressor`.
7. Mengevaluasi model menggunakan validasi silang 5-fold.

## Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Tujuan

Tujuan proyek ini adalah memahami alur dasar penerapan Machine Learning untuk masalah regresi, mulai dari pengolahan data hingga pelatihan dan evaluasi model.

## Cara Menjalankan

1. Pastikan Python dan pustaka yang diperlukan sudah terpasang.
2. Letakkan file `insurance.csv` pada lokasi yang sesuai dengan path yang digunakan di notebook.
3. Buka notebook menggunakan Jupyter Notebook atau JupyterLab.
4. Jalankan sel secara berurutan dari awal hingga akhir.

## Catatan

Hasil prediksi dan evaluasi bergantung pada data serta konfigurasi model yang digunakan. Untuk memahami hasil proyek, periksa keluaran visualisasi dan metrik evaluasi yang dihasilkan saat notebook dijalankan.
