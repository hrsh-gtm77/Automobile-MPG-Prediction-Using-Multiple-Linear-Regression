# Automobile-MPG-Prediction-Using-Multiple-Linear-Regression
## Auto MPG Prediction using linear, ridge and lasso regression

The project uses **CarS-MPG Dataset** to predict a car's fuel efficiency (measured in **Miles per Gallon - MPG**) based on its specification.

The project compares **Multiple Linear Regression** , **Ridge regression** and **Lasso regression** models.

----

## PROJECT OVERVIEW 
Dataset: [https://www.kaggle.com/datasets/raghupalem/auto-mpg-data-set]

the target variable is **MPG** (fuel efficiency)
Additional engineered features:
**power_to_weight** = horsepower / weight 
**car_age** = 2025 - model_year

Models used:
Multiple Linear Regression
Ridge Regression
Lasso Regression

---- 


## STEPS IN THE CODE

1.**Import Libraries** -> numpy, pandas, matplotlib, seaborne, scikit-learn
2.**Load Dataset** -> 'Cars-MPG Dataset' 
3.**Data Cleansing** -> Removed Missing Values
4.**EDA - EXploratory Data Analysis** -> boxplots, scatterplot, histogram, correlation-heatmap
5.**Feature Engineering** -> created 'power_to_weight' and 'car_age'
6.**Define Features and Target** 
7.**Train-Test-Split** -> (80% training, 20% testing)
8.**Feature Scaling** -> used standard sacling
9.**Train Models**
  - Multiple Linear Regression
  - Ridge Regression
  - Lasso Regression
10. **Model Evaluation**
  - Mean Absolute Error
  - Mean Square Error
  - R² Score
11. **Model Comparison**
12. **Feature Importance**
  - Print Regression Coeffiecients
  - Plot Regression Coefficients
13. **Prediction For A New Car** -> Model predicts MPG for unseen car specifications
