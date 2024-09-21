# Verizon Customer Default Prediction

This project focuses on building a **machine learning model** to predict customer default on contract payments for Verizon. The goal is to identify customers at risk of defaulting on their phone contracts to minimize revenue loss and optimize Verizon's decision-making process.

## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Methodology](#methodology)
- [Model Selection](#model-selection)
- [Business Value](#business-value)
- [Results](#results)

## Project Overview
As the largest wireless carrier in the U.S., Verizon aims to minimize defaults on customer contracts. This project involves developing a predictive model based on customer attributes such as **age**, **credit score**, **down payment**, and **payment type**. The model helps Verizon identify high-risk customers and make informed decisions about granting or declining contracts.

## Problem Statement
Currently, **12% of Verizon’s customers default** on their contracts, leading to significant revenue losses. The aim is to build a model that can accurately predict which customers are likely to default and which are reliable, helping Verizon to maximize profit and minimize risks.

## Methodology
### Data Sources
- Historical customer data including age, gender, credit score, down payment, and contract payment history.

### Key Features
- **Payment type**, **credit score**, and **down payment** were found to be the most significant predictors of default.

### Metrics for Success
- Reducing false positives (rejecting reliable customers) and false negatives (approving high-risk customers).
- Optimizing profits by minimizing defaults and improving contract acceptance rates.

## Model Selection
The **Multi-Layer Perceptron (MLP)** was selected as the best-performing model due to its ability to handle non-linear relationships and **imbalanced data**. Other models evaluated included **XGBoost** and **Isolation Forest**, but MLP demonstrated the highest accuracy, recall, and F1 score.

## Business Value
- **Profit Gained**: $200 million per million applicants.
- **Revenue Loss Avoided**: $88.9 million by preventing defaults.
  
The model correctly identified **91% of customers** who would make payments and prevented **75% of defaults**.

## Results
The MLP model successfully identified high-risk customers with an **accuracy of 90%** and a **ROC-AUC score of 0.94**, offering a significant reduction in revenue loss and enhancing Verizon's customer retention strategy.
