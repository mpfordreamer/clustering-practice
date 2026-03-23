# Clustering - Startup Risk-Return Profiling

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk mengelompokkan data startup berdasarkan profil risiko dan pengembalian (*risk-return profile*). Analisis ini membantu dalam mengidentifikasi kategori startup untuk keputusan investasi atau analisis pasar.

---

## 📂 Struktur Proyek
```text
Clustering/
├── datasets/
│   └── Dataset_clustering.csv  # Dataset Startup
└── Clustering-practice.ipynb  # Notebook Latihan Clustering
```

---

## 🛠️ Ringkasan & Library
Model menggunakan teknik **Unsupervised Learning** (Clustering) untuk mengidentifikasi pola tersembunyi dalam data bisnis startup.

**Library Utama:**
*   `pandas` & `numpy`: Analisis dan struktur data.
*   `seaborn` & `matplotlib`: Visualisasi grafik dan persebaran data.
*   `sklearn`: Algoritma clustering (K-Means), evaluasi (Silhouette Score).
*   `pingouin`: Analisis statistik tambahan jika diperlukan.

---

## 🚀 Cara Menjalankan
Untuk menjalankan notebook ini secara interaktif di **Google Colab**, ikuti langkah berikut:

1.  **Buka Google Colab**: Masuk ke [Google Colab](https://colab.research.google.com/).
2.  **Upload Notebook**: Pilih tab `Upload` dan pilih file `Clustering-practice.ipynb`.
3.  **Upload Dataset**:
    *   Pastikan path dataset di notebook sesuai (misal: `datasets/Dataset_clustering.csv`).
    *   Upload file `Dataset_clustering.csv` ke session storage Colab.
4.  **Jalankan Sel**: Klik `Runtime` -> `Run all` atau jalankan sel satu per satu dari atas ke bawah.

---

## 📊 Informasi Dataset
Dataset ini berisi data performa startup dengan beberapa variabel:
*   `Industry`: Sektor industri startup.
*   `Investment`: Total investasi yang diterima.
*   `Valuation`: Nilai valuasi startup.
*   `Growth`: Tingkat pertumbuhan.
*   Variabel finansial dan operasional lainnya yang relevan untuk analisis risiko.
*   **Output**: Label Cluster yang menunjukkan kategori profil risiko.