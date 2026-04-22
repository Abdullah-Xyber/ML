# Lab 09: Random Forest & Decision Trees

## Description
In this lab, we explored Decision Trees and Random Forest models using lending data. The goal was to predict whether a borrower will fully repay a loan.

## Dataset
- [loan_data.csv](./loan_data.csv)

## Code File
- [LAB9.ipynb](./LAB9.ipynb)

## Objectives
- Perform exploratory data analysis (EDA)
- Handle categorical variables using dummy encoding
- Train and evaluate Decision Tree and Random Forest models
- Compare model performance

## Key Steps
- Load and explore the dataset
- Visualize data using histograms, countplots, and lmplots
- Convert categorical features using pd.get_dummies
- Split data into training and testing sets
- Train Decision Tree model
- Evaluate using confusion matrix and classification report
- Train Random Forest model
- Compare results between models

## Tools & Libraries
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Conclusion
Random Forest generally performs better than a single Decision Tree due to reduced overfitting. However, class imbalance can affect performance, especially for minority classes.
