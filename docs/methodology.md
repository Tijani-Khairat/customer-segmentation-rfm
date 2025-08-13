Methodology Summary
Why RFM was chosen
RFM (Recency, Frequency, Monetary) analysis was selected because it is a proven, interpretable framework for customer segmentation. It directly measures customer engagement and value, making it suitable for marketing applications. RFM reduces dimensionality by focusing on the three most impactful behavioral indicators.

Why scaling was necessary
RFM values have different ranges (e.g., Monetary could be in thousands, Recency in days). Without scaling, features with larger values would dominate clustering results. StandardScaler was applied to normalize all features to the same scale, ensuring fair contribution in distance-based algorithms like K-Means.

Why K-Means performed best
Three clustering algorithms—K-Means, Agglomerative Clustering, and DBSCAN—were tested. K-Means achieved the best performance based on evaluation metrics, producing well-separated and balanced clusters with interpretable centroids. It also had the advantage of computational efficiency and stability with our dataset.

Summary of evaluation metrics
- Silhouette Score: K-Means produced the highest silhouette score, indicating well-defined and separated clusters.

- Davies-Bouldin Index: K-Means had the lowest DBI, meaning clusters were compact and distinct.

- Adjusted Rand Index: Comparison between rule-based segments and K-Means clusters yielded an ARI of 0.0998, confirming low agreement and validating that K-Means uncovered patterns that rules missed.



