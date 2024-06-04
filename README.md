# Human-Resources-Analytics
## Human Resources Analytics with Machine Learning

This repository contains the solution for a Machine Learning assignment focused on Human Resources Analytics. The project involves exploring a dataset related to employee attributes, applying various machine learning techniques, and drawing insights to optimize organizational performance.

## Contents

- `ML_3.ipynb`: Jupyter Notebook with the complete solution, including code, analysis, and visualizations.
- `data-variables-description.pdf`: PDF file describing the variables in the dataset.
- `Human_Resuorces_Analytics.csv`: CSV file containing the raw data.
- `df.csv`: CSV file containing processed data.
- `HW3.pdf`: PDF file with the detailed homework assignment and instructions.

## Overview

### Section A: Data Exploration and Pre-processing
- Explored data using tables and visualizations (bar charts, scatter plots, histograms).
- Analyzed the overall diversity profile, relationship between performance and managers, and pay equity across the company.
- Additional visualizations provided insights on employee satisfaction and turnover rates.
- Applied data pre-processing techniques including handling missing values, encoding categorical variables, and feature scaling.

### Section B: Dimensionality Reduction
- Applied Principal Component Analysis (PCA) to reduce dimensionality.
- Created scatter plots to visualize clusters based on employment status.
- Identified key features influencing employee grouping and visualized their contributions.
- Examined the effect of excluding the most influential feature on PCA results.
- Created a biplot to interpret relationships between data points and variables.

### Section C: Classification
- Built predictive models (SVM, Random Forest, and Logistic Regression) to classify employment status (Active, Voluntarily Terminated, Terminated for Cause).
- Evaluated models based on accuracy, sensitivity, and specificity.
- Identified important features for each model and implemented methods to improve performance.

### Section D: Regression
- Developed regression models (Linear Regression, Decision Tree, and Random Forest) to predict time until employee termination.
- Evaluated models using suitable performance metrics and compared results.
- Post-processed predictions to determine exact termination dates.

### Section E: Bonus Tasks
- Calculated employee retention rate for different recruitment sources over the years and visualized it.
- Computed diversity index for each department based on race, gender, and age, and ranked departments.
- Created a map visualization showing the number of employees from each state.

### Section F: Performance
- Compared model performance with peers to identify superior methodologies.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HR_Analytics_Homework.git
