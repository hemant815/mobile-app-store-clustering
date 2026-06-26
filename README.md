# 📱 Mobile App Store Clustering

## 📌 Overview

This project applies **unsupervised machine learning** to segment Google Play Store applications into meaningful groups based on their characteristics. Using clustering techniques, the project identifies hidden patterns among apps without predefined labels and provides business-oriented insights into different app segments.

The workflow includes data preprocessing, feature engineering, feature scaling, clustering, cluster evaluation, dimensionality reduction, and business interpretation.

---

## 🎯 Project Objective

The primary objective of this project is to discover meaningful groups of mobile applications by analyzing features such as:

* App Category
* Rating
* Number of Installs
* Price
* App Size
* Content Rating

The project compares **K-Means Clustering** and **Agglomerative Clustering** to determine the most effective clustering algorithm for this dataset.

---

## 📂 Dataset

* **Dataset:** Google Play Store Applications
* **Sample Size Used:** 10,000 applications
* **Reason:** A representative sample was selected to reduce computational cost while preserving the overall characteristics of the original dataset.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* SciPy
* Kneed

---

## 📊 Project Workflow

1. Data Loading
2. Data Understanding
3. Data Cleaning
4. Feature Engineering
5. Feature Selection
6. Feature Scaling using StandardScaler
7. Optimal Cluster Selection

   * Elbow Method
   * Knee Locator
   * Silhouette Score
8. K-Means Clustering
9. Agglomerative Clustering
10. PCA Visualization
11. Cluster Profiling
12. Business Insights

---

## ⚙️ Machine Learning Techniques

### K-Means Clustering

Used as the primary clustering algorithm to partition applications into meaningful groups.

### Agglomerative Clustering

Implemented to compare clustering performance with K-Means.

### PCA (Principal Component Analysis)

Applied to reduce the high-dimensional feature space into two principal components for visualization purposes.

---

## 📈 Cluster Evaluation

The clustering models were evaluated using:

* Elbow Method
* Knee Locator
* Silhouette Score
* PCA Visualization

Based on these evaluation techniques, **K = 3** was selected as the optimal number of clusters.

---

## 📊 Cluster Insights

Three meaningful application segments were identified:

### 🎮 Cluster 0 — Entertainment & Social Apps

* Entertainment-focused applications
* Social networking apps
* Media and gaming-related apps

### 💼 Cluster 1 — Productivity & Education Apps

* Business applications
* Educational apps
* Productivity tools
* Finance applications

### 📚 Cluster 2 — Content & Personalization Apps

* Music & Audio
* Books & Reference
* Photography
* News & Magazines
* Personalization applications

---

## 💡 Business Insights

* Entertainment and Social applications form the largest user segment.
* Productivity and Education applications demonstrate higher engagement and adoption.
* Content and Personalization applications represent a smaller niche segment with specialized user interests.

---

## 📁 Repository Structure

```
mobile-app-store-clustering/
│
├── Mobile_App_Store_Clustering.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── dataset/
│   └── google-appstore_sample.csv
└── images/
    ├── elbow_method.png
    ├── silhouette_score.png
    ├── pca_clusters.png
    └── agglomerative_clusters.png
```

---

## 🚀 Future Improvements

* Experiment with DBSCAN and Gaussian Mixture Models.
* Build an interactive Streamlit dashboard for cluster exploration.
* Perform hyperparameter tuning for clustering algorithms.
* Add automated cluster profiling and reporting.

---

## 📌 Key Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Feature Scaling
* Unsupervised Learning
* K-Means Clustering
* Agglomerative Clustering
* Cluster Evaluation
* PCA
* Data Visualization
* Business Insight Generation

---

## ⭐ Results

This project successfully segmented Google Play Store applications into three meaningful groups using unsupervised machine learning. Among the evaluated algorithms, **K-Means Clustering** achieved the best clustering performance based on the **Silhouette Score**, while **Agglomerative Clustering** was used for comparison and validation. The identified clusters provide valuable insights into different categories of mobile applications and their characteristics.
