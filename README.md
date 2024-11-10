[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MuhammadAbbas01/Predict-Crime-rate/blob/main/Untitled10.ipynb)

## 1 - Introduction

This dataset contains crime statistics from U.S. cities in 1975, including data on violent crimes like homicides, rapes, assaults, and robberies. It provides insights into the relationship between population size and crime rates. The goal of this analysis is to explore crime patterns across cities and assess the impact of demographic factors on crime rates, helping to inform future crime prevention strategies.

---

## 2 - Objectives

The objectives of this project are:
- To clean and preprocess crime data for further analysis.
- To explore crime patterns and their relationships with population size and other socio-economic factors.
- To build machine learning models to predict crime rates across U.S. cities.
- To compare the performance of different models, including Logistic Regression, K-Nearest Neighbors (KNN), Random Forest, Stacking Classifier, AdaBoost, and XGBoost.

---

## 3 - Data Cleaning and Preprocessing

### 3.1 - Handling Missing Values
- The dataset may contain missing or null values. These were handled by either imputation or removal of rows with missing data, depending on the situation.

### 3.2 - Removing Duplicates
- Duplicate entries were checked and removed to ensure the integrity of the analysis.

---

## 4 - Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) was conducted to:
- Examine the distribution of crime rates across cities.
- Visualize the correlation between population size and violent crime rates.
- Identify any outliers or patterns in the dataset.

---

## 5 - Correlation Analysis

This section analyzes the correlation between crime-related variables and other features like population size. Heatmaps and scatter plots were used to visualize these relationships and understand the impact of socio-economic factors on crime rates.

---

## 6 - Feature Scaling

Feature scaling was performed to standardize the data and prepare it for modeling. This process ensures that all features contribute equally to the model's predictions.

---

## 7 - Modeling

Several machine learning models were implemented to predict crime rates:

### 7.1 - Logistic Regression
- A baseline classification model to predict the likelihood of violent crimes.

### 7.2 - K-Nearest Neighbors (KNN)
- A non-parametric method used to classify crime rates based on similar cities' characteristics.

### 7.3 - Random Forest Classifier
- An ensemble learning method that improves accuracy by averaging multiple decision trees.

### 7.4 - Stacking Classifier
- A model that combines multiple classifiers to improve overall prediction performance.

### 7.5 - AdaBoost Classifier
- A boosting algorithm that combines multiple weak classifiers to create a strong predictive model.

### 7.6 - XGBoost Classifier
- A powerful gradient boosting model known for its high performance in classification tasks.

---

## 8 - Conclusion

The project successfully built and evaluated various classification models to predict crime rates based on socio-economic factors. The Random Forest and XGBoost models performed the best, offering strong predictive power for crime prevention strategies.

---

## 9 - Next Steps

Future work will include:
- Exploring additional data sources for improved model accuracy.
- Refining the clustering techniques used for crime prediction.
- Implementing a real-time prediction system for crime rates.

---

## 10 - Key Insights

- A significant correlation was found between population size and violent crimes in U.S. cities.
- Socio-economic factors such as income and education also play a role in crime rates.

---

## 11 - Suggestions

- Policymakers can use these insights to target interventions in high-risk areas.
- Further research can explore predictive modeling with more granular data (e.g., at the neighborhood level) to refine crime prevention strategies.

---

### Requirements
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Usage
Clone this repository and run the `crime_analysis.ipynb` notebook to view the analysis and models.

---
