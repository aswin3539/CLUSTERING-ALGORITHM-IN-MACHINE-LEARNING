# CLUSTERING-ALGORITHM-IN-MACHINE-LEARNING
# Iris Dataset

# Dataset

The Iris dataset from sklearn is used for this task. The dataset includes measurements of iris flowers across three species.

# Key Components

# 1. Loading and Preprocessing

Steps Taken:

Loaded the dataset using sklearn.datasets.load_iris.

Dropped the species column as clustering is unsupervised.

# 2. Clustering Algorithms Implemented

# KMeans Clustering:

 Description: A partition-based algorithm that minimizes intra-cluster variance by assigning data points to k clusters.

 Why Suitable: The Iris dataset has numerical features, making it ideal for KMeans clustering.

 Implementation: Applied KMeans with 3 clusters and visualized the clusters using scatter plots.

# Hierarchical Clustering:

Description: A tree-based algorithm that groups data points based on similarity, either in a bottom-up (agglomerative) or top-down (divisive) manner.

Why Suitable: It provides a dendrogram for visualizing the hierarchical relationships among data points.

Implementation: Applied hierarchical clustering using Ward’s method and visualized both the dendrogram and clusters.

# Submission

The code and outputs are provided in a Jupyter Notebook. All explanations are included in markdown cells.

