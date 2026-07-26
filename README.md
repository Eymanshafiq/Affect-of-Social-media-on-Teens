# Affect-of-Social-media-on-Teens
This project develops a machine learning model to identify problematic social media use among teenagers using daily screen time, social media activity, and gender. It demonstrates an end-to-end workflow, including data preprocessing, feature scaling, Logistic Regression, model evaluation, and pipeline deployment for reliable predictions.
# Teen Social Media Problematic Use Prediction

A machine learning project that predicts whether a teenager exhibits "problematic social media usage" using behavioural features such as daily screen time, social media usage, and gender.

## Features

* Data cleaning and preprocessing
* Missing value and duplicate removal
* Outlier detection using the IQR method
* Categorical data encoding with `LabelEncoder`
* Feature scaling using `StandardScaler`
* Classification using Logistic Regression
* Model evaluation with Accuracy Score, Classification Report, and Confusion Matrix
* Model persistence using `Joblib`
* Prediction on new data using the saved pipeline

## Technologies

* Python
* Pandas
* Scikit-learn
* Joblib

## Machine Learning Workflow

1. Load the dataset.
2. Inspect and clean the data.
3. Remove outliers using the IQR method.
4. Encode categorical variables.
5. Select features and target variable.
6. Split the dataset into training and testing sets.
7. Build a preprocessing and classification pipeline.
8. Train the Logistic Regression model.
9. Evaluate model performance.
10. Save and reload the trained pipeline for future predictions.

## Features Used

* Daily Screen Time Hours
* Social Media Hours
* Gender

## Target Variable

* `problematic_use_flag`

## Evaluation Metrics

* Accuracy Score
* Classification Report
* Confusion Matrix

## Output

The trained model predicts whether a teenager is likely to have problematic social media usage based on the selected input features. The preprocessing steps and trained classifier are combined into a reusable Scikit-learn pipeline for consistent and efficient predictions.

