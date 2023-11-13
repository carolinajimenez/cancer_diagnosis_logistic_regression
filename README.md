# Cancer Diagnosis Prediction - Logistic Regression Analysis

## Overview

This repository contains a logistic regression analysis performed on a cancer dataset to predict whether a tumor is benign or malignant. The analysis utilizes machine learning techniques to build and evaluate a logistic regression model.

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data

## Dataset

The dataset used for this analysis includes the following features:

- `id`: Identifier for each patient
- `diagnosis`: Diagnosis label (Malignant - M or Benign - B)
- Various numerical features related to tumor characteristics

## Analysis Steps

1. **Data Loading:** The dataset is loaded from the provided URL.

2. **Data Preparation:** The data is split into independent variables (features) and the target variable. The diagnosis labels are mapped to numerical values (Malignant - 1, Benign - 0).

3. **Data Splitting:** The data is divided into training and testing sets.

4. **Logistic Regression Model:** A logistic regression model is created and trained on the training data.

5. **Model Evaluation:** The model is evaluated using accuracy, confusion matrix, and a classification report.

## Results

### Confusion Matrix:
```
[[69  2]
 [ 2 41]]
```

### Accuracy:
```
0.9649122807017544
```

### Classification Report:
```
              precision    recall  f1-score   support
           0       0.97      0.97      0.97        71
           1       0.95      0.95      0.95        43
    accuracy                           0.96       114
   macro avg       0.96      0.96      0.96       114
weighted avg       0.96      0.96      0.96       114
```

## Interpretation

- The model demonstrates a high accuracy of approximately 96.49%, indicating strong performance in predicting tumor diagnoses.
- The confusion matrix reveals a good balance between true positives, true negatives, false positives, and false negatives.
- Precision and recall values for both benign and malignant cases are high, showcasing the model's effectiveness in distinguishing between the two classes.


## Conclusion

The logistic regression model successfully predicts whether a tumor is benign or malignant based on the given features. This analysis provides valuable insights into the model's performance, contributing to cancer diagnosis prediction.

## Author

Carolina Jiménez M

https://carolinajimenez.github.io