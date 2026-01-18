# Clustering-using-hierarchical-method
Agglomerative hierarchical clustering with dendrogram and cluster visualization.




# Hierarchical Clustering on Dataset
A simple and beginner-friendly Machine Learning project demonstrating **Hierarchical Clustering** (Agglomerative Clustering) with visualizations using a dendrogram.

---

##  Project Objective
To group similar data points together using **Hierarchical Clustering**, and visualize how clusters merge step-by-step using a **dendrogram**.

---

##  What is Hierarchical Clustering?
Hierarchical clustering builds clusters step-by-step:

###  **Agglomerative Clustering (Bottom-Up)**
- Each point starts as its own cluster  
- Clusters are merged based on similarity  
- Continues until all points form one cluster  

###  **Output includes:**
- Dendrogram  
- Cluster labels  
- Visual scatter plots  

---
##  Results

Clusters created based on similarity

Dendrogram shows merging of clusters

Visualization helps understand separability of data

##  Technologies Used

Python

Pandas

NumPy

Matplotlib

Scipy

Scikit-Learn


##  Machine Learning Workflow

### Import Libraries
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from scipy.cluster.hierarchy import dendrogram, linkage
from sklearn.cluster import AgglomerativeClustering
