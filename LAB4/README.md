# 📊 Lab 04 – Data Quality Assessment & Preprocessing

---

## 📌 Overview

This lab focuses on evaluating and improving data quality before building machine learning models.  
The **Ames Housing (House Prices)** dataset is preprocessed to ensure clean, consistent, and well-scaled features suitable for regression tasks.

The objective is to enhance data reliability, reduce noise, and optimize feature representation.

---

## 🎯 Objectives

- Detect and handle outliers using the **Interquartile Range (IQR)** method  
- Apply feature scaling techniques:
  - **Min-Max Normalization**
  - **Standardization (Z-score scaling)**
- Explore relationships between features using a **correlation heatmap**
- Perform **Principal Component Analysis (PCA)**
- Analyze and interpret the **explained variance ratio**

---

## 📂 Dataset Details

- **Dataset File:** `train.csv`  
- **Target Variable:** `SalePrice`  
- **Learning Type:** Supervised Learning  
- **Task:** Regression  

The dataset contains a mixture of numerical and categorical variables describing residential properties and their final sale prices.

---

## 🛠 Preprocessing Workflow

### 1️⃣ Data Inspection
- Check missing values  
- Review data types  
- Identify potential inconsistencies  

### 2️⃣ Outlier Detection & Treatment
- Apply the **IQR method**  
- Cap or remove extreme values  

### 3️⃣ Feature Scaling
- Normalize numerical features using **Min-Max Scaling**  
- Standardize features using **Z-score transformation**  

### 4️⃣ Correlation Analysis
- Generate a correlation matrix  
- Visualize relationships using a **heatmap**  
- Identify strong positive and negative correlations  

### 5️⃣ Dimensionality Reduction
- Apply **PCA**  
- Evaluate cumulative explained variance  
- Select optimal number of principal components  

---
## Files
🔗 **Notebook File:** [LAB4_DataqualityAsssesment.ipynb](./LAB4_DataqualityAsssesment.ipynb)  
🔗 **Dataset File:** [train.csv](./train.csv)
