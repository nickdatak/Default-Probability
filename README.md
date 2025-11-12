**Default Probability Prediction Models**

This repository contains a Jupyter notebook demonstrating predictive modeling to assess the probability of customer default on loans. Two machine learning methods are explored and compared:
Decision Tree Classifier: Used for binary classification of default (0 or 1). The decision tree achieves an accuracy of approximately 99.5% on test data, indicating strong performance for the classification task.
Linear Regression: Applied as an alternative regression approach to predict default probability as a continuous variable. While not directly comparable, it achieves an R-squared score of about 0.79 and a Mean Squared Error (MSE) of 0.031, reflecting a reasonable approximation
The notebook walks through data preprocessing, feature selection, model training, evaluation, and visualization of results including decision tree plots and regression prediction plots.

**Features used:**
creditLinesOutstanding
loanAmtOutstanding
totalDebtOutstanding
income
yearsEmployed
ficoScore

**How to use:**
Load the data with appropriate path configuration.
Run the notebook cells sequentially to reproduce training, evaluation, and visualization.
Compare model metrics to select the better performing method for your use case.
This provides a practical reference for default risk assessment models using Python, scikit-learn, and pandas.

<img width="950" height="636" alt="clipboard10" src="https://github.com/user-attachments/assets/928dde9c-ed0e-4fd9-a45e-6701e5b05610" />

**FICO Score Quantization & Rating Map**
This module provides a pipeline for quantizing borrower FICO scores into discrete rating buckets to support downstream modeling and credit risk analysis. The main idea is to transform continuous FICO scores into a fixed number of buckets, where each bucket receives a rating (with lower ratings denoting better credit). (It's another notebook that uses the same csv file)
