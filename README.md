# DA5401 Assignment 5: Visualizing Data Veracity Challenges in Multi-Label Classification

## Overview
This project explores the challenges of multi-label classification in real-world biological data using advanced non-linear dimensionality reduction techniques (t-SNE and Isomap). The Yeast gene expression dataset is analyzed to visually inspect data veracity issues such as noisy labels, outliers, and hard-to-learn samples.

## Contents
- `Assignment_5.ipynb`: Main Jupyter notebook with all code, visualizations, and analysis.
- `yeast.arff`: Dataset file (not included here; download from the MULAN repository).

## Key Steps
- **Preprocessing:**
  - Data loading, dimensionality check, label simplification, and feature scaling.
- **Exploratory Data Analysis (EDA):**
  - Feature distributions, label co-occurrence, and summary statistics.
- **t-SNE & Isomap:**
  - Dimensionality reduction, parameter exploration, and 2D visualization.
- **Data Veracity Inspection:**
  - Identification and quantification of noisy labels, outliers, and ambiguous samples.
- **Quantitative Analysis:**
  - Outlier detection, ambiguous point count, and silhouette scores.
- **Discussion:**
  - Comparison of t-SNE and Isomap, implications for classification, and real-world considerations.

## How to Run
1. Download the Yeast dataset (`yeast.arff`) from the [MULAN repository](http://mulan.sourceforge.net/datasets-mlc.html).
2. Place the dataset in the appropriate directory and update the file path in the notebook if needed.
3. Open `Assignment_5.ipynb` in Jupyter or VS Code.
4. Run all cells in order for a complete analysis.

## Requirements
- Python 3.8+
- numpy, pandas, matplotlib, seaborn, scikit-learn, scipy

## References
- van der Maaten & Hinton (2008): t-SNE
- Tenenbaum et al. (2000): Isomap
- Zhang & Zhou (2014): Multi-label learning review
- scikit-learn, seaborn documentation

---

**Author:** Basavaraj A Naduvinamani  
**Roll No.:** DA25C005
