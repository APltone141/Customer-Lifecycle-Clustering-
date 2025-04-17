# 📦 Folder: data/

This folder contains the raw dataset and processed output used in the customer segmentation analysis.

## 📁 Folder Contents

### 1. `online_retail.csv`

- Sales transaction dataset from an online retail store.
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail) or Kaggle.

**Sample Columns:**

- `InvoiceNo`: Transaction ID  
- `StockCode`: Product ID  
- `Description`: Product description  
- `Quantity`: Number of items  
- `InvoiceDate`: Transaction date  
- `UnitPrice`: Price per item  
- `CustomerID`: Customer ID  
- `Country`: Customer’s country  

### 2. `rfm_segmented.csv`

- Dataset after RFM processing and clustering.

**Sample Columns:**

- `CustomerID`  
- `Recency`  
- `Frequency`  
- `Monetary`  
- `Cluster`: KMeans clustering result  
- `Segment`: Segment label (e.g., Loyal, At Risk, New, etc.)

## 📁 data/

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

Make sure to run all preprocessing steps in the notebook or script before using `rfm_segmented.csv`.

