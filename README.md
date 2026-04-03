# 🚀 Unsupervised Learning: Clustering & High-Dimensional Data Visualization

A structured machine learning project focused on **implementing and analyzing unsupervised learning algorithms** across synthetic and real-world datasets.

This project emphasizes **algorithm behavior, data characteristics, and visualization pipelines**, rather than just API usage.

---

## 🚀 Project Overview

This repository explores:

- Multiple clustering paradigms:
  - Density-based
  - Probabilistic
  - Hierarchical
- Dimensionality reduction for visualization
- Behavior of models under different data distributions

Focus:

> Understanding **how unsupervised models behave**, not just applying them.

---

## 🎯 Objectives

- Compare clustering algorithms across different data types  
- Understand how:
  - data distribution
  - feature scaling
  - algorithm assumptions  
  affect clustering results  
- Build visualization pipelines for high-dimensional data  
- Apply clustering to real-world segmentation problems  

---

## 🧠 Algorithms Covered

| Category        | Techniques                     |
|----------------|------------------------------|
| Density-Based   | DBSCAN                        |
| Probabilistic   | Gaussian Mixture Models (GMM) |
| Hierarchical    | Agglomerative Clustering      |
| Dimensionality  | PCA, t-SNE                    |

---

## 📂 Project Structure

```bash
UNSUPERVISED_ML_CLUSTERING/
│
├── data/
│   └── country-data.csv
│
├── tsne_vs_pca_visualization_mnist.ipynb
├── gmm_probabilistic_clustering_demo.ipynb
├── dbscan_density_based_clustering.ipynb
├── country_segmentation_using_hierarchical_clustering.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Implementation Breakdown

### 1️⃣ PCA vs t-SNE (High-Dimensional Visualization)

- Reduces dimensionality of MNIST dataset  
- PCA → linear projection  
- t-SNE → non-linear embedding  

**Key Understanding:**

- PCA preserves global variance  
- t-SNE preserves local structure  

---

### 2️⃣ Gaussian Mixture Models (GMM)

- Probabilistic clustering approach  
- Assigns **soft cluster memberships**  
- Models data as Gaussian distributions  

**Key Understanding:**

- Handles overlapping clusters better than KMeans  

---

### 3️⃣ DBSCAN (Density-Based Clustering)

- Detects clusters based on density  
- Identifies noise points  

**Key Understanding:**

- Works well for non-linear cluster shapes  
- Does not require predefined number of clusters  

---

### 4️⃣ Hierarchical Clustering (Country Segmentation)

- Real-world dataset (country socio-economic data)  
- Uses dendrogram for cluster formation  

**Key Understanding:**

- Provides interpretable cluster hierarchy  
- Useful for segmentation problems  

---

## 🧪 Workflow

```
Data → Preprocessing → Scaling → Clustering → Visualization → Interpretation
```

---

## 📊 Key Observations

- Clustering performance is highly data-dependent  
- DBSCAN handles noise better than centroid-based methods  
- GMM provides flexibility for overlapping clusters  
- PCA vs t-SNE trade-off:
  - PCA → faster, global structure  
  - t-SNE → better visualization, slower  

---

## 🛠️ Tech Stack

- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn, Plotly  
- Scikit-learn  

---

## 📦 Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

```bash
jupyter notebook
```

Run notebooks individually based on use case.

---

## ⚠️ Limitations

- No cluster evaluation metrics (silhouette score, etc.)  
- Limited hyperparameter tuning  
- No unified pipeline implementation  
- Notebook-based (not modularized)  

---

## 🚀 Future Improvements (High Impact)

### 1️⃣ Evaluation Framework

- Silhouette Score  
- Davies-Bouldin Index  
- Cluster validation  

---

### 2️⃣ System Upgrade

- Build clustering pipeline module  
- Add preprocessing + clustering integration  
- Standardize experiments  

---

### 3️⃣ Scalability

- Apply on larger datasets  
- Experiment with MiniBatch / distributed clustering  

---

## 🎯 What This Project Demonstrates

- Strong understanding of unsupervised learning algorithms  
- Ability to analyze model behavior across data types  
- Experience with high-dimensional data visualization  
- Practical intuition for clustering techniques  

---

## 📌 Key Takeaway

Unsupervised learning is **data-driven** — the effectiveness of clustering depends more on **data representation and preprocessing** than the algorithm itself.

---

## 👤 Author

**Rudra Tyagi**  
ML Systems | MLOps | AI Infrastructure  