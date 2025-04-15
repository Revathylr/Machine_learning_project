# Machine_learning_project
Car Price Prediction 

1. Introduction
               A Chinese automobile company plans to enter the US market and seeks insights into how car prices are influenced by various factors. The primary objective is to predict car prices using machine learning models and identify the most significant features affecting pricing.

2. Objective
              The goal is to develop a regression model that accurately predicts car prices based on technical specifications and categorical attributes. The insights will help the company tailor their designs and marketing strategies for the US market.

3. Dataset Overview
             The dataset contains technical and categorical specifications of various car models including variables like engine size, horsepower, fuel type, number of doors, etc. The target variable is price.

4. Data Preprocessing

I.Removed irrelevant columns (e.g., car_ID)

II.Extracted and encoded car brand from CarName

III.Handled categorical variables using one-hot encoding

IV.Standardized numerical features using StandardScaler

5. Model Implementation
Five regression models were trained and tested:

I.Linear Regression

II.Decision Tree Regressor

III.Random Forest Regressor

IV.Gradient Boosting Regressor

V.Support Vector Regressor

6. Model Evaluation Metrics
Models were evaluated using:

a)R-squared (R²)

b)Mean Squared Error (MSE)

c)Mean Absolute Error (MAE)

Best Performing Model: Random Forest Regressor achieved the highest R² value(0.957509) and the lowest error metrics among all models.

7. Feature Importance Analysis
Using the Random Forest model, the top factors affecting car price were:

i)Engine size

ii)Horsepower

iii)Curb weight

iv)Car width

v)Highway mpg

8. Hyperparameter Tuning
Performed grid search on Random Forest with parameters:

n_estimators: [100, 200]

max_depth: [None, 10, 20]

This tuning improved performance slightly, confirming the model's robustness.

9. Conclusion
The Random Forest model effectively predicts car prices with high accuracy. Key variables like engine size and horsepower significantly influence car pricing. These insights will help the company strategize product offerings and price points in the US market.
