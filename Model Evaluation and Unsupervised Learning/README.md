# 🍷 Wine Classification & Clustering

This project explores both **Supervised** and **Unsupervised** Learning techniques on the UCI Wine Dataset using `sklearn`.

## 🧠 Part A: Model Evaluation (Supervised)
Used a trained classifier to evaluate:
- ✅ Accuracy, Precision, Recall, F1-Score
- ✅ Confusion Matrix
- ✅ ROC Curve and AUC (Multiclass)

## 🔍 Part B: Clustering & Dimensionality Reduction (Unsupervised)
Applied unsupervised methods on the same dataset:
- ✅ K-Means Clustering
- ✅ Elbow Method to find optimal clusters
- ✅ PCA to reduce dimensions and visualize clusters

## 📊 Dataset
- UCI Wine Dataset (from `sklearn.datasets.load_wine()`)

## 📌 Tools Used
- Python
- Jupyter Notebook
- Scikit-learn
- Matplotlib / Seaborn

## 🎯 Output Highlights
- ROC AUC: 1.00 (All Classes)
- Optimal Clusters (from Elbow): 3
- PCA Variance Ratio: ~99.8% by 1st component
