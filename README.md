# House Price Prediction using Machine Learning

## Project Overview

This project predicts residential house prices using machine learning techniques. The dataset was preprocessed, analyzed, and used to train multiple regression models. The performance of each model was compared using standard evaluation metrics, and the best-performing model was selected for final prediction.

## Objectives

* Clean and preprocess housing data
* Handle missing values and categorical features
* Perform feature engineering using correlation analysis
* Train and compare multiple machine learning models
* Evaluate model performance using regression metrics
* Identify the best model for house price prediction

## Dataset Source

Kaggle: House Prices - Advanced Regression Techniques

https://www.kaggle.com/c/house-prices-advanced-regression-techniques

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Data Preprocessing

* Removed columns with excessive missing values
* Filled missing numerical values using median
* Filled missing categorical values using mode or "None" where appropriate
* Converted categorical variables into numerical format using one-hot encoding
* Split the dataset into training and testing sets (80:20)

## Feature Engineering

Correlation analysis was performed to identify the most influential features affecting house prices. Key features included:

* OverallQual
* GrLivArea
* GarageCars
* GarageArea
* TotalBsmtSF
* YearBuilt

Feature importance analysis was also performed using the Random Forest model.

## Models Trained

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Model Evaluation Metrics

The following metrics were used:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## Results

| Model             | MAE      | RMSE     | R² Score |
| ----------------- | -------- | -------- | -------- |
| Linear Regression | 20607.58 | 52614.11 | 0.64     |
| Decision Tree     | 27395.35 | 43103.00 | 0.76     |
| Random Forest     | 17621.33 | 29089.24 | 0.89     |

## Best Model

Random Forest Regressor achieved the best performance with:

* Lowest MAE
* Lowest RMSE
* Highest R² Score (0.89)

Therefore, Random Forest was selected as the final model for house price prediction.

## Visualizations

* Correlation Heatmap
* Residual Plot
* Feature Importance Chart

## Conclusion

The project successfully demonstrated the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and interpretation. Among the three models tested, Random Forest provided the most accurate predictions and showed strong capability in capturing complex relationships between housing features and sale prices.

## Author

Kushagr Srivastava
AI & Machine Learning Internship Project
