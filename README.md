**Project Overview**

This project aims to predict lung cancer presence using patient survey data by applying a Gaussian Naive Bayes classifier.
The dataset is fetched directly from Snowflake, preprocessed using Python, and evaluated using Stratified Cross-Validation to handle class imbalance effectively.
Medical datasets are often imbalanced, so special care is taken to ensure reliable and unbiased model evaluation.

**Tech Stack Used**

Database: Snowflake
Programming Language: Python
Libraries:
pandas
snowflake-connector-python
scikit-learn
imbalanced-learn
matplotlib


**Data Leakage Prevention**

SMOTE is applied inside a pipeline
Ensures oversampling happens only on training folds
Prevents artificial data from leaking into validation data
