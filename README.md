# Anomaly Detection in Network Traffic Using Unsupervised Clustering

## 📘 Overview
This project applies unsupervised learning to detect anomalies in high‑dimensional network traffic. PCA is used for dimensionality reduction, UMAP for visualization, and DBSCAN, K‑Means, and Hierarchical Clustering for anomaly detection. Hierarchical clustering achieved the best performance based on Silhouette score.

## 📂 Dataset
UNSW‑NB15 dataset from Kaggle:  
https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15

Download the dataset and place all CSV files inside a folder named `data/`.

## 🔧 Methods
- PCA for dimensionality reduction  
- UMAP for 2D visualization  
- DBSCAN, K‑Means, Hierarchical Clustering  
- Outlier detection using noise labels or centroid distance  
- Validation: Silhouette Score, ANOVA, ARI, NMI  

## 📊 Results
- Hierarchical: **Silhouette = 0.7801**  
- K‑Means: 0.3957  
- DBSCAN: 0.2042  
- Temporal analysis revealed clear hourly anomaly spikes.

## ▶️ How to Run
1. Download dataset → place in `data/`  
2. Open the notebook: code.ipynb
3. Run all cells.

## 🛠️ Technologies
Python, NumPy, Pandas, Scikit‑learn, Matplotlib, Seaborn, UMAP

## 📄 License
MIT License

