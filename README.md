# Exploring-Unsupervised-Clustering-Techniques-on-Wine-Data
Exploring Unsupervised Clustering Techniques on Wine Data: A Comparative Analysis of K-Means, Agglomerative Clustering, and DBSCAN
## Project Overview

This project explores the application of unsupervised machine learning techniques on the Wine dataset, which contains chemical properties of different wine cultivars grown in the same region of Italy. The objective is to identify natural groupings of wines based on chemical composition using clustering algorithms such as:

- K-Means
- Agglomerative Hierarchical Clustering
- DBSCAN (Density-Based Spatial Clustering)

The performance of each clustering algorithm is evaluated using Silhouette Scores, cluster interpretability, and visualizations generated through PCA and t-SNE.

## Dataset

The dataset used is the Wine dataset from the UCI Machine Learning Repository, which includes the results of a chemical analysis of 178 wine samples with 13 continuous features.

- 178 samples of wine
- 13 features including Alcohol content, Malic acid, Ash, Color intensity, Proline, and others

For more details on the dataset and to access it, refer to the data_link.txt file.

## Key Analysis Steps

1.Exploratory Data Analysis (EDA): Visualizations and statistical summaries to understand feature distributions and correlations.
2.Feature Scaling: Standardizing the dataset using StandardScaler to normalize chemical measurements for clustering.
3.Clustering Techniques:
	- K-Means
	- Agglomerative Hierarchical Clustering (Ward, Complete, Average, and Single Linkage methods)
	- DBSCAN
4.Evaluation and Comparison of Models: Silhouette Scores, PCA plots, and interpretability of clusters to assess each model’s performance.
5.Cluster Interpretation:
	- Cluster Centers interpretation for K-Means
	- Heatmap of Cluster Means
	- Cluster Purity Analysis
6.	Parameter Tuning: Experimentation with various parameter values (e.g., number of clusters in K-Means and linkage methods in Agglomerative Clustering).


Project Results

Key Findings

- K-Means clustering performed the best, with compact and well-separated clusters, particularly for wines with high alcohol and proline content.
- Agglomerative Hierarchical Clustering provided more flexible, hierarchical relationships between data points, with Ward linkage performing similarly to K-Means.
- DBSCAN struggled to find meaningful clusters for this dataset, likely due to the nature of the chemical properties and the distribution of data points.
