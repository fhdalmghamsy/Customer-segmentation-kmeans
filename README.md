# Customer Segmentation using K-Means Clustering

A machine learning project that segments mall customers into distinct groups using clustering algorithms, enabling data-driven marketing strategies. This work is based on a peer-reviewed paper published in **IJEECS** (Paper ID# 45927).

## 📊 Overview

Customer segmentation helps businesses understand their customers better by grouping them based on shared characteristics. This project compares **10 different clustering algorithms** on a real-world dataset of **15,079 customers** to identify the optimal segmentation approach.

## 🎯 Problem Statement

Businesses often struggle to design targeted marketing campaigns because they treat all customers the same way. By clustering customers based on behavioral and demographic features, businesses can tailor strategies for each segment — improving marketing ROI and customer satisfaction.

## 📁 Dataset

- **Source:** Shopping Mall Customer Segmentation Data (Kaggle)
- **Size:** 15,079 customers
- **Features:** Age, Annual Income, Spending Score, and other demographic attributes

## 🔬 Methodology

1. **Data Preprocessing:** Cleaning, scaling, and preparing features for clustering
2. **Algorithm Comparison:** Evaluated 10 clustering algorithms, including K-Means, Gaussian Mixture Models (GMM), Hierarchical Clustering, and more
3. **Evaluation Metric:** Silhouette Score used to measure cluster quality
4. **Optimal Cluster Selection:** Elbow method and Silhouette analysis to determine the best K value

## 📈 Results

| Algorithm | Silhouette Score |
|-----------|------------------|
| **GMM**   | **0.4063** (highest) |
| **K-Means** | 0.4062 (close second) |

- **Optimal number of clusters (K):** 4
- GMM and K-Means performed almost identically, with K-Means chosen for production use due to its simplicity, speed, and interpretability for business stakeholders.

## 🛠️ Tools & Technologies

- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Clustering algorithms: K-Means, GMM, Hierarchical, DBSCAN, and others

## 📄 Published Research

This project is the foundation of a peer-reviewed paper:

**"Customer Segmentation Using K-Means Clustering"**
Published in *International Journal of Electrical and Computer Engineering (IJEECS)*
Author: Fahad Almghamsy
Paper ID: 45927

## 🚀 Future Work

- Build an interactive Power BI / Streamlit dashboard for cluster visualization
- Deploy the model as an API for real-time customer classification
- Extend analysis to include RFM (Recency, Frequency, Monetary) features

## 👤 Author

**Fahad Almghamsy**
Data Science & Analytics Student, University of Ha'il
