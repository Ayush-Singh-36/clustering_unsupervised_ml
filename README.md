Clustering the Iris Dataset
This project serves as a comprehensive guide to understanding Unsupervised Learning through clustering techniques. We utilize the famous Iris dataset to demonstrate how data can be grouped based on inherent features without prior labels.

Key Objectives
Algorithm Comparison: Implementing and comparing Centroid-based (K-Means) and Density-based (DBSCAN) clustering.
Optimal Parameter Selection: Using the Elbow Method to calculate inertia across different values of  k  to identify the most natural groupings.
Data Visualization: Creating 2D scatter plots to visualize cluster formation and centroid locations.
Methodology
1. K-Means Clustering
We apply K-Means to partition the dataset into  k  clusters. The project illustrates how inertia (within-cluster sum-of-squares) decreases as  k  increases, helping us find the 'elbow' point for optimal clustering.

2. DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
Unlike K-Means, DBSCAN identifies clusters based on the density of data points. This section demonstrates how to handle data that may not have clearly defined spherical boundaries and how the algorithm identifies outliers.

3. Feature Selection
To simplify visualization, we focus on key numeric features like sepal length and petal length, demonstrating how even a subset of dimensions can reveal significant patterns in the data.

Summary
By the end of this project, you will have a clear understanding of how different clustering parameters affect the resulting groups and how to evaluate the performance of unsupervised models visually and mathematically.

