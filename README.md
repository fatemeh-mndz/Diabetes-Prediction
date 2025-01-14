

# Diabetes Prediction Project

This project is designed to predict whether a person has diabetes or not using machine learning algorithms. The dataset includes various health metrics such as BMI, glucose levels, and more, which are used to train several classification models. The best performing model, in this case, was **Random Forest**.

## Project Overview

The goal of this project is to predict the likelihood of a person having diabetes based on health-related features. To achieve this, we used three different machine learning algorithms:

1. **K-Nearest Neighbors (KNN)**
2. **Random Forest**
3. **Logistic Regression**



## Dataset

The dataset contains the following columns:

- **Pregnancies**: Number of times the person has been pregnant.
- **Glucose**: Glucose level in the blood.
- **BloodPressure**: Blood pressure measurement.
- **SkinThickness**: Thickness of the skin.
- **Insulin**: Insulin level in the blood.
- **BMI**: Body Mass Index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: A function that represents a genetic predisposition to diabetes.
- **Age**: The age of the person.
- **Outcome**: Whether the person has diabetes (`1`) or not (`0`).

### BMI Categories
The BMI column was transformed into two categories:
- **Normal_BMI**: Indicates if the BMI is in the normal range (18.5 to 24.9).
- **Overweight_BMI**: Indicates if the BMI is above the normal range (> 24.9).

## Models Used

### 1. K-Nearest Neighbors (KNN)
- A simple, non-parametric classification method that makes predictions based on the majority class of the k-nearest neighbors.
- **Accuracy on train data**: 0.7215
- **Accuracy on test data**: 0.7468

### 2. Random Forest (Best Performing Model)
- A powerful ensemble method that uses multiple decision trees to make more accurate predictions.
- **Accuracy on train data**: 0.9805
- **Accuracy on test data**: 0.8052
  
### 3. Logistic Regression
- A popular and interpretable model for binary classification.
- **Accuracy on train data**: 0.7508
- **Accuracy on test data**: 0.7987



The **Random Forest** model provided the best results, making it the chosen model for this task.



## Conclusion

This project demonstrates the use of machine learning algorithms to predict diabetes using a combination of health metrics. Among the three models tested, **Random Forest** provided the best performance. Future work can include hyperparameter tuning and further feature engineering to improve model accuracy.



