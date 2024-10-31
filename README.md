# Classification-in-healthcare-dataset

This project analyzes a healthcare dataset to predict patient test results using various machine learning classifiers. The workflow includes data preprocessing, visualization, model training, and performance evaluation to identify the most effective predictive model.

## Project Overview

This project uses a healthcare dataset to predict the test results of patients. By applying machine learning algorithms such as **K-Nearest Neighbors (KNN)**, **Random Forest**, **Logistic Regression**, and **Support Vector Machine (SVM)**, the goal is to find the best-performing model for accurate predictions in a healthcare setting.

## Dataset

The dataset includes various healthcare features, such as patient demographics, medical history, and billing information. Key steps include:

- Dropping unnecessary columns
- Label encoding categorical variables
- Standardizing numerical features for optimal model performance

## Project Workflow

1. **Data Preprocessing**  
   - Removed irrelevant columns (`Name`, `Doctor`, etc.)
   - Label-encoded categorical features
   - Scaled numerical features for KNN and SVM

2. **Data Visualization**  
   - Visualized data distributions with count plots and histograms
   - Analyzed correlations with a heatmap
   - Identified outliers using boxplots

3. **Model Training and Evaluation**  
   - Trained KNN, Random Forest, Logistic Regression, and SVM
   - Evaluated each model using accuracy, precision, recall, and F1-score
   - Compared model performance with a summary table of accuracy
