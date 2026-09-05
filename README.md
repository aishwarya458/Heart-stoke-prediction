# Stroke Prediction Using Machine Learning

## Problem Statement

Stroke is a serious medical condition where early identification of high-risk individuals can help support timely medical intervention.

The objective of this project is to develop a machine learning model that predicts whether a person is likely to experience a stroke based on demographic, medical, and lifestyle-related features.

## Solution

The dataset was first analyzed and preprocessed by handling missing values and converting categorical variables into numerical features.

Since the dataset had a significant class imbalance, **class-weight balancing** was applied to give greater importance to stroke cases.

The numerical features were standardized using **StandardScaler**, and **Logistic Regression** was used as the classification algorithm.

The model was evaluated using accuracy, precision, recall, F1-score, and log loss, with particular focus on **recall for the stroke class**.

## Conclusion

The Logistic Regression model achieved:

* **Accuracy:** 72.74%
* **Stroke Recall:** 81%
* **Stroke Precision:** 12%
* **Stroke F1-Score:** 21%
* **Log Loss:** 0.5366

The model achieved a high recall for stroke cases, making it better at identifying potential stroke cases, although the low precision indicates a relatively high number of false positives.
