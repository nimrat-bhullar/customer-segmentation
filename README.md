# 🛍️ Customer Segmentation Using KMeans & DBSCAN Clustering

This project applies **unsupervised machine learning** techniques (KMeans and DBSCAN) to segment customers based on their demographics and behavior, using a classic mall customer dataset.

## 📁 Dataset

The dataset includes the following customer features:

- **Gender**
- **Age**
- **Annual Income (k$)**
- **Spending Score (1-100)**

> 📌 Note: This project uses a modified or cleaned version of the `Mall_Customers.csv` dataset.

---

## 📊 Objective

To cluster customers into meaningful groups that help businesses:

- 🎯 Target marketing strategies effectively
- 💸 Understand spending behavior
- 📈 Improve customer experience and loyalty

---

## 🧠 Algorithms Used

- **KMeans Clustering**
  - `init='k-means++'`
  - Optimal number of clusters selected using the **Elbow Method** and **Silhouette Score**
  
- **DBSCAN Clustering**
  - Optimal `eps` value chosen using the **k-distance graph (knee method)**
  - Automatically detects number of clusters and noise points
  - Robust to outliers and arbitrary shapes

---

## ⚙️ Tools & Libraries

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---
