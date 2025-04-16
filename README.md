# 🧠 RFM Customer Segmentation with KMeans

Segmentasi pelanggan menggunakan analisis RFM (Recency, Frequency, Monetary) dan algoritma KMeans Clustering untuk mengidentifikasi perilaku pelanggan dan memberikan insight strategis untuk bisnis ritel atau e-commerce.

---

## 📌 Tujuan Proyek

- Mengelompokkan pelanggan berdasarkan kebiasaan belanja mereka.
- Menyediakan insight untuk meningkatkan retensi, loyalitas, dan personalisasi kampanye.
- Memberikan visualisasi dan interpretasi segmen pelanggan.

---

## 🔍 Metodologi

1. **Data Preparation**
   - Pembersihan data, menghapus nilai kosong dan transaksi tidak valid.

2. **Feature Engineering**
   - Perhitungan nilai Recency, Frequency, dan Monetary dari transaksi pelanggan.

3. **Normalisasi dan Clustering**
   - Standardisasi data RFM.
   - KMeans Clustering dengan pencarian jumlah klaster optimal (Elbow Method & Silhouette Score).

4. **Visualisasi dan Interpretasi**
   - Visualisasi klaster dengan PCA.
   - Profiling dan pemberian label segmen seperti "Loyal Customers", "At Risk", dll.

5. **Output**
   - Dataset tersegmentasi.
   - Insight bisnis dari setiap kelompok pelanggan.

---

## 🛠️ Tools dan Library

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (KMeans, PCA)
- Streamlit (opsional untuk dashboard interaktif)

---

## 📁 Struktur Folder

```
rfm-customer-segmentation/
├── data/
│   └── online_retail.csv
├── notebooks/
│   └── rfm_clustering.ipynb
├── images/
│   └── visualizations.png
├── scripts/
│   └── segment_customer.py
├── README.md
└── requirements.txt
```

---

## 📈 Contoh Insight

- **Loyal Customers**: RFM rendah, frekuensi tinggi, spending besar.
- **New Customers**: Baru bertransaksi, potensi untuk diloyalkan.
- **At Risk**: Lama tidak belanja, butuh reaktivasi.

---

## 🚀 Pengembangan Selanjutnya

- Integrasi rekomendasi produk berbasis segmen.
- Deployment dashboard interaktif dengan Streamlit.
- Segmentasi lanjutan dengan model unsupervised lain (DBSCAN, HDBSCAN).



