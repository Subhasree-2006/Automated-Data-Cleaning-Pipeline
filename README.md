# Automated-Data-Cleaning-Pipeline
MY 1st step cleaning real hospital data
## Overview

This demonstrates an automated data cleaning and preprocessing pipeline using a real-world healthcare dataset from Kaggle.

The pipeline performs data inspection, text standardization, outlier filtering, correlation analysis, and visualization using Python data science libraries.

## Dataset

Dataset: Diabetes Prediction Dataset

Source:
https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

## Objectives

- Load and inspect raw healthcare data
- Identify missing values
- Standardize categorical text values
- Remove invalid age records
- Analyze relationships between numerical features
- Generate correlation heatmap
- Export cleaned dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning Steps

### 1. Data Loading
Loaded dataset using Pandas.

### 2. Data Inspection
- Dataset shape
- Column information
- Missing value counts

### 3. Gender Standardization
Converted gender values to lowercase and removed extra spaces.

### 4. Outlier Filtering
Removed records with unrealistic age values:
- Age ≤ 0
- Age ≥ 115

### 5. Correlation Analysis
Generated a correlation matrix using numerical features.

### 6. Visualization
Created and saved a heatmap showing feature correlations.

### 7. Export
Saved cleaned data as:

cleaned_hospital_records.csv

## Output Files

- cleaned_hospital_records.csv
- correlation_heatmap.png

## Author

Subhasree
