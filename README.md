# Unsupervised Learning in Machine Learning

## Introduction

Unsupervised Learning is a type of Machine Learning where the model learns from unlabeled data. The algorithm tries to find hidden patterns, groups, or relationships in the dataset without knowing the correct output.

---

# Types of Unsupervised Learning

## 1. Clustering

Clustering is used to group similar data points into clusters.

### Algorithm: K-means Clustering

K-means clustering divides data into K groups based on similarity.

### Uses of K-means

* Customer Segmentation
* Product Recommendation
* Image Segmentation
* Market Analysis
* Fraud Detection

### Workflow of K-means Clustering

```text
Collect Dataset
      ↓
Import Libraries
      ↓
Load Dataset
      ↓
Select Important Features
      ↓
Find Best Value of K (Elbow Method)
      ↓
Apply K-means Clustering
      ↓
Create Clusters
      ↓
Visualize Clusters and Centroids
      ↓
Analyze Results
```

### Mall Dataset Example

In the Mall Customer dataset, K-means clustering is used to divide customers into groups based on:

* Annual Income
* Spending Score

This helps businesses understand customer behavior and create better marketing strategies.

---

## 2. Association Rule Learning

Association Rule Learning is used to find relationships between items.

### Algorithm: Apriori Algorithm

Apriori identifies products or items that are frequently purchased together.

### Example

```text
Bread → Butter
```

Meaning: Customers who buy bread often also buy butter.

### Uses of Apriori

* Market Basket Analysis
* Product Recommendation
* Shopping Pattern Analysis
* Inventory Management
* Cross Selling

### Workflow of Apriori Algorithm

```text
Collect Transaction Dataset
          ↓
Import Libraries
          ↓
Load Dataset
          ↓
Convert Data into Transactions
          ↓
Apply Apriori Algorithm
          ↓
Generate Association Rules
          ↓
Analyze Support, Confidence & Lift
```

---

## 3. Dimensionality Reduction

Dimensionality Reduction is used to reduce the number of features while keeping important information.

### Technique: PCA (Principal Component Analysis)

PCA converts large datasets into smaller dimensions called Principal Components.

### Uses of PCA

* Data Compression
* Noise Reduction
* Faster Model Training
* Data Visualization
* Feature Reduction

### Workflow of PCA

```text
Collect Dataset
      ↓
Import Libraries
      ↓
Load Dataset
      ↓
Standardize Data
      ↓
Apply PCA
      ↓
Reduce Dimensions
      ↓
Visualize Important Components
```

---

# Difference Between Clustering and Classification

| Clustering            | Classification               |
| --------------------- | ---------------------------- |
| Unsupervised Learning | Supervised Learning          |
| Uses Unlabeled Data   | Uses Labeled Data            |
| Finds Hidden Groups   | Predicts Categories          |
| Example: K-means      | Example: Logistic Regression |

---

# Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from apyori import apriori
```

---

# Conclusion

Unsupervised Learning helps in discovering hidden patterns and relationships in data. Techniques like K-means, Apriori, and PCA are widely used in real-world applications such as customer segmentation, recommendation systems, and data reduction.
