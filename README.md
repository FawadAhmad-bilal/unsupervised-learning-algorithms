# 🤖 Unsupervised Learning Algorithms

A collection of unsupervised learning notebooks covering clustering and association rule mining algorithms, implemented in Python using scikit-learn and mlxtend.

---


## 📁 Notebooks

| Notebook | Algorithm | Dataset |
|---|---|---|
| `k-means_clustring.ipynb` | K-Means Clustering | Titanic (Seaborn) |
| `wine_k-means_clustring.ipynb` | K-Means Clustering | Wine Dataset |
| `Hierarchical_Clustering.ipynb` | Hierarchical / Bisecting K-Means | GLUE Benchmark (Seaborn) |
| `DBSCAN_CLUSTRAING.ipynb` | DBSCAN | Iris (Seaborn) |
| `overview_on_all_algorithems.ipynb` | K-Means, Hierarchical, DBSCAN | Titanic (Seaborn) |
| `apirior.ipynb` | Apriori | Online Retail |
| `paritice_on_association.ipynb` | Apriori (Practice) | Online Retail |
| `FP-Growth_unsupervised.ipynb` | FP-Growth | Online Retail |

---

## 🧠 Algorithms Covered

### Clustering

**K-Means Clustering**
- Partitions data into K clusters by minimizing intra-cluster distance
- Uses Elbow Method to find optimal K
- Applied on Titanic and Wine datasets

**Hierarchical Clustering**
- Builds a tree of clusters (dendrogram) using Agglomerative or Divisive approach
- Applied on GLUE NLP benchmark dataset with Label Encoding

**DBSCAN (Density-Based Spatial Clustering)**
- Groups points based on density; automatically detects outliers as noise
- Parameters: `eps=0.5`, `min_samples=5`
- Applied on Iris dataset; evaluated with Silhouette Score

### Association Rule Mining

**Apriori**
- Finds frequent itemsets using a bottom-up candidate generation approach
- Parameters: `min_support=0.04`, `max_len=2`
- Applied on Online Retail transaction data

**FP-Growth (Frequent Pattern Growth)**
- Faster alternative to Apriori; uses FP-tree structure, no candidate generation
- Parameters: `min_support=0.03`, `max_len=3`
- Rules filtered by `confidence ≥ 0.5` and `lift > 3`

---

## 🛠️ Tech Stack

- Python 3.x
- pandas, numpy
- scikit-learn
- seaborn, matplotlib
- mlxtend

---

## ⚙️ Setup

```bash
pip install pandas numpy scikit-learn seaborn matplotlib mlxtend openpyxl
```

---

## 👤 Author

**Fawad Ahmad Bilal**  
BSAI Student — University of Haripur, Pakistan  
GitHub: [github.com/FawadAhmad-bilal](https://github.com/FawadAhmad-bilal)

