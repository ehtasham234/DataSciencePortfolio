# 🛍️ Customer Segmentation using K-Means Clustering

## 📘 Overview
This project applies **K-Means clustering** to segment mall customers based on their **Age**, **Annual Income**, and **Spending Score**.  
The goal is to identify distinct customer groups for targeted marketing strategies.

---

## 🧩 Dataset
Dataset: [Mall Customers Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

---

## ⚙️ Methods Used
- Data preprocessing and scaling using **StandardScaler**
- **Elbow Method** to determine optimal cluster count
- **K-Means Clustering** for segmentation
- Visualization using **Matplotlib** and **Seaborn**

---

## 📊 Cluster Summary

| Cluster | Average Age | Annual Income (k$) | Spending Score |
|----------|--------------|-------------------|----------------|
| 0 | 55.3 | 47.6 | 41.7 |
| 1 | 32.9 | 86.1 | 81.5 |
| 2 | 25.8 | 26.1 | 74.8 |
| 3 | 26.7 | 54.3 | 40.9 |
| 4 | 44.4 | 89.8 | 18.5 |

---

## 📈 Visuals
- `Elbow_Method.png` → Finding optimal number of clusters  
- `Annual_Income_Spending_Score.png` → Income vs Spending Score  
- `Customer_Segments.png` → Final segmentation visualization  
- `customer_clusters.png` → Clustered scatter plot  

---

## 🧠 Insights
- **Cluster 1** → Young, high-income, high spenders → *Premium segment*  
- **Cluster 2** → Young, low-income, high spenders → *Impulsive buyers*  
- **Cluster 4** → Older, high-income, low spenders → *Conservative buyers*  

---

## 🚀 Next Steps
- Try other clustering algorithms like **DBSCAN** or **Hierarchical Clustering**
- Add customer demographics (e.g., Gender, Profession)
- Use PCA for dimensionality reduction before clustering
