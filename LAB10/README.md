# 📘 Lab 10 – Support Vector Machines (SVM)

## 📌 Overview
This lab demonstrates the implementation of **Support Vector Machines (SVM)** using the famous Iris dataset.

The objective is to classify iris flower species using machine learning techniques, evaluate model performance, and improve the model using **GridSearchCV** for hyperparameter tuning.

---

## 🎯 Objectives
- Load and explore the Iris dataset  
- Visualize data using pairplots and KDE plots  
- Split data into training and testing sets  
- Train an SVM classifier  
- Evaluate model performance  
- Optimize the model using GridSearchCV  

---

## 📂 Dataset
- **Dataset Used:** Iris Dataset  
- **Problem Type:** Classification  

---

## 📁 Files Included
- [iris.data](iris.data)  
- [Lab10.ipynb](Lab10.ipynb)  
- `README.md` – Project documentation  

---

## ⚙️ Workflow

### 1. Data Loading
- Loaded dataset using Seaborn  
- Displayed dataset information and samples  

### 2. Data Visualization
- Created pairplots for feature relationships  
- Generated KDE plots for Setosa species  

### 3. Data Preparation
- Defined features and target labels  
- Performed train-test split  

### 4. Model Training
- Implemented Support Vector Machine (SVM) classifier  
- Trained the model using training data  

### 5. Model Evaluation
- Generated predictions on test data  
- Evaluated performance using:
  - Confusion Matrix
  - Classification Report

### 6. Hyperparameter Tuning
- Used GridSearchCV to find optimal parameters  
- Compared tuned model performance with the original model  

---

## ✅ Results
The SVM classifier achieved very high accuracy on the Iris dataset.  
Using GridSearchCV slightly improved or maintained the model performance by selecting optimal hyperparameters.

---

## 📚 Topics Covered
- Support Vector Machines (SVM)
- Classification
- Data Visualization
- Model Evaluation
- Hyperparameter Tuning
- GridSearchCV
