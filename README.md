# Binary Income Classification using Azure Machine Learning

A cloud-based binary classification project built in Azure ML Studio to predict whether an individual's income exceeds $50K using the Adult Census dataset. The workflow includes data preprocessing, model training, 
hyperparameter tuning, and evaluation using two algorithms: Two-Class Boosted Decision Tree and Two-Class Support Vector Machine.

## 🚀 Project Overview
- Cleaned and prepared the Adult Census dataset (missing values, feature handling).
- Split the dataset into training and testing subsets.
- Trained two classification models: **Boosted Decision Tree** and **SVM**.
- Performed **hyperparameter tuning** using 10-fold cross-validation.
- Evaluated models using AUC, F1 Score, Precision, Recall, and Accuracy.
- Identified the **Boosted Decision Tree** as the best-performing model (AUC = 0.926).

## 📊 Best Model Performance (Boosted Decision Tree)
- **AUC:** 0.926  
- **Accuracy:** 0.872  
- **Precision:** 0.775  
- **Recall:** 0.655  
- **F1 Score:** 0.71  

## 🧪 Pipeline Architecture
The Azure ML pipeline includes:
- Clean Missing Data  
- Split Data  
- Two-Class Boosted Decision Tree  
- Two-Class Support Vector Machine  
- Tune Model Hyperparameters  
- Score Model  
- Evaluate Model  

## 🛠️ Tech Stack
- Azure Machine Learning Studio  
- Binary Classification  
- Boosted Decision Trees  
- Support Vector Machine (SVM)  
- Hyperparameter Tuning  
- Cross-Validation  
- AUC Evaluation  
- Data Preprocessing  
