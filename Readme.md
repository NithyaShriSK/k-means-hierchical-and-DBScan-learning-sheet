# Clustering Learning Sheet

A concise and practical learning resource for practicing and understanding three fundamental clustering algorithms: **K‑Means**, **Hierarchical (Agglomerative)**, and **DBSCAN**. This notebook-style learning sheet is perfect for students and data scientists exploring unsupervised learning basics.

---

##  Repository Structure

```
k-means-hierchical-and-DBScan-learning-sheet/
├── clustering_learning_sheet.ipynb
└── README.md
```

- **`clustering_learning_sheet.ipynb`**  
  A Jupyter Notebook containing minimal, clean clustering examples using synthetic data with inline comments for clarity.

---

##  What’s Inside the Notebook

1. **Data Generation**  
   - Creates synthetic blob data using `sklearn.datasets.make_blobs`, ideal for demonstrating clustering behavior.

2. **K‑Means Clustering**  
   - Simple implementation with `KMeans` from `sklearn.cluster`.
   - Visualizes clusters with a clear scatter plot.

3. **Hierarchical (Agglomerative) Clustering**  
   - Uses `AgglomerativeClustering`.
   - Demonstrates cluster formation via hierarchical merging.

4. **DBSCAN Clustering**  
   - Density-based clustering using `DBSCAN`.
   - Highlights how outliers are labeled as `-1` and clusters form based on density, not centroids.

The notebook displays clear visual outputs and section headers, making it ideal for reference or teaching.

---

##  Quick Comparison Table

| Algorithm   | Type            | Pros                                         | Cons                                      |
|-------------|-----------------|----------------------------------------------|-------------------------------------------|
| K‑Means     | Centroid-based  | Fast, scalable, easy to understand           | Assumes spherical clusters, needs `k`      |
| Hierarchical| Hierarchical    | No need to predefine clusters, builds dendrogram | Not scalable for large datasets         |
| DBSCAN      | Density-based   | Finds clusters of any shape, handles noise    | Sensitive to ε (eps) and `min_samples`     |

---

##  Usage Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/NithyaShriSK/k-means-hierchical-and-DBScan-learning-sheet.git
   ```
2. Run the notebook:
   - Launch via **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.
   - Execute cells in order to explore clustering visually.

---

##  Why Use This Learning Sheet?

- **Lean & Focused**: No extra dependencies—just core clustering code and plots.
- **Visual Intuition**: Compare algorithms side-by-side to understand how they differ in cluster formation.
- **Great for Beginners**: Clean code, concise comments, and understandable flow.

---

##  License

Open-sourced under the **MIT License** — feel free to use, adapt, and share!

---

##  Contributing

Contributions are welcome! Whether you want to:
- Add more clustering methods (like spectral clustering or Gaussian Mixtures),
- Include clustering quality metrics (e.g., Silhouette Score),
- Or enhance visualization (e.g., 3D plots or dendrograms),

…please submit a pull request or open an issue.

---

##  Author(s)

**Nithya Shri**  
Self-directed learning on clustering techniques using Python and scikit-learn.

---

Happy Clustering! 🚀
