<div align="center">

# K-Means Clustering

### Manual implementation from scratch and implementation using Scikit-learn

<img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>

</div>

---

# Overview

This project explores the **K-Means Clustering** algorithm through two different approaches.

The first notebook contains a complete **manual implementation** of the algorithm using only **NumPy**, while the second notebook demonstrates how to solve the same problem using **Scikit-learn**.

The objective of this project was to first understand how K-Means works internally and then learn how to use its optimized implementation in Scikit-learn.

---

# Repository Structure

```text
KMeansClustering/
│
├── images/
│
├── K_mean_clustering.ipynb
│   └── Manual implementation of K-Means
│
├── Kmean_sklearn.ipynb
│   └── Scikit-learn implementation
│
└── README.md
```

---

# Manual Implementation

The manual implementation includes:

- Random centroid initialization
- Euclidean distance calculation
- Assigning each point to its nearest centroid
- Updating centroid locations
- Iterative optimization until convergence
- Handling empty clusters
- Testing on multiple datasets
- Cluster visualization

---

# Scikit-learn Implementation

The Scikit-learn notebook demonstrates:

- Creating a `KMeans` model
- Training using `fit()`
- Predicting cluster labels
- Accessing centroid positions
- Visualizing the final clusters
- Selecting the optimal number of clusters using the **Elbow Method**
- Evaluating clustering quality using the **Silhouette Score**

---

# Algorithm Workflow

```text
Initialize Centroids
        │
        ▼
Compute Distances
        │
        ▼
Assign Points to Nearest Centroid
        │
        ▼
Update Centroids
        │
        ▼
Converged?
   │          │
  No         Yes
   │          │
   └──────────┘
        ▼
 Final Clusters
```

---

# Technologies

- Python
- NumPy
- Matplotlib
- Scikit-learn

---

# What I Learned

Through this project I gained practical experience with:

- Unsupervised Learning
- K-Means Clustering
- Euclidean Distance
- Cluster Assignment
- Centroid Optimization
- Convergence Detection
- Random Initialization
- Empty Cluster Handling
- Elbow Method
- Silhouette Analysis
- Using Scikit-learn for clustering tasks

---

# Key Takeaways

- Building K-Means from scratch provides a much deeper understanding of how the algorithm works.
- Scikit-learn offers an efficient and highly optimized implementation with only a few lines of code.
- The Elbow Method and Silhouette Score may recommend different values for **K**.
- Choosing the best number of clusters should combine quantitative metrics with visualization and domain knowledge.

---

# Future Improvements

Possible future extensions include:

- K-Means++ initialization
- Mini-Batch K-Means
- PCA before clustering
- Testing on larger real-world datasets
- Performance comparison between implementations

---

# License

This repository was created for educational purposes and personal machine learning practice.
