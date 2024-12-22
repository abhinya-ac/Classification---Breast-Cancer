#  Breast Cancer Classification Assignment  

## Overview  
This repository contains a statistical analysis and classification project using the Breast Cancer dataset sourced from the Scikit-Learn library. The goal of this assignment was to evaluate several classification algorithms to predict whether a tumor is malignant or benign based on various features.  

## Dataset  
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset. It contains 569 samples with 30 features related to cell measurements (e.g., radius, texture, perimeter, area, etc.) and a binary target variable indicating whether the tumor is malignant (1) or benign (0).  

## Technologies Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## Steps Performed  

### 1. Loading the Dataset  
- The dataset was loaded using the `load_breast_cancer` function from `sklearn.datasets`.  

### 2. Data Exploration  
- Performed exploratory data analysis (EDA) to understand the data structure, checked for missing values, duplicates, and summarized statistics.  

### 3. Outlier Detection and Handling  
- Identified and handled outliers using the Interquartile Range (IQR) method to ensure that extreme values do not adversely affect model performance.  

### 4. Feature Scaling  
- Applied `StandardScaler` to standardize features, ensuring that they have a mean of 0 and a standard deviation of 1, which is essential for many machine learning algorithms.  

### 5. Train-Test Split  
- Split the data into training and testing sets (80/20) to evaluate model performance on unseen data, mitigating overfitting risks.  

### 6. Model Implementation  
The following classification algorithms were implemented and evaluated:  
- **Logistic Regression**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  
- **Support Vector Classifier (SVC)**  
- **k-Nearest Neighbors (k-NN)**  

### 7. Model Evaluation  
- Assessed model performance using metrics such as accuracy, classification reports, and confusion matrices.  
- Compared the accuracies of different models to identify the best and worst-performing classifiers.  

## Results  
- The results include classification reports and confusion matrices for each model.  
- The best-performing model achieved an accuracy of **0.98** (Logistic Regression), while the worst-performing model achieved an accuracy of **0.63** (Random Forest).
