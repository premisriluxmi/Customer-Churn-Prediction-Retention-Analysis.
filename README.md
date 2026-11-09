# Customer Churn Prediction & Retention Analysis

## Project Overview
Customer Churn Prediction & Retention Analysis is a machine learning project that aims to identify customers who are likely to leave a subscription-based service.

The project analyzes customer data, identifies churn patterns, trains classification models, and provides retention recommendations to help businesses improve customer relationships.

## Project Objectives
- Understand customer churn patterns through Exploratory Data Analysis.
- Clean and preprocess customer data.
- Build machine learning models to predict customer churn.
- Compare model performance using evaluation metrics.
- Identify important factors influencing customer churn.
- Predict customer churn risk.
- Provide customer retention recommendations.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset
The project uses the **Telco Customer Churn Dataset** from Kaggle.

Dataset link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

It contains customer details, subscription information, services, monthly charges, total charges, tenure, and churn status.

## Project Workflow

### Day 1 – Data Understanding and Exploratory Data Analysis
- Loaded and explored the customer churn dataset.
- Checked dataset dimensions, data types, missing values, and duplicates.
- Analyzed customer churn distribution.
- Explored customer demographics, contract types, payment methods, monthly charges, and tenure.
- Created visualizations to understand customer behaviour.

### Day 2 – Data Cleaning and Preprocessing
- Handled missing values.
- Converted TotalCharges into numeric format.
- Checked and removed duplicate records.
- Removed unnecessary customer ID column.
- Encoded the target variable.
- Converted categorical variables into numerical format.
- Separated features and target variables.

### Day 3 – Machine Learning Model Training and Evaluation
- Split the dataset into training and testing sets.
- Trained three classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC.
- Generated confusion matrices and ROC curves.
- Compared model performance.

### Day 4 – Model Comparison and Churn Prediction
- Compared the performance of all trained models.
- Identified the best-performing model based on F1-score.
- Analyzed important features influencing churn.
- Developed a customer churn risk prediction function.
- Classified customers into low, medium, and high risk.
- Generated customer retention recommendations.

## Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

## Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction_Day1.ipynb
├── Customer_Churn_Prediction_Day2.ipynb
├── Customer_Churn_Prediction_Day3.ipynb
├── Customer_Churn_Prediction_Day4.ipynb
│
├── customer_churn_dataset.csv.csv
├── customer_churn_day1.csv
├── customer_churn_preprocessed.csv
│
├── logistic_regression_model.pkl
├── decision_tree_model.pkl
├── random_forest_model.pkl
├── best_churn_model.pkl
│
├── customer_churn_model_comparison.csv
├── final_model_comparison.csv
├── customer_churn_feature_importance.csv
│
└── README.md
```

## Expected Outcome
The project aims to identify customers who may churn, understand the factors contributing to churn, and support businesses in taking proactive customer retention measures.

## Internship
**Veda Technology – AI & ML Internship**

**Mini Project 2: Customer Churn Prediction & Retention Analysis**

## Author
Premi Sri Luxmi G.
