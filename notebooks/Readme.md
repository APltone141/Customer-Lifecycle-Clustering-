# 📁 notebooks/

This folder contains Jupyter Notebooks used to conduct the full analysis.

## Files

- **rfm_clustering.ipynb**  
  The main notebook for the entire customer segmentation workflow, including:
  - Data Cleaning
  - RFM Feature Engineering
  - Normalization
  - KMeans Clustering
  - Elbow & Silhouette Analysis
  - Visualization
  - Segment Interpretation

## Usage
To run the notebook:
1. Open in Jupyter or VSCode.
2. Ensure required libraries are installed (see `requirements.txt`).
3. Run cells step-by-step from top to bottom.

## Output
Generates a segmented customer dataframe (`rfm_segmented.csv`) and visualizations stored in `images/`.
