# Iris-Cluster-Prediction
 predict the optimum number of clusters and represent it visually, from the given ‘Iris’ dataset
 This project predicts the optimal number of clusters for the Iris dataset and visually represents the results using unsupervised machine learning.

## Problem Statement

The Iris dataset contains information about three species of iris flowers with features like sepal length, sepal width, petal length, and petal width. The objective is to determine the ideal number of clusters that best represent the underlying structure of the data.

## Analysis Steps

1. **Data Loading and Preprocessing**: The dataset is loaded and prepared for clustering.

2. **Elbow Method**: We employ the Elbow Method to determine the optimal number of clusters. It identifies a 'k' where the reduction in the sum of squared distances (inertia) slows down.

3. **Silhouette Score**: We use the Silhouette Score to validate the chosen 'k.' It measures the quality of the clusters.

4. **Clustering**: K-Means clustering is performed with the chosen 'k' to assign labels to each data point.

5. **Visualization**: The results are visually represented to showcase the separation of clusters.

## Results

- The Elbow Method suggests the optimal number of clusters is 3.
- The Silhouette Score supports the choice of 3 clusters.
- Clustering is performed with K-Means (k=3).
- Visualizations demonstrate the separation of species based on petal length and width.


## Dataset

The Iris dataset used in this project is available at [this link](https://bit.ly/3kxTdox).


---
BY :- Raman Kumar Gyan












