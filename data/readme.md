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
