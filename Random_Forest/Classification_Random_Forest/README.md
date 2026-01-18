# Random-forest-on-digits-dataset
A machine learning project on digit prediction using Random Forest.

# Digit Classification using Random Forest
### Machine Learning • Image Classification • Scikit-Learn

This project uses a **Random Forest Classifier** to predict handwritten digits (0–9) using the classic **Digits dataset** from Scikit-Learn.

It includes data visualization, model training, predictions, and evaluation using a confusion matrix.

---

## 1. Project Overview
The Digits dataset contains **8x8 pixel images** of handwritten numbers.  
Each image is converted into numerical features, and a Random Forest model is trained to classify them.

The workflow includes:

- Loading digits dataset  
- Visualizing sample images  
- Preparing data for training  
- Training Random Forest Classifier  
- Making predictions  
- Evaluating accuracy  
- Confusion Matrix visualization  

---

## 2. Dataset Used
Dataset: **load_digits() from sklearn.datasets**

- Total samples: **1797**
- Image size: **8 × 8 pixels**
- Target classes: **0 to 9**
- Type: Small Image Classification Dataset

---
## 2. Technologies Used


- **Python**
- **Pandas**
- **Matplotlib**
- **Matplotlib**
- **Seabon**
- **Scikit-Learn**
- **Jupyter Notebook**



## 3. Code Overview

### ✔ Load Dataset
```python
from sklearn.datasets import load_digits
digits = load_digits()
