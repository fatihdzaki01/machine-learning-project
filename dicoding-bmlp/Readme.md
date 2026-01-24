# Dicoding - Belajar Machine Learning Pemula (BMLP)

Project ini merupakan submission akhir dari course **Belajar Machine Learning Pemula** oleh Dicoding Indonesia.

Project mencakup dua pendekatan utama:
- **Clustering** untuk menemukan pola data
- **Classification** untuk memprediksi kelas berdasarkan hasil clustering

---

## 📌 Project Overview

### 1. Clustering
- Preprocessing data (handling missing value, duplicate, encoding, scaling)
- Clustering menggunakan **K-Means**
- Penentuan jumlah cluster menggunakan **Elbow Method**
- Evaluasi hasil clustering dengan **Silhouette Score**
- Reduksi dimensi menggunakan **PCA** (opsional)
- Hasil clustering disimpan sebagai fitur **Target**

### 2. Classification
- Dataset hasil clustering digunakan sebagai input
- Model utama: **Decision Tree**
- Model pembanding (opsional): algoritma klasifikasi lain
- Evaluasi model menggunakan:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Hyperparameter tuning (opsional)

---

## 🗂️ Struktur Folder
dicoding-bmlp/
├── notebooks/
│ ├── [Clustering]_Submission_Akhir_BMLP_Nama.ipynb
│ └── [Klasifikasi]_Submission_Akhir_BMLP_Nama.ipynb
│
├── data/
│ ├── data_clustering.csv
│ └── data_clustering_inverse.csv
│
├── models/
│ ├── model_clustering.h5
│ ├── PCA_model_clustering.h5
│ ├── decision_tree_model.h5
│ └── tuning_classification.h5
│
└── requirements.txt


---

## ⚙️ Tools & Library
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

---

## 📝 Note
Project ini mengikuti struktur dan ketentuan submission dari course  
**"Belajar Machine Learning Pemula" – Dicoding Indonesia**.