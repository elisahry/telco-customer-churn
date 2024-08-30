# telco-customer-churn
JCDS Purwadhika On Campus Bandung - Capstone Project Modul 2 - Telco Customer Churn - Elisa Hariyanti

Telco Customer Churn Prediction
📊 Overview
This repository contains a project aimed at predicting customer churn in the telecommunications industry using machine learning models. The goal is to identify the factors contributing to customer churn and build a model that can effectively predict which customers are likely to discontinue their service, allowing the company to implement targeted retention strategies.

📝 Project Description
Customer churn is a significant challenge in the telecommunications industry, where retaining existing customers is often more cost-effective than acquiring new ones. This project involves analyzing customer data to identify patterns and factors that lead to churn. By applying machine learning techniques, we aim to build a predictive model that helps the company proactively address churn and improve customer retention.

🚀 Usage
Prepare the data: Ensure you have the dataset in the data/ directory.

Run the notebook: Open CP3-telco-churn-elisa.ipynb in Jupyter Notebook or JupyterLab and execute the cells step-by-step to reproduce the analysis and model training.

Model Evaluation: Use the final trained model to evaluate its performance and understand the most critical factors influencing customer churn.

🔍 Key Features
Data Exploration & Preprocessing: Analyze and clean the data, handle missing values, encode categorical variables, and normalize numerical features.
Feature Engineering: Create new features that could improve model performance based on domain knowledge.
Model Training & Tuning: Train various machine learning models, including AdaBoost, and fine-tune them using techniques like cross-validation and hyperparameter tuning.
Evaluation & Insights: Evaluate model performance using metrics like F2-score, precision, recall, and ROC-AUC, and derive actionable insights to reduce customer churn.
📊 Results
The best-performing model was AdaBoostClassifier with an F2-score of 76.18%. Key features influencing churn included contract type, tenure, internet service type, and monthly charges.

By using machine learning predictions, the company can save approximately $19,251.4 per month in retention costs compared to not using predictive models.
