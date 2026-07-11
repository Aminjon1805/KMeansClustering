<div align="center">

# KMeansClustering

**Manual implementation of the K-Means Clustering algorithm from scratch using NumPy.**

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange?style=for-the-badge)

</div>

---

# Overview

This project focuses on implementing the **K-Means Clustering** algorithm completely from scratch without using machine learning libraries.

The objective is to understand every step of the algorithm, from assigning data points to the nearest centroid to updating centroid positions until convergence.

A **scikit-learn implementation** will be added in a future update.

---

# Project Goals

* Understand how K-Means works internally.
* Implement the algorithm using only NumPy.
* Visualize clustering results.
* Build a strong understanding of unsupervised learning.

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

# Features

* Manual implementation from scratch
* Euclidean distance computation
* Random centroid initialization
* Cluster assignment
* Centroid updates
* Iterative optimization
* Convergence detection
* Cluster visualization

---

# Technologies

* Python
* NumPy
* Matplotlib

---

# Project Structure

```text
KMeansClustering/
│
├── Manual/
│   └── kmeans_manual.ipynb
│
├── Images/
│
└── README.md
```

---

# Future Updates

* Add a scikit-learn implementation
* Implement the Elbow Method
* Experiment with different datasets
* Explore different centroid initialization strategies

---

# What I Learned

This project helped me better understand:

* Unsupervised learning
* K-Means optimization
* Euclidean distance
* Cluster assignment
* Centroid updates
* Convergence criteria
* Building machine learning algorithms from scratch

---

# License

This repository is intended for educational purposes and personal learning.

