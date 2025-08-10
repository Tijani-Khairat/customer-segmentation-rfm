Customer Segmentation using RFM Analysis and Clustering
📌 Project Overview
This project applies RFM (Recency, Frequency, Monetary) analysis combined with unsupervised machine learning to segment customers for targeted marketing strategies. Three clustering algorithms were evaluated — K-Means, Agglomerative Clustering, and DBSCAN — with K-Means achieving the best performance based on evaluation metrics.

🎯 Purpose
The goal is to identify distinct customer groups from transactional data to support data-driven marketing, retention campaigns, and personalized offers.

📊 Dataset
Source: Anonymized retail transaction data.

Format: CSV, containing customer IDs, transaction dates, and purchase amounts.

Processing: Aggregated into RFM scores for each customer.

🛠 Methodology
Data Cleaning: Removed duplicates, handled missing values.

Feature Engineering: Computed Recency, Frequency, and Monetary values per customer.

Scaling: Standardized RFM features for fair clustering.

Clustering: Applied and compared K-Means, Agglomerative, and DBSCAN.

Evaluation: Used Silhouette Score, Davies-Bouldin Index, Calinski-Harabasz Index, and Adjusted Rand Index to compare performance.

Insights: K-Means produced clearer, more meaningful customer segments.

📈 Key Results
Best Model: K-Means (highest Silhouette score, lowest Davies-Bouldin Index).

Finding: Rule-based segmentation aligned poorly with ML clusters (ARI ~ 0.099).

Impact: Demonstrates the superiority of ML-based segmentation in capturing complex customer patterns.

