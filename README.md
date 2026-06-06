# Heart Disease Prediction Using Machine Learning

## Overview

This project focuses on predicting the likelihood of cardiovascular disease using machine learning techniques and clinical patient data. The objective is to identify key health indicators associated with heart disease and develop predictive models capable of assisting data-driven healthcare decision-making.

The project follows a complete machine learning workflow including exploratory data analysis, feature engineering, feature selection, model training, evaluation, and algorithm comparison.

---

## Dataset

The dataset contains patient health records with attributes such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* ST Slope

Target Variable:

* **HeartDisease**

  * 0 = No Heart Disease
  * 1 = Heart Disease Present

---

## Project Workflow

### Exploratory Data Analysis (EDA)

* Analyzed categorical and numerical health indicators
* Visualized disease distribution across patient groups
* Identified relationships between clinical features and heart disease occurrence
* Explored correlations and patterns within the dataset

### Feature Engineering

* Applied feature scaling and preprocessing techniques
* Generated analytical insights from transformed variables
* Prepared data for machine learning algorithms

### Feature Selection

#### Chi-Square Test

Used to evaluate the significance of categorical features in predicting heart disease.

#### ANOVA Test

Applied to identify numerical features with strong predictive power.

### Machine Learning Models

Implemented and compared multiple classification algorithms:

* Logistic Regression
* Support Vector Classifier (SVC)
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)

---

## Model Evaluation

Models were evaluated and compared to identify the most effective approach for heart disease prediction.

Evaluation metrics included:

* Accuracy
* Classification Performance Comparison
* Feature Importance Analysis

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Key Learning Outcomes

* Exploratory Data Analysis (EDA)
* Healthcare Data Analytics
* Feature Engineering
* Feature Selection using Chi-Square and ANOVA
* Classification Modeling
* Model Comparison and Evaluation
* Data Visualization

---

## Repository Structure

```text
Heart-Disease-Prediction/

├── Heart_Disease_Prediction.ipynb
├── heart.csv
└── README.md
```

---

## Conclusion

Successfully developed and evaluated multiple machine learning models for cardiovascular disease prediction. Through feature engineering, statistical feature selection, and comparative model analysis, the project demonstrates how healthcare data can be leveraged to support predictive analytics and clinical decision-making.

```
```
