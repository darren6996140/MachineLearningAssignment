# Principal Component Analysis (PCA) Enhancement

This lab explores **Principal Component Analysis (PCA), t-SNE, and Singular Value Decomposition (SVD)** for reducing high-dimensional data while preserving meaningful structure.

## Key Enhancements:
- **PCA Implementation**: Reduced feature dimensions while retaining variance.
- **t-SNE Visualization**: Captured non-linear relationships for better clustering insights.
- **SVD Analysis**: Applied as an alternative to PCA for feature extraction.
- **Computational Efficiency Comparison**: Evaluated speed and effectiveness of each method.
- **Cluster Visualization**: Compared the ability of PCA, t-SNE, and SVD to separate data visually.

## Dataset:
- **Iris Dataset** – A well-known dataset with numerical features, ideal for testing dimensionality reduction methods.

## Notable Results:
- **Explained Variance (PCA)**:
  - Component 1: `72.96%`
  - Component 2: `22.85%`
  - **Total Variance Captured (2D PCA):** `96%`
- **Computation Time (Seconds)**:
  - PCA: `0.0010`
  - t-SNE: `0.4396`
  - SVD: `0.0010`
- **Key Insights**:
  - **PCA** preserves the global structure and is computationally efficient.
  - **t-SNE** captures local clusters but is computationally expensive.
  - **SVD** works well with sparse data and compresses information effectively.

## Advantages & Disadvantages:
| Method | Advantages | Disadvantages |
|--------|------------|--------------|
| **PCA** | Fast, preserves global variance, interpretable components | Assumes linearity, sensitive to outliers |
| **t-SNE** | Captures complex non-linear relationships, excellent for visualization | Slow, parameter-sensitive, does not preserve global structure |
| **SVD** | Handles sparse data well, used in NLP & recommendation systems | Computationally heavy, lacks interpretability |

## Folder Contents:
- `3_LabEnhancements_PCA.ipynb` – Jupyter Notebook with full implementation.
- `README.md` – Overview of the lab.

A **detailed explanation** of each step is available inside the Jupyter Notebook.
