# 📊 Classifying Income Class and Loan Prediction

This repository contains the code and documentation for the **Classifying Income Class and Loan Prediction** project. The goal is to predict income class and use this insight to assist in **loan approval decisions**, applying statistical and machine learning techniques. This project was developed for a course in **Applied Statistics and Visualization for Analytics**.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Research Questions](#research-questions)
- [Dataset](#dataset)
- [Data Cleaning and Transformation](#data-cleaning-and-transformation)
- [Methodology and Models](#methodology-and-models)
- [Results and Special Efforts](#results-and-special-efforts)
- [Challenges](#challenges)
- [Future Work](#future-work)
- [Team](#team)

---

## 🧠 Project Overview

This project aims to address the challenge of predicting a person's **income class** and subsequently applying this prediction to assess **loan approval feasibility**. The study investigates associations between **demographic characteristics**, **work-related attributes**, and **income levels** in the United States using statistical models and machine learning algorithms.

The ultimate goal is to enhance **financial analytics** and support **responsible lending practices** by accurately identifying potential income classes.

---

## ❓ Research Questions

This study examines the following key questions:

1. Can we predict a person's income class based on their demographic and work-related attributes?  
2. Is there a significant difference in the distribution of income class, hours worked per week, education level, and age distribution among individuals from different native countries?  
3. Can we predict a person's capital gain based on age, hours worked per week, and years of education using appropriate machine learning techniques?

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository – Adult Data Set](https://archive.ics.uci.edu/ml/datasets/adult)  
- **Size**: 48,842 records  
- **Variables**: 14 attributes, including:
  - **Demographics**: `age`, `sex`, `race`, `marital-status`, `native-country`
  - **Work-related**: `workclass`, `education`, `education-num`, `occupation`, `relationship`, `capital-gain`, `capital-loss`, `hours-per-week`
  - **Target**: `income` (binary: >$50K or <=$50K)

---

## 🧹 Data Cleaning and Transformation

- Handled missing values (e.g., `"?"`) using imputation or row filtering  
- Transformed categorical variables into more interpretable groupings  
- Encoded factors for use in machine learning models

---

## 🧪 Methodology and Models

The project employs both **statistical analysis** and **machine learning algorithms**:

### 🔍 Exploratory Data Analysis (EDA)
- Visualized distributions, correlations, and demographic patterns affecting income

### 📊 Statistical Models
- Regression Analysis  
- Chi-squared Tests  
- T-tests  

### 🤖 Machine Learning Algorithms
- Logistic Regression with **LASSO regularization**  
- **Random Forest**  
- **Linear Regression** (for capital gain prediction)  
- **XGBoost Classifier**

### 📈 Evaluation Metrics
- Area Under ROC (AUC)  
- Accuracy  
- Precision  
- Recall

---

## 📱 Results and Special Efforts

- The models were able to **successfully predict income class** and **identify key predictors** (e.g., education, hours worked, capital gain).
- Two **Shiny Apps** were developed using R:

  #### 💡 Shiny App 1
  - Inputs: `Age`, `Education`, `Hours Worked`
  - Output: **Predicted Capital Gain**

  #### 💡 Shiny App 2
  - Inputs: All relevant variables from the dataset
  - Output: **Predicted Income Class**

---

## ⚠️ Challenges

- **Complexity of Dataset**: Cleaning and transforming a large dataset with multiple categorical features  
- **Class Imbalance**: Handling the disproportionate number of low-income vs high-income entries  
- **Model Interpretability**: Translating machine learning results into actionable business intelligence  
- **Avoiding Overfitting**: Balancing complexity with generalization for real-world applicability

---

## 🔮 Future Work

- **Advanced ML Methods**: Explore deep learning and ensemble techniques  
- **Expanded Data Sources**: Integrate alternative data like social media or real-time market trends  
- **Real-Time Analysis**: Build a live income classification and loan eligibility platform

---

## 👥 Team

- **Akhil Reddy Chimmula**  
- **Bhavesh Kurella**  
- **Shashank Yelagandula**

**Instructor**: Dr. Isuru Dassanayake

