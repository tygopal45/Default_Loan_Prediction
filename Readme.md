# 🏦 Loan Predictor - Machine Learning Project

A machine learning system that predicts whether a borrower is eligible for a loan based on financial and credit history available at the time of application.

### 📌 Overview

Peer-to-Peer (P2P) lending connects borrowers directly with individual lenders through online platforms such as Lending Club. These platforms publish historical data, enabling research on whether loan features can predict loan performance.
This project builds a loan approval prediction module using only origination-time features for individual and joint applicants.

### 🎯 Objectives

Predict loan eligibility (approved / likely to default).

Use only non-leaky, pre-loan features.

Compare multiple ML models and select the best performer.

### 🔍 Features

Key attributes used:

Loan amount, income etc

Debt-to-income ratio

Purpose of loan

FICO score

Reconstructed Grade, Sub-Grade, and Interest Rate (derived from FICO)

### ⚙️ Machine Learning Approach

Tested models include Logistic Regression, Random Forest, Gradient Boosting, XGBoost, and SVM.
Evaluated using accuracy, precision, recall, F1, and ROC-AUC.
Separate optimized models were built for individual and joint applicants.

### 🚀 How It Works

User enters financial / credit inputs.

Model preprocesses and transforms the data.

System outputs loan eligibility prediction.

### 🗂️ Project Structure

Loan_Predictor

├── Data              
├── Jupyter_Notebooks            
├── static    
├── templates    
├── app.py             
└── Readme.md  

### 🧪 Tech Stack

Python • Scikit-learn • XGBoost • Jupyter Notebook • FLask • HTML • CSS • JS   

###  📁 Dataset

Historical Lending Club loan data.

### 🙌 Acknowledgements

This project draws inspiration from publicly available P2P lending datasets and incorporates insights from Kunal Goyal’s thesis on loan default prediction.