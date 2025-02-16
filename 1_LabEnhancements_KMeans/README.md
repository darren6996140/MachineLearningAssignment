# K-Means Clustering Enhancement

This lab applies **K-Means Clustering** to an **e-commerce dataset**, with preprocessing, feature engineering, and comparison with **Agglomerative Clustering**.

## Key Enhancements:
- **Preprocessing**: Handling missing values, scaling, log transformation.
- **Feature Engineering**: Created `ReviewScore` for better clustering.
- **Clustering**: Used **Elbow Method** to find optimal clusters.
- **PCA**: Reduced dimensions for better visualization.
- **Business Insights**: Identified sales trends for product categories.

## Notable Results:
- **Silhouette Scores**: 
  - K-Means: `0.16` → PCA-KMeans: `0.34`
  - Agglomerative: `0.10` → PCA-Agglomerative: `0.30`

## Files:
- `Lab_KMeans.ipynb` – Full implementation.
- `README.md` – Overview of enhancements.
- 'ecommerce_product_dataset' -dataset
- 'ecommerce_product_dataset2' - dataset2

For more details, please refer to the Jupyter Notebook.
