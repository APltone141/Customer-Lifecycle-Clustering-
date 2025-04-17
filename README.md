# 🧠 RFM Customer Segmentation with KMeans

Customer segmentation using RFM analysis (Recency, Frequency, Monetary) and KMeans Clustering algorithm to identify customer behavior and provide strategic insights for retail or e-commerce businesses.

---

## 📌 Project Objectives

- Group customers based on their shopping behavior.
- Provide insights to improve retention, loyalty, and campaign personalization.
- Deliver visualizations and interpretation of customer segments.

---

## 🔍 Methodology

1. **Data Preparation**
   - Data cleaning, removing null values and invalid transactions.

2. **Feature Engineering**
   - Calculating Recency, Frequency, and Monetary values from customer transactions.

3. **Normalization and Clustering**
   - Standardizing the RFM data.
   - KMeans Clustering with optimal cluster number search (Elbow Method & Silhouette Score).

4. **Visualization and Interpretation**
   - Cluster visualization with PCA.
   - Profiling and labeling segments like "Loyal Customers", "At Risk", etc.

5. **Output**
   - Segmented dataset.
   - Business insights from each customer group.

---

## 🛠️ Tools and Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (KMeans, PCA)
- Streamlit (optional for interactive dashboard)

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

## 📈 Example Insights

- **Loyal Customers**: Low recency, high frequency, large spending.
- **New Customers**: Recently made purchases, potential for loyalty.
- **At Risk**: Haven't purchased in a while, need reactivation.

---

## 🚀 Future Developments

- Integrate product recommendations based on segments.
- Deploy interactive dashboard using Streamlit.
- Advanced segmentation with other unsupervised models (DBSCAN, HDBSCAN).


