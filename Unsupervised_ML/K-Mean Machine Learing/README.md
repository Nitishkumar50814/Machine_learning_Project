# K-means-unsupervised-Machine-Learning-Model
Unsupervised learning project using K-Means for cluster identification.

# K-Means Clustering Machine Learning Project
A simple and beginner-friendly project demonstrating **K-Means Clustering**, an unsupervised machine learning algorithm used to partition data into distinct groups based on similarity.

---

## Project Objective
The goal of this project is to:

- Apply **K-Means Clustering** on a dataset  
- Identify underlying groups/clusters  
- Visualize clusters in 2D space  
- Understand the role of the **Elbow Method** in selecting the optimal number of clusters (K)

---

##  What is K-Means?
**K-Means** is an unsupervised clustering algorithm that:

1. Selects K cluster centers (centroids)  
2. Assigns each data point to the nearest centroid  
3. Updates centroids again based on group means  
4. Repeats steps until convergence  

It is widely used in:
- Customer segmentation  
- Image compression  
- Pattern recognition  
- Market analysis  

---

##  Dataset Information
This notebook uses a numerical dataset (example: 2D features).  
Dataset contains features like:
- Feature 1  
- Feature 2  
- (and more if present)

*(Replace with your actual dataset details if required.)*

---
# Output includes:

Cluster plot

Centroids

Cluster labels

# Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-Learn

##  Machine Learning Workflow

### ✔ Import Libraries
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans
