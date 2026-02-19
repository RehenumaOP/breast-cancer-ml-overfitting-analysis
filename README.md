# Breast Cancer Classification Using Machine Learning

## Project Overview

This project implements machine learning models to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin dataset.

The main focus of this project is to:

- Analyze overfitting
- Apply polynomial feature expansion
- Use regularization techniques (L1 & L2)
- Implement early stopping
- Visualize loss and accuracy curves
- Evaluate model performance using multiple metrics

---

## Dataset Information

- Dataset: Breast Cancer Wisconsin Dataset
- Total Samples: 569
- Total Features: 30 numerical features
- Target Variable: Diagnosis
  - M (Malignant) → 1
  - B (Benign) → 0

The dataset contains medical measurements extracted from digitized breast mass images.

---

## Project Workflow

### 1. Dataset Description
- Exploratory Data Analysis (EDA)
- Target distribution visualization
- Correlation heatmap

### 2. Missing Data Handling
- Checked for null values
- No missing values found

### 3. Data Preprocessing
- Dropped ID column
- Label Encoding of target
- Train/Validation/Test split
- Standard Scaling

### 4. Overfitting Demonstration
- Deep Decision Tree
- Comparison of training vs testing accuracy

### 5. Polynomial Regression
- Polynomial Feature Expansion (Degree 1, 2, 3)
- Performance comparison
- Overfitting analysis

### 6. Regularization
- L1 Regularization (Lasso)
- L2 Regularization (Ridge)
- Effect of C parameter

### 7. Neural Network with Epoch Analysis
- Manual epoch tracking
- Training vs Validation accuracy
- Loss curve visualization

### 8. Early Stopping
- Prevented over-training
- Improved generalization performance

---

## Evaluation Metrics

- Accuracy
- Confusion Matrix
- ROC Curve
- AUC Score

---

## Key Observations

- Increasing model complexity increases overfitting risk.
- Polynomial feature expansion significantly increases feature space.
- Regularization reduces overfitting.
- Early stopping prevents unnecessary training.
- Proper preprocessing improves model stability.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
