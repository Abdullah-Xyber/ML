# Lab 08: K-Nearest Neighbors (KNN)

## Description
In this lab, we applied the K-Nearest Neighbors (KNN) algorithm to a classified dataset. The goal was to build a model that can predict the target class based on feature similarity.

## Dataset
- [KNN_Project_Data](./KNN_Project_Data)

## Code File
- [LAB8.ipynb](./LAB8.ipynb)

## Objectives
- Understand how KNN works
- Apply feature scaling using StandardScaler
- Train a KNN model with different K values
- Evaluate model performance using confusion matrix and classification report
- Use the Elbow Method to determine the optimal K value

## Key Steps
- Load and explore the dataset
- Standardize the features
- Split data into training and testing sets
- Train KNN model (starting with K=1)
- Evaluate predictions
- Find best K using error rate vs K plot
- Retrain model with optimal K

## Tools & Libraries
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Conclusion
KNN performance depends heavily on the choice of K and feature scaling. Selecting an optimal K improves model accuracy and generalization.
