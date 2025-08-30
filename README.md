## 🧩 Clustering dengan DBSCAN — Dataset Wine

Proyek ini merupakan implementasi algoritma DBSCAN (Density-Based Spatial Clustering of Applications with Noise) untuk mengelompokkan data wine berdasarkan fitur kimia. Model dibangun menggunakan scikit-learn dengan preprocessing, clustering, dan visualisasi.

---

## 📂 Struktur File

| File                                                | Deskripsi                                                               |
| --------------------------------------------------- | ----------------------------------------------------------------------- |
| `Clustering_Rizky_Nanda_Praditia_20210140057.ipynb` | Notebook utama berisi preprocessing, clustering, dan visualisasi hasil. |

---

## ⚙️ Alur Model

| Tahap                 | Deskripsi                                                             |
| --------------------- | --------------------------------------------------------------------- |
| **Data Loading**      | Membaca dataset `wine-clustering.csv`.                                |
| **Visualisasi Awal**  | Scatterplot dua fitur (`Malic_Acid` dan `OD280`).                     |
| **Feature Scaling**   | Normalisasi data dengan **MinMaxScaler**.                             |
| **Clustering**        | Menggunakan **DBSCAN** dengan parameter `eps=0.5, min_samples=160`.   |
| **Evaluasi**          | Menampilkan jumlah cluster dan distribusinya.                         |
| **Visualisasi Hasil** | Scatterplot hasil clustering dengan warna berbeda untuk tiap cluster. |

---

## ✨ Fitur Utama

🌀 Implementasi clustering dengan DBSCAN.

📊 Visualisasi sebelum dan sesudah clustering.

🔎 Identifikasi data noise (-1) dan cluster valid.

⚡ Notebook interaktif untuk eksplorasi parameter DBSCAN.

---

## 🚀 Cara Menjalankan

Clone repo:

git clone https://github.com/rizkynandapr/Clustering-Wine.git
cd Clustering-Wine


Install dependencies:

pip install -r requirements.txt


Jalankan notebook:

jupyter notebook Clustering_Rizky_Nanda_Praditia_20210140057.ipynb

---

## 🛠️ Teknologi yang Digunakan

Python 3.x

scikit-learn

NumPy, Pandas

Matplotlib

---

## 📊 Hasil

✅ Data berhasil dikelompokkan menjadi beberapa cluster.

📈 Noise (outlier) teridentifikasi dengan label -1.

🎨 Visualisasi hasil clustering memperlihatkan pemisahan data berdasarkan densitas.
