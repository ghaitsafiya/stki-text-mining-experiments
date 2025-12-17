# STKI-Text-Mining-Experiments

Repository ini berisi kumpulan **eksperimen Sistem Temu Kembali Informasi (STKI)** dan **Text Mining** menggunakan Python dan Jupyter Notebook. Seluruh eksperimen disusun berdasarkan materi perkuliahan dan digunakan untuk latihan serta pemahaman konsep dasar pengolahan teks.

## 📂 Struktur Repository

```
STKI-TEXT-MINING-EXPERIMENTS
│
├── dataset/
│   ├── clean_dataset_part01.csv
│   ├── clean_dataset_stem.csv
│   ├── Dataset_Sentimen_Emosi.csv
│   ├── kamus perbaikan kata.xlsx
│   ├── tennis_articles_v4.csv
│   ├── tmdb_5000_movies.csv
│   └── classifier_nb.best_estimator_sav
│
├── Minggu8/
│   ├── 01-TFIDF.ipynb
│   ├── 02-Klasifikasi Text Mining Naive Bayes.ipynb
│   └── classifier_nb.best_estimator_sav
│
├── Minggu9/
│   └── Pipeline-Klasifikasi Text Mining-NB-KNN.ipynb
│
├── textClustering/
│   ├── Document Clustering.ipynb
│   ├── movie_hierachical_clusters.png
│   └── tmdb_5000_movies.csv.gz
│
├── textSummarization/
│   ├── rank_summ.py.ipynb
│   └── tf-idf_summ.py.ipynb
│
└── README.md
```

## 🧪 Daftar Eksperimen

### 1. TF-IDF (Term Frequency–Inverse Document Frequency)
- Representasi dokumen teks menggunakan TF-IDF
- Analisis kata penting berdasarkan sentimen (positif, netral, negatif)
- Visualisasi WordCloud

### 2. Klasifikasi Teks
- **Naive Bayes** untuk klasifikasi sentimen
- **K-Nearest Neighbor (KNN)**
- Pipeline preprocessing, vektorisasi, dan klasifikasi
- Penyimpanan model menggunakan `.sav`

### 3. Text Clustering
- **K-Means Clustering**
- **Hierarchical Clustering**
- Pengelompokan dokumen film berdasarkan deskripsi

### 4. Text Summarization
- **Sentence Ranking (PageRank)**
- **TF-IDF based Summarization**
- Pembuatan ringkasan otomatis dari dokumen teks

## 🛠️ Tools & Teknologi
- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas, numpy
- nltk
- matplotlib
- wordcloud
- networkx

## ▶️ Cara Menjalankan

1. Clone repository ini
   ```bash
   git clone https://github.com/username/STKI-Text-Mining-Experiments.git
   ```
2. Masuk ke folder project
3. Install dependensi
   ```bash
   pip install -r requirements.txt
   ```
4. Jalankan Jupyter Notebook
   ```bash
   jupyter notebook
   ```

## 📦 requirements.txt

```txt
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn
wordcloud
networkx
openpyxl
jupyter
```

## 🎓 Catatan
Repository ini dibuat untuk **keperluan akademik** dan pembelajaran mata kuliah **Sistem Temu Kembali Informasi (STKI)**. Dataset yang digunakan bersifat publik dan hanya digunakan untuk eksperimen.

---
✍️ Dibuat sebagai latihan dan dokumentasi eksperimen Text Mining & Information Retrieval.

