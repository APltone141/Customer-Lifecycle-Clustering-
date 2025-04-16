# 📦 Folder: data/

Folder ini menyimpan dataset mentah dan hasil pengolahan yang digunakan dalam analisis segmentasi pelanggan.

## 📁 Isi Folder

### 1. `online_retail.csv`

- Dataset transaksi penjualan dari toko ritel daring.
- Sumber: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail) atau Kaggle.

**Contoh Kolom:**

- `InvoiceNo`: ID transaksi
- `StockCode`: ID produk
- `Description`: Deskripsi produk
- `Quantity`: Jumlah barang
- `InvoiceDate`: Tanggal transaksi
- `UnitPrice`: Harga per item
- `CustomerID`: ID pelanggan
- `Country`: Negara pelanggan

### 2. `rfm_segmented.csv`

- Dataset hasil pengolahan RFM dan klasterisasi.

**Contoh Kolom:**

- `CustomerID`
- `Recency`
- `Frequency`
- `Monetary`
- `Cluster`: Hasil clustering KMeans
- `Segment`: Label segmen pelanggan (misal: Loyal, At Risk, New, dll)

  # 📁 data/

This folder contains all the datasets used in the project.

## Files

- **online_retail.csv**  
  A publicly available dataset of UK-based online retail transactions from 2010–2011. Used as raw input data.

- **rfm_segmented.csv**  
  Contains the final RFM scores and cluster labels for each customer after segmentation.

## Usage
You can load these datasets using pandas:

```python
import pandas as pd
raw_data = pd.read_csv("data/online_retail.csv")
rfm_data = pd.read_csv("data/rfm_segmented.csv")
```

Make sure to run all preprocessing steps in the notebook or script before using `rfm_segmented.csv`.

