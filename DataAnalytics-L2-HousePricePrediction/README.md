# Level 2 – Task 1: House Price Prediction Using Linear Regression

## Project Overview

This project focuses on predicting house prices using Machine Learning techniques.

The objective is to develop a Linear Regression model that estimates residential property prices based on important housing characteristics.

The project uses the Ames Housing dataset and applies data preprocessing, feature selection, categorical encoding, model training and performance evaluation.

## Objective

- Analyze housing data.
- Identify important features influencing house prices.
- Perform data preprocessing and feature engineering.
- Develop a Linear Regression model.
- Predict house prices using selected property features.
- Evaluate model performance using regression metrics.

## Dataset Information

**Dataset:** Ames Housing Dataset

**File:** `train.csv`

**Target Variable:** `SalePrice`

Dataset information:
- Total Records: 1,460
- Total Columns: 81
- Numerical Columns: 38
- Categorical Columns: 43
- Duplicate Records: 0

## Selected Features

The following eight features were selected for model development:

| Feature | Description |
|---|---|
| GrLivArea | Above-ground living area |
| LotArea | Lot size |
| Neighborhood | Physical location of the property |
| BedroomAbvGr | Number of bedrooms above ground |
| FullBath | Number of full bathrooms |
| OverallQual | Overall material and finish quality |
| HouseAge | Difference between year sold and year built |
| GarageCars | Garage capacity in cars |

**Target:** `SalePrice`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading and Inspection
Loaded the Ames Housing dataset and examined its structure, dimensions, data types and statistical information.

### 2. Data Preprocessing
Selected eight relevant features and checked for missing values and duplicate records.

### 3. Feature Engineering
Created a new feature called `HouseAge` using:

`HouseAge = YrSold - YearBuilt`

### 4. Categorical Encoding
Applied One-Hot Encoding to the `Neighborhood` categorical feature to convert it into a numerical representation.

### 5. Train-Test Splitting
Split the dataset into training and testing sets using an 80:20 ratio.

- Training records: 1,168
- Testing records: 292
- Random state: 42

### 6. Model Development
Developed a Linear Regression model using Scikit-learn to predict house prices.

### 7. Model Evaluation
Evaluated the model using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) Score

## Model Performance

The Linear Regression model achieved the following results:

| Evaluation Metric | Result |
|---|---:|
| MSE | 1,371,081,354.45 |
| RMSE | 37,028.12 |
| R² Score | 0.8212 |
| R² Percentage | 82.12% |

The R² score indicates that the model explains approximately 82.12% of the variation in house prices on the test dataset.

## Visualization and Analysis

The project includes model analysis and visualizations such as:
- Actual vs Predicted House Prices.
- Residual Analysis.
- Residual Distribution.
- Regression Coefficient Analysis.

The residual analysis showed errors distributed around zero, with larger positive residuals and increasing error spread at higher predicted prices.

The coefficient analysis also indicated positive contributions from OverallQual and GarageCars in the fitted model.

## Key Learning Outcomes

- Understood regression-based prediction.
- Learned feature selection and feature engineering.
- Gained experience in categorical encoding.
- Practiced training and testing machine learning models.
- Learned regression evaluation metrics.
- Understood residual analysis and model interpretation.

## Conclusion

This project demonstrates the application of Linear Regression for residential house price prediction using selected housing features.

The model achieved an R² score of 0.8212, indicating a reasonably strong relationship between the selected housing features and the actual sale prices in the test dataset.

The project provided practical experience in building, evaluating and interpreting a machine learning regression model.

## Project File

`House_Price_Prediction.ipynb`

## Internship

Oasis Infobyte – Data Analytics Internship

**Level:** 2 | **Task:** 1
