# Level 2 – Task 2: Wine Quality Prediction Using Machine Learning

## Project Overview

This project focuses on predicting wine quality using Machine Learning classification techniques.

The objective is to analyze the physicochemical properties of red wine and develop classification models to predict wine quality based on its characteristics.

The project involves data preprocessing, exploratory data analysis, feature scaling, model development, model comparison and performance evaluation.

## Objective

- Analyze the physicochemical properties of red wine.
- Understand the relationship between wine characteristics and quality.
- Clean and preprocess the dataset.
- Develop machine learning classification models.
- Compare model performance.
- Identify a suitable model for wine quality prediction.

## Dataset Information

**Dataset:** Red Wine Quality Dataset

**Source:** Kaggle – UCI Red Wine Quality Dataset

**File:** `winequality-red.csv`

### Dataset Details

- Original Records: 1,599
- Original Features: 11
- Target Variable: `quality`
- Duplicate Records Removed: 240
- Records After Cleaning: 1,359
- Missing Values: 0

### Dataset Features

The dataset contains the following physicochemical properties:

1. Fixed Acidity
2. Volatile Acidity
3. Citric Acid
4. Residual Sugar
5. Chlorides
6. Free Sulfur Dioxide
7. Total Sulfur Dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

**Target Variable:** `quality`

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
Loaded the red wine quality dataset and examined its structure, columns, data types and statistical information.

### 2. Data Cleaning and Preprocessing
- Checked for missing values.
- Identified duplicate records.
- Removed 240 duplicate records.
- Prepared the cleaned dataset for model development.

### 3. Exploratory Data Analysis
Analyzed the distribution of wine quality and the relationships between physicochemical properties and wine quality.

### 4. Feature Scaling
Applied StandardScaler to standardize the input features before model training.

### 5. Train-Test Splitting
Split the cleaned dataset using stratified sampling.

- Training Records: 1,087
- Testing Records: 272
- Split Ratio: 80:20
- Random State: 42

### 6. Model Development

Developed and compared two classification algorithms:

**Logistic Regression**

Used as an initial classification model to predict wine quality categories.

**Tuned Random Forest Classifier**

Developed a tuned Random Forest model with balanced class weights to improve the handling of imbalanced wine quality classes.

### 7. Model Evaluation

Evaluated model performance using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Model Comparison

### Logistic Regression

| Metric | Result |
|---|---:|
| Accuracy | 58.09% |
| Macro F1-score | 0.27 |
| Weighted F1-score | 0.55 |

### Tuned Random Forest Classifier

| Metric | Result |
|---|---:|
| Accuracy | 54.04% |
| Macro F1-score | 0.326 |
| Macro Recall | 0.360 |

The tuned Random Forest model was selected as the final model based on the improved macro F1-score and macro recall compared with Logistic Regression.

## Visualizations

The project includes:
- Exploratory data analysis visualizations.
- Wine quality distribution.
- Model comparison bar chart.
- Feature importance visualization.
- Confusion matrix.

## Key Learning Outcomes

- Learned how to preprocess classification datasets.
- Understood the importance of handling duplicate records.
- Gained experience in exploratory data analysis.
- Practiced feature scaling using StandardScaler.
- Implemented Logistic Regression and Random Forest.
- Compared classification models using evaluation metrics.
- Understood class imbalance and the importance of macro evaluation metrics.

## Conclusion

This project demonstrates the application of machine learning classification techniques to predict red wine quality based on physicochemical properties.

Two classification algorithms, Logistic Regression and Tuned Random Forest, were evaluated.

The tuned Random Forest model achieved an accuracy of 54.04%, a macro F1-score of 0.326 and a macro recall of 0.360.

Although the model provides a foundation for wine quality classification, the evaluation results indicate that predicting less frequent quality categories remains challenging.

The project provided practical experience in data preprocessing, classification, model comparison and performance evaluation.

## Project File

`Level_2_Task_2_Wine_Quality_Prediction.ipynb`

## Internship

Oasis Infobyte – Data Analytics Internship

**Level:** 2 | **Task:** 2
