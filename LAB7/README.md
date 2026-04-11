# Logistic Regression LAB 7

## 📌 LAB Overview
This lab uses a fake advertising dataset to predict whether a user will click on an advertisement using Logistic Regression.

---

## 📂 Dataset
- [advertising.csv](advertising.csv)
- [LAB7.ipynb](LAB7.ipynb)

---

## 🧾 Dataset Features

- **Daily Time Spent on Site**: Consumer time on site in minutes  
- **Age**: Customer age in years  
- **Area Income**: Average income of the consumer's area  
- **Daily Internet Usage**: Average minutes per day on the internet  
- **Ad Topic Line**: Advertisement headline  
- **City**: Consumer's city  
- **Male**: Gender (1 = Male, 0 = Female)  
- **Country**: Consumer's country  
- **Timestamp**: Time of interaction with the ad  
- **Clicked on Ad**: Target variable (1 = Clicked, 0 = Not Clicked)  

---

## ⚙️ LAB Workflow

### 1. Import Libraries
Load necessary libraries such as pandas, numpy, matplotlib, seaborn, and sklearn.

### 2. Load Data
Read the dataset using pandas.

### 3. Data Exploration
- `head()`
- `info()`
- `describe()`

### 4. Exploratory Data Analysis (EDA)
- Histogram of Age  
- Jointplot: Area Income vs Age  
- KDE Jointplot: Daily Time Spent on Site vs Age  
- Jointplot: Daily Time Spent vs Daily Internet Usage  
- Pairplot with hue = Clicked on Ad  

### 5. Data Preparation
- Select features  
- Define X and y  
- Train-test split  

### 6. Model Training
Train a Logistic Regression model on the training data.

### 7. Predictions
Predict outcomes using the test data.

### 8. Evaluation
Evaluate the model using a classification report.

---
