# Calories-Burnt-Prediction

### Project Overview
---
This project predicts calories burnt during physical activity using machine learning regression models. It uses a dataset with features like age, gender, height, heart rate, body temperature, and exercise duration. The pipeline includes data preprocessing, exploratory data analysis (EDA), model training (Linear Regression, XGBoost, Random Forest, Lasso, Ridge), and hyperparameter tuning via GridSearchCV. The tuned XGBoost model achieved the best validation MAE of 9.93.

### Dataset
---
The dataset, sourced from Github, consists of two CSV files (exercise.csv and calories.csv) merged on User_ID. It includes 15,000 entries with features;

- Gender (male/female)
- Age (years)
- Height (cm)
- Weight (kg)
- Duration (minutes)
- Heart_Rate (bpm)
- Body_Temp (°C)
- Calories (target variable)

### Results
---
Best Model: Tuned XGBoost (learning_rate = 0.1, max_depth = 6, n_estimators = 100)
Validation MAE: 9.93
Training MAE: 8.89

###Licence
---
All rights reserved by *1453nicat*.
