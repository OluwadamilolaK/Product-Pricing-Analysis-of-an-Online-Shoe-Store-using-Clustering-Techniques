# Product-Pricing-Analysis-of-an-Online-Shoe-Store-using-Clustering-Techniques
# Overview
The goal of this task was to apply clustering algorithms to the UCI Online Retail Store Dataset, focusing on customer segmentation and behavior analysis. The dataset consists of 3,268 instances and 10 features, offering an in-depth view of customer interactions. This research aimed to group similar data points into clusters to identify natural patterns and compute features of these clusters, ultimately to gain actionable insights.
# Data Cleaning and Transformation
Data processing involved handling minimal missing values using the dropna() method to preserve the original distribution. Data encoding was performed for categorical variables. All variables were on the same scale, preventing any feature from dominating the model due to its scale.
# EDA
Visual exploration was conducted to understand feature distribution,. Two clustering algorithms, K-Means and Hierarchical Clustering, were applied. The optimal number of clusters was determined using the WCSS Elbow Method and Silhouette Scoring Method. The analysis included examining the distribution of the 'Quantity' feature across clusters through boxplots and visualizing clusters in 2D scatter plots. Clusters were characterized by various purchasing behaviors: mainstream transactions, higher value transactions, bulk purchases, and outlier transactions.
# Recommendation
K-Means Clustering is recommended due to its simplicity, interpretability, scalability, and effectiveness in identifying customer behavioral patterns. It provided clear separation in scatterplots, well-defined centroids, and actionable insights into customer behavior. Hierarchical Clustering, while providing an alternative perspective, offered less clarity and separation compared to K-Means.
# Clustering Algorithm - Results of Analysis
The analysis with K-Means and Hierarchical Clustering algorithms resulted in the following findings:
# K-Means Clustering:
Effectively segmented the dataset into four distinct clusters, each characterized by unique purchasing behaviors. The clusters were well-separated with clear centroids.. The silhouette score for the optimal number of clusters (3) was 0.703, indicating a good fit.
# Hierarchical Clustering:
Also resulted in four clusters, but the separation and interpretability of these clusters were less pronounced compared to K-Means. This method provided a different perspective on clustering but did not offer the same level of clarity.
The clustering analysis provided valuable insights into customer behavior, particularly in terms of purchasing patterns and potential market segmentation strategies.

