# customer-clustering-project

## Overview
This project focuses on customer segmentation using clustering algorithms. The goal is to identify different groups of customers based on their purchasing behaviors, which helps businesses in targeted marketing.

## Objectives
- **Cluster** customers into distinct segments based on their behavior.
- **Analyze** the characteristics of each segment.
- **Provide** business insights to improve marketing strategies.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
- **Algorithms**: K-Means Clustering.

## Data Preprocessing Steps  

### 1. Import Libraries & Load Dataset  
- Used `pandas`, `numpy`, `seaborn`, `matplotlib`, and `sklearn.preprocessing` for data processing.  
- Loaded the dataset and explored its structure using `info()`, `head()`, and `describe()` functions.  

### 2. Handling Missing Values  
- Checked for missing values in the dataset.

### Visualizations
- Uses histogram for visualization

### Encode categorical columns
- Mapping in gender column

## Dataset
The dataset consists of customer demographic information, purchasing patterns, and transaction history. It was sourced from [Kaggle](https://www.kaggle.com/datasets/zubairmustafa/shopping-mall-customer-segmentation-data) and contains the following fields:
- **CustomerID**: Unique customer identifier.
- **Gender**: Customer gender.
- **Age**: Customer age.
- **Annual Income**: Income of the customer.
- **Spending Score**: Score assigned by the mall based on customer behavior.
