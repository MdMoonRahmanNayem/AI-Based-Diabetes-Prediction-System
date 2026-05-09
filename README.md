# AI Based Diabetes Prediction System

An Artificial Intelligence based healthcare prediction system designed to identify diabetes risk using machine learning algorithms and clinical health indicators. The project applies data preprocessing, exploratory data analysis (EDA), classification modeling, and performance evaluation techniques to support early diabetes detection. 

## Project Overview

The objective of this project is to develop an intelligent diabetes prediction system capable of identifying diabetic patients based on medical and lifestyle-related attributes.

The system utilizes multiple machine learning algorithms to analyze patient health indicators and compare model performance for selecting the most reliable prediction approach.

## Dataset Information

| Feature         | Details                    |
| --------------- | -------------------------- |
| Dataset Size    | 100,004 Records            |
| Target Variable | Diabetes                   |
| Dataset Type    | Healthcare / Clinical Data |

## Features Used

* Age
* Gender
* BMI
* HbA1c Level
* Blood Glucose Level
* Hypertension
* Heart Disease
* Smoking History

## Objectives

* Perform comprehensive Exploratory Data Analysis (EDA)
* Preprocess healthcare data for machine learning
* Train multiple classification models
* Compare model performance using evaluation metrics
* Predict diabetes risk using patient health data

## Machine Learning Models

### Logistic Regression

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 95.6% |
| Precision | 84.9% |
| Recall    | 61.1% |
| F1-Score  | 71.1% |

### Decision Tree

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 95.0% |
| Precision | 71.8% |
| Recall    | 74.0% |
| F1-Score  | 72.8% |

### Random Forest

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 97.0% |
| Precision | 94.7% |
| Recall    | 67.4% |
| F1-Score  | 78.7% |

### Artificial Neural Network (ANN)

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 86.0% |
| Precision | 81.0% |
| Recall    | 80.0% |
| F1-Score  | 80.0% |

## Project Workflow

1. Data Ingestion
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Encoding & Scaling
5. Model Training
6. Performance Evaluation
7. Diabetes Prediction

## Exploratory Data Analysis

The project includes:

* Correlation Heatmap Analysis
* Class Distribution Visualization
* Histograms and KDE Plots
* Confusion Matrix Visualization
* Comparative Model Analysis

## Key Findings

* Blood glucose level and HbA1c are strong predictors of diabetes.
* Random Forest achieved the best overall performance.
* Decision Tree showed signs of overfitting.
* ANN performed well for nonlinear relationships.
* Logistic Regression provided strong interpretability.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

## Repository Structure

```text id="25v1u2"
├── README.md
├── Project Code.ipynb
└── Project Report.pdf
```

## Contributors

| Name                    | ID            |
| ----------------------- | ------------- |
| Nusroth Nourin          | 2022-3-60-006 |
| Mantasha Rahman Mahi    | 2022-3-60-194 |
| Jannatul Ferdous Nabila | 2022-3-60-198 |
| Md Moon Rahman Nayem    | 2022-3-60-210 |
| Nazratan Mazumder Niha  | 2022-3-60-328 |

## Academic Information

* **Course Title:** Artificial Intelligence
* **Course Code:** CSE366
* **Section:** 04
* **Department:** Computer Science and Engineering
* **Institution:** East West University

## Supervisor

**Dr. Md. Golam Rabiul Amin**
Adjunct Faculty
Department of CSE
East West University

## Conclusion

This project demonstrates the practical application of machine learning techniques in healthcare prediction systems. Among all evaluated models, Random Forest achieved the best overall performance and was identified as the most reliable model for diabetes prediction using clinical health indicators.
