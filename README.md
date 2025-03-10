# Clustering Covid 19

## Deskripsi Proyek
Proyek ini bertujuan untuk mengelompokkan data kasus COVID-19 dari berbagai wilayah menggunakan algoritma **K-Means**. Tujuannya adalah untuk mengidentifikasi pola atau kelompok wilayah dengan karakteristik penyebaran COVID-19 yang serupa. Selain itu, proyek ini menghitung **Silhouette Score** untuk mengevaluasi kualitas hasil clustering yang diperoleh.

## Dataset
Dataset yang digunakan berisi data kasus COVID-19, termasuk informasi seperti:
- Jumlah kasus positif
- Jumlah kepadatan penduduk
- Jumlah kesembuhan

## Metodologi
Proyek ini mengikuti langkah-langkah berikut:

1. **Pra-pemrosesan Data**:
   - Membersihkan data dengan menghapus atau menangani nilai yang hilang.
   - Menormalisasi fitur agar memiliki skala yang sama menggunakan teknik standarisasi.

2. **Clustering dengan K-Means**:
   - Menentukan jumlah cluster optimal (**k**) menggunakan metode Elbow atau analisis Silhouette.
   - Menerapkan algoritma K-Means untuk mengelompokkan data berdasarkan fitur yang dipilih.

3. **Evaluasi Clustering**:
   - Menghitung **Silhouette Score** untuk mengukur seberapa baik data dikelompokkan.
   - Membuat visualisasi untuk memahami distribusi cluster.

## Alat dan Teknologi
- **Bahasa Pemrograman**: Python
- **Library yang Digunakan**:
  - `pandas`: Manipulasi dan analisis data
  - `numpy`: Operasi numerik
  - `scikit-learn`: Implementasi K-Means dan perhitungan Silhouette Score
  - `matplotlib` & `seaborn`: Visualisasi data

## Hasil
- **Clustering**: Data kasus COVID-19 berhasil dikelompokkan ke dalam beberapa cluster berdasarkan fitur yang dipilih.
- **Silhouette Score**: Nilai Silhouette Score dihitung untuk mengevaluasi kualitas clustering. Nilai mendekati 1 menunjukkan clustering yang baik, sedangkan nilai mendekati -1 menunjukkan clustering yang buruk.

## Kesimpulan
Proyek ini berhasil mengelompokkan wilayah berdasarkan data kasus COVID-19 menggunakan K-Means dan mengevaluasi hasilnya dengan Silhouette Score. Hasil clustering dapat dimanfaatkan untuk analisis lebih lanjut, seperti mengidentifikasi wilayah dengan pola penyebaran serupa atau mendukung strategi penanganan pandemi yang lebih terarah.
