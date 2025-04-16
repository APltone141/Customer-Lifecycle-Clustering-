# 📁 images/

This folder stores all visualization images generated during analysis and for presentation.

## Files

- **segment_distribution.png**  
  A pie chart showing the percentage distribution of each customer segment.

- **rfm_boxplot_by_segment.png**  
  A set of boxplots comparing Recency, Frequency, and Monetary values across segments.

## Usage
These images are used in:
- Jupyter Notebook reports
- Streamlit dashboard app
- README or presentation materials

You can load them into your report using:
```python
from PIL import Image
from IPython.display import display
img = Image.open("images/segment_distribution.png")
display(img)

