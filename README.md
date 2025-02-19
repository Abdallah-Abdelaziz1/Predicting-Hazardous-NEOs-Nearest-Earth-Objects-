# Predicting-Hazardous-NEOs-Nearest-Earth-Objects-
###Training a model to accurate predicting NEOs is hazardous or not.

### Project Overview
---

This data analysis project aims to Training a model to accurate predicting NEOs is hazardous or not. The dataset I used was observed by NASA from 1910 to 2024. The dataset contains 338,199 records, each representing an object in space that has been monitored for its proximity to Earth.

### Data Sources

Dataset loaded from Kaggle (https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024/data)

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the data to answer key questions, such as:

- What is the Distribution of Hazardous vs Non-hazardous NEOs?

### Model Training and Evaluation
## Key Findings
1.Imbalance Handling: SMOTE improved recall for the minority class (hazardous objects).

2.Top Features: absolute_magnitude and miss_distance were most predictive.

3.Best Model: Random Forest achieved F1-score: 0.98 and AUC-ROC: 0.99.
