# House-Price-Prediction
Machine Learning Regression Project
# Problem statement
The real estate industry often needs accurate estimation of property prices based on various
house characteristics. In this task, the goal is to build a Machine Learning regression model
that predicts the price of a house using features such as house size, number of bedrooms,
number of bathrooms, lot size, garage size, neighborhood quality, and the year the house was
built.
Students are required to analyze the dataset, perform data preprocessing, apply feature
engineering techniques, train multiple regression models, and evaluate their performance to
identify the best model for predicting house prices.
# Objective
The objective of this task is to:
● Understand and explore the housing dataset.
● Perform data preprocessing including handling missing values, duplicates, and outliers.
● Conduct Exploratory Data Analysis (EDA) to identify patterns and relationships in the
data.
● Apply encoding, log transformation, and feature scaling where necessary.
● Train multiple regression algorithms to predict house prices.
● Evaluate and compare model performance using appropriate evaluation metrics
# Project Description
This project aims to predict house prices using Machine Learning regression techniques.  
The model is trained using various features such as square footage, number of bedrooms, bathrooms, lot size, garage size, neighborhood quality, and year built.
The project includes data preprocessing, exploratory data analysis, feature scaling, model training, and evaluation.
# Dataset Features
- Square_Footage
- Num_Bedrooms
- Num_Bathrooms
- Year_Built
- Lot_Size
- Garage_Size
- Neighborhood_Quality
- House_Price (Target variable)
# Steps Performed
1. Import Libraries
2. Load Dataset
3. Check Dataset Information
4. Handle Missing Values
5. Remove Duplicates
6. Univariate Analysis
7. Bivariate Analysis
8. Correlation Heatmap
9. Outlier Detection using Boxplot & IQR
10. Log Transformation
11. Split Features and Target
12. Train Test Split
13. Feature Scaling
14. Train Models
    - Linear Regression
    - KNN Regression
15. Model Evaluation
# Models Used
 Linear Regression
Used to model linear relationship between features and target.

 KNN Regression
Predicts values based on nearest neighbors.
# Evaluation Metrics
- MAE
- MSE
- RMSE
- MAPE
- R2 Score
- Adjusted R2
# Result
Linear Regression performed better because the dataset has strong linear correlation between square footage and house price.
R2 Score (Linear) ≈ 0.94  
R2 Score (KNN) ≈ 0.86  
# Conclusion
Both models performed well, but Linear Regression is more suitable for this dataset due to strong linear relationship.
This project demonstrates how Machine Learning can be used for real-world price prediction problems.
