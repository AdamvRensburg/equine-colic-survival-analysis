# Clinical Clues to Survival in Horses Affected by Colic
### A Statistical Analysis of Key Clinical Indicators in Equine Colic  
**Author:** Adam van Rensburg  
**Date:** December 2025  

---

## 📌 Project Overview
This project analyzes clinical data from 127 horses affected by colic to determine whether specific clinical signs—**pain level**, **abdominal distention**, and **mucous membrane color**—are related to survival outcomes. Using R and R Markdown, the analysis includes data cleaning, exploratory heatmap visualizations, and logistic regression modeling to quantify the relationship between clinical signs and survival.

This project was completed for a statistical data analysis course and also reflects my interest in animal science and applying data-driven methods to real clinical situations.

---

## 🎯 Research Question
**Are certain clinical signs related to survival outcomes in horses affected by colic?**

Specifically:
- Does pain level predict the likelihood of survival?
- Does abdominal distention indicate severity and risk?
- Does mucous membrane color provide meaningful diagnostic information?

---

## 🧪 Methods

### ✔ Data Cleaning & Preparation
- Removed missing values  
- Re-coded factor levels  
- Selected relevant variables (clinical signs + vital parameters)  

### ✔ Exploratory Data Analysis (EDA)
- Heatmap visualization of survival proportions  
- Summary statistics to understand variable distributions  

### ✔ Logistic Regression
A logistic regression model was used to determine which clinical signs significantly affect the probability of survival. Odds ratios were calculated for easier interpretation of model coefficients.

---

## 📊 Key Findings
- **Pain level** is a strong indicator of survival. Horses experiencing severe or extreme pain had substantially lower survival rates.
- **Abdominal distention** also showed a strong relationship with outcome, with moderate and severe distention linked to poor prognosis.
- **Mucous membrane color** displayed some variation in survival but was not as strong or consistent as the other predictors.
- Logistic regression confirmed these findings, with several predictor levels showing significant effects on survival.

---

## 🛠 Tools & Technologies Used
- **R**  
- **R Markdown**  
- **tidyverse / dplyr**  
- **ggplot2**  
- **broom**  
- **knitr**  

---

## 📁 Repository Structure

