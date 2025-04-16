# 📁 scripts/

This folder contains reusable Python scripts used in the project.

## Files

- **segment_customer.py**  
  Contains a function that takes an RFM dataframe as input and applies KMeans clustering to assign customer segments.

## Function Description
```python
from segment_customer import segment_customers
rfm_labeled = segment_customers(rfm_df)
```

## Parameters
- `rfm_df` (pandas.DataFrame): A dataframe with 'Recency', 'Frequency', and 'Monetary' columns.

## Output
- Returns the same dataframe with an additional 'Segment' column indicating the assigned cluster.

## Usage
Can be imported and used in any notebook or script for automation of segmentation process.
