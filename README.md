# Boston Housing Price Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-Model-brightgreen)
![RandomForest](https://img.shields.io/badge/RandomForest-Model-orange)

##  Table of Contents
- [Introduction](#introduction)
- [Business Background](#business-background)
- [Analysis Method](#analysis-method)
- [Tech Stack](#tech-stack)
- [Dataset Overview](#dataset-overview)
- [Model Evaluation and Summary](#model-evaluation-and-summary)
- [Links to Code and Kaggle Dataset](#links-to-code-and-kaggle-dataset)

---

##  Introduction

This project aims to **predict the selling price of houses in the city of Boston (USA)** by applying Machine Learning techniques.  
Using a well-known **Boston Housing Dataset**, we can uncover key factors affecting prices and develop models to accurately forecast future selling prices.

---

##  Business Background

Accurate pricing models are valuable for:
- Home sellers pricing their properties appropriately
- Buyers estimating a fair price to pay
- Real estate companies making profitable decisions
- Policy makers and city planners understanding the factors that affect housing prices in their area

---

##  Analysis Method

1️⃣ **Import and explore the data:**  
Checked for missing values, understood the distribution of each feature.

2️⃣ **Detect and handle outliers:**  
Some apparent “outliers” were predominantly high or low in certain attributes; we kept them to reflect the true nature of the market.

3️⃣ **Feature selection:**  
Features like **LSTAT**, **RM**, **DIS**, and **CRIM** were found to be key contributors to the pricing.

4️⃣ **Model Implementation:**  
We applied and evaluated 3 regression models:
- **Linear Regression**
- **Random Forest Regressor**
- **Support Vector Machine (SVM)**

---

##  Tech Stack

- **Python:** pandas, scikit-learn, matplotlib, seaborn
- **Jupyter Notebook:** Google Colab
- **Scikit-Learn:** regression models, evaluation metrics
- **Matplotlib/Seaborn:** for visualization of data and results

---

##  Dataset Overview

➥ The **Boston Housing** dataset comprises 14 attributes (including the target) describing houses in the area.

➥ **Features:**  
- **CRIM:** per capita crime rate by town  
- **ZN:** residential land proportions  
- **INDUS:** non-retail acres per town  
- **CHAS:** 1 if tract bounds river, 0 otherwise  
- **NOX:** nitric oxides concentration  
- **RM:** average number of rooms  
- **AGE:** proportion of houses built before 1940  
- **DIS:** distances to employment centers  
- **RAD:** index of highway accessibility  
- **TAX:** property-tax rate  
- **PTRATIO:** pupil-teacher ratio  
- **B:** 1000(Bk - 0.63)^2 — Black population indicator  
- **LSTAT:** % lower-status population  
- **MEDV:** Median Home Values (Target)

➥ [Kaggle Dataset Link](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices)

---

##  Model Evaluation and Summary

| Model | R² (%) | MAE | MSE | RMSE | Max Error |
|------------|---------|---------|---------|---------|---------|
| **Linear Regression** | 71.16 | Medium | Medium | Medium | Low |
| **Support Vector Machine (SVM)** | 80.98 | Lower than LR | Lower than LR | Lower than LR | Higher max error |
| **Random Forest** | **83.17** | **Lowest** | **Lowest** | **Lowest** | Lower max error |  

The **Random Forest Model** performs the best in all key metrics — highest R², and lowest error — indicating it's most suitable for this regression problem.

---

##  Links to Code and Kaggle Dataset

➥ [Python Code (Colab)](https://colab.research.google.com/)  
➥ [Kaggle Dataset](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices)

---

If you'd like more details or a walkthrough, please feel free to [contact me](mailto:annizamegabianalyst@gmail.com).

