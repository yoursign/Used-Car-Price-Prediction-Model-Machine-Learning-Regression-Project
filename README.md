# Used-Car-Price-Prediction-Model-Machine-Learning-Regression-Project
**Overview**
This project is part of my Data Science Journey, focusing on developing a machine learning regression model to predict the prices of used cars. The model is designed to help users and dealerships estimate a fair selling price based on historical data of car sales, leveraging features like car model, year of manufacture, mileage, fuel type, and transmission.

**Problem Statement**
Predicting the price of a used car is challenging due to multiple factors influencing the final sale price. These factors include the car’s brand, age, mileage, fuel type, and more. The goal of this project is to create a reliable model that predicts the selling price of used cars, offering valuable insights for buyers and sellers alike.

**Data**
The dataset consists of multiple features that affect a car’s price:

**Car Model:** The brand and model of the car.
Year of Manufacture: The year the car was manufactured.
**Mileage:** The number of miles driven.
**Fuel Type:** Categorical feature indicating whether the car runs on petrol, diesel, etc.
**Transmission:** Categorical feature indicating manual or automatic transmission.
**Price:** Target variable representing the selling price of the car.

Approach
Data Preprocessing

Handled missing values and outliers.
Converted categorical variables such as fuel type and transmission into numerical values.
Normalized and scaled numerical features (e.g., mileage, year).
Modeling
Built and compared various regression models, including:

****Linear Regression**
Decision Tree Regression
Random Forest Regression
Gradient Boosting**

**Evaluated model performance using:**

Mean Squared Error (MSE)
R-squared
Feature Importance

Analyzed feature importance to identify the most significant factors influencing car prices, providing actionable insights for users and dealerships.

**Model Evaluation**

Used hyperparameter tuning to optimize model performance.
Tools & Technologies
Python (Jupyter Notebook)
Pandas, NumPy for data manipulation
Scikit-learn for building and evaluating machine learning models
Matplotlib, Seaborn for data visualization

**Conclusion**

The final model was selected based on performance metrics and feature interpretability. The project demonstrates the power of machine learning in predicting used car prices, helping consumers and dealerships make data-driven decisions.
