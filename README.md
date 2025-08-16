# Task-8

Task 8 – Customer Segmentation using K-Means

This task applies K-Means Clustering to segment mall customers into distinct groups based on their purchasing behavior. The dataset used is Mall_Customers.csv.

Process Overview

1. Import Libraries – Load Python libraries (pandas, matplotlib, scikit-learn).

2. Load Dataset – Read Mall_Customers.csv into a DataFrame.

3. Data Preprocessing - Drop CustomerID (irrelevant for clustering), Encode Gender into numeric values (Male = 1, Female = 0), Select key features like Annual Income and Spending Score for clustering
   
4. Determine Optimal Clusters (K) – Use the Elbow Method to identify the best number of clusters.

5. Apply K-Means – Train the model (e.g., K=5) and assign each customer to a cluster.

6. Visualization – Scatter plot of customer segments with cluster centroids.

7. Model Evaluation – Compute Silhouette Score to evaluate clustering quality.

8. Save Results – Append cluster labels to the dataset for further analysis.

Key Learning Outcomes

1. Practical use of unsupervised learning for market segmentation.

2. Importance of feature selection in clustering performance.

3. How to use the Elbow Method and Silhouette Score for cluster validation.

4. Data visualization for better understanding of customer groups.
