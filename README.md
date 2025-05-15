# Prediksi-Pembelian-Berdasarkan-Iklan-Menggunakan-Random-Forest
Repository ini berisi implementasi Random Forest Classifier untuk memprediksi apakah seorang pengguna akan melakukan pembelian berdasarkan data iklan yang mencakup umur dan estimasi gaji. Tujuan dari proyek ini adalah membangun model klasifikasi yang mampu memprediksi perilaku pengguna terhadap sebuah produk berdasarkan data demografis mereka.

# Fitur yang Digunakan:
  1. Age: Usia pengguna
  2. EstimatedSalary: Gaji yang diestimasi

# Target
  * Purchased: Apakah pengguna membeli produk (0 = Tidak, 1 = Ya)

# Langkah Langkah:
  1. Load Dataset dan buang kolom tidak relevan (User ID)
  2. Split Dataset menjadi data latih dan uji (75:25)
  3. Pelatihan Model:
  * Gunakan RandomForestClassifier dengan 10 pohon keputusan (n_estimators=10)
  4. Evaluasi Model:
  * Accuracy
  * Classification Report
  * Confusion Matrix

# Tools & Library
  1. Python
  2. Pandas, NumPy
  3. Matplotlib, Seaborn
  4. Scikit-Learn

# Visualisasi
* Confusion Matrix
* ![image](https://github.com/user-attachments/assets/15a9c84b-4be1-4507-86c2-a735b8af32a9)



* Random Forest
* ![image](https://github.com/user-attachments/assets/34b4f9c5-b40a-4978-926f-d905c22ebe62)
 








