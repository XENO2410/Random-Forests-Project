# Random Forests Project

## Project Overview

In this project, we use a dataset containing census information from the UCI Machine Learning Repository to predict whether a person makes more than $50,000 per year. This classification task is performed using a Random Forest classifier. The main steps of this project include data preprocessing, model training, and evaluation.

## Data Description

The dataset comprises various input features and a target feature (`income`). Some of the key features of interest include:

- **age**: continuous
- **workclass**: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
- **education**: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool
- **race**: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black
- **sex**: Female, Male
- **capital-gain**: continuous
- **capital-loss**: continuous
- **hours-per-week**: continuous
- **native country**: discrete
- **income**: discrete, >50K, <=50K

## Project Steps

1. **Data Loading**:
   - The dataset is loaded into a DataFrame named `df`.

2. **Data Preprocessing**:
   - Handle missing values if any.
   - Encode categorical variables using techniques such as one-hot encoding.
   - Split the dataset into training and testing sets.

3. **Model Training**:
   - Implement a Random Forest classifier using scikit-learn.
   - Train the classifier on the training data.

4. **Model Evaluation**:
   - Evaluate the performance of the classifier using appropriate metrics such as accuracy, precision, recall, and the F1-score.
   - Analyze the results to understand the classifier's effectiveness in predicting whether a person makes more than $50,000.

## Conclusion

This project demonstrates the application of a Random Forest classifier to predict income levels based on census data. Through data preprocessing, model training, and evaluation, the project aims to provide insights into the classifier's performance and its ability to handle various input features.

