# Vehicle CO₂ Emissions Prediction

A guided machine learning project to practice data preprocessing, exploratory data analysis, and regression modeling for predicting vehicle CO₂ emissions using regression models.

> **Learning Project:** This project was completed as part of the AI learning activities in **UKM Circle AI** during my university studies. The implementation followed a step-by-step tutorial and guidance from the mentor.

---

## Project Overview

This project uses a vehicle dataset containing information about vehicle characteristics, fuel type, fuel consumption, and CO₂ emissions.

The target variable is:

- `co2` — CO₂ emissions

The project follows a basic machine learning workflow:

**Data Inspection → Data Preprocessing → EDA → Feature Scaling → Train-Test Split → Modeling → Evaluation**

---

## Learning Objectives

This project was used to practice:

- Data inspection using Pandas
- Missing value handling
- Duplicate checking
- Categorical data encoding
- Exploratory Data Analysis (EDA)
- Outlier detection and handling
- Feature scaling
- Train-test splitting
- Regression modeling
- Model evaluation

---

## Data Preprocessing

The following preprocessing techniques were practiced:

### Missing Value Handling

Missing values were identified and handled using:

- Mean imputation
- K-Nearest Neighbors (KNN) imputation

The KNN imputation used 5 nearest neighbors.

### Categorical Encoding

Categorical features were encoded using `LabelEncoder`:

- `vehicle_class`
- `fuel_type`

### Outlier Handling

Outliers were identified using boxplots and handled using the **Interquartile Range (IQR)** method.

### Feature Scaling

`MinMaxScaler` was used to normalize the feature values before modeling.

---

## Exploratory Data Analysis

Several visualizations were created to explore the dataset, including:

- Histograms
- Correlation heatmap
- Scatterplots
- Boxplots

The analysis also explored relationships between fuel consumption variables and CO₂ emissions.

---

## Machine Learning Models

Three regression models were implemented:

- Linear Regression
- Ridge Regression
- Lasso Regression

The dataset was split into:

- **80% training data**
- **20% testing data**

using `random_state=42`.

---

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Linear Regression

| Metric | Score |
|---|---:|
| MAE | 11.21 |
| MSE | 425.86 |
| RMSE | 20.64 |
| R² | 0.865 |

### Ridge Regression

| Metric | Score |
|---|---:|
| MAE | 11.22 |
| MSE | 425.59 |
| RMSE | 20.63 |
| R² | 0.865 |

Linear Regression and Ridge Regression produced very similar results on the test set.

---

## Tools & Libraries

**Language**
- Python

**Libraries**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

** Machine Learning Techniques**
- KNN Imputation
- Label Encoding
- Min-Max Scaling
- Linear Regression
- Ridge Regression
- Lasso Regression

---

** Learning Context

This project was completed as part of the UKM Circle AI learning activities during my university studies.

The implementation followed the mentor's step-by-step guidance. The purpose of this project was to practice the concepts and workflow introduced during the study session.

This repository is maintained as part of my learning documentation and does not represent an independently designed machine learning project.
## Learning Outcomes

Through this guided project, I practiced implementing a basic machine learning workflow from data preprocessing and exploratory analysis to regression modeling and evaluation.

This project helped me become more familiar with the Scikit-learn workflow and the overall process of preparing data for machine learning.
