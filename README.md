# Waze Churn Analysis (EDA & Statistical Testing)

## Project Overview

This project focuses on exploring user behavior data to identify patterns and factors contributing to churn by applying descriptive statistics and hypothesis testing in Python.

## Objective

The purpose of this project is to demostrate knowledge of how to conduct a two-sample hypothesis test.

## 🔍 Key Analysis Performed

* Data Cleaning and Preparation
* Exploratory Data Analysis (EDA)
* Visualization of user behavior patterns
* Hypothesis Testing

## 📊 Key Insights

1) It was observed that drivers who use an iPhone device to interact with the application have a higher number of drives on average. However, this difference might arise from random sampling, rather than being a true difference in the number of drives.

2) The key business insight is that drivers who use iPhone devices on average have a similar number of drives as those who use Androids.

## 📈 Hypothesis Testing

1) Since the p-value calculated was larger than the chosen significance level (5%), we fail to reject the null hypothesis. Hence the conclution is that there is not a statistically significant difference in the average number of drives between drivers who use iPhones and drivers who use Androids.


## 📁 Project Files

* [📓 Notebook](notebooks/waze_churn_eda_analysis_and_hypothesis_testing.ipynb)

## 🚀 Tools & Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy

