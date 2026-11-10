# Level 1 – Task 2: Customer Segmentation Analysis

## Project Overview

Customer Segmentation Analysis is a data analytics project that focuses on grouping customers based on their purchasing behavior.

The objective is to identify different customer groups using transaction history and understand their purchasing patterns. Customer segmentation helps businesses develop better marketing strategies, improve customer engagement and make data-driven decisions.

## Objective

- Analyze customer purchasing behavior.
- Understand customer transaction patterns.
- Calculate Recency, Frequency and Monetary (RFM) values.
- Group customers based on their purchasing behavior.
- Apply clustering techniques to identify customer segments.
- Generate useful insights for customer relationship management.

## Dataset Information

**Dataset:** Online Retail II

**Source:** Kaggle – Online Retail II Dataset

The dataset contains retail transaction information from a UK-based online retailer covering December 2009 to December 2011.

### Dataset Attributes

| Column | Description |
|---|---|
| Invoice | Invoice number |
| StockCode | Product code |
| Description | Product description |
| Quantity | Quantity purchased |
| InvoiceDate | Date and time of transaction |
| Price | Unit price |
| Customer ID | Customer identifier |
| Country | Customer country |

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
Loaded the Online Retail II dataset and examined its structure, columns, data types and transaction information.

### 2. Data Cleaning and Preprocessing
Prepared the transaction data for customer-level analysis by examining missing values, duplicate records and transaction information.

### 3. RFM Analysis

RFM analysis was used to understand customer purchasing behavior through three important metrics.

**Recency:** Measures how recently a customer made a purchase.

**Frequency:** Measures how frequently a customer made purchases.

**Monetary:** Measures the total amount spent by a customer.

### 4. Feature Scaling
Applied StandardScaler to standardize RFM features before clustering.

### 5. Customer Segmentation Using K-Means
Used the K-Means clustering algorithm to group customers based on their RFM characteristics.

### 6. Elbow Method
Used the Elbow Method to help determine a suitable number of clusters for customer segmentation.

### 7. Cluster Analysis and Visualization
Analyzed customer groups using visualizations, cluster distributions and RFM characteristics.

## Key Concepts

- Customer behavior analysis.
- RFM analysis.
- Feature engineering.
- Feature scaling.
- K-Means clustering.
- Unsupervised Machine Learning.
- Customer segmentation.

## Business Applications

Customer segmentation can help businesses:

- Identify recently active customers.
- Recognize frequent customers.
- Understand high-value customers.
- Develop targeted marketing campaigns.
- Improve customer retention strategies.
- Design personalized customer engagement approaches.

## Key Learning Outcomes

- Learned how to analyze transaction datasets.
- Understood RFM-based customer analysis.
- Gained practical experience with K-Means clustering.
- Learned feature scaling using StandardScaler.
- Understood the Elbow Method.
- Developed skills in customer behavior analysis and visualization.

## Conclusion

This project demonstrates how customer transaction data can be transformed into meaningful customer segments using RFM analysis and K-Means clustering.

The analysis provides a foundation for understanding customer purchasing behavior and supporting data-driven marketing and customer relationship management decisions.

## Project File

`Customer_Segmentation.ipynb`

## Internship

Oasis Infobyte – Data Analytics Internship

**Level:** 1 | **Task:** 2
