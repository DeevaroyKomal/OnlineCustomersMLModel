# OnlineCustomersMLModel

## Online Retail Customer Purchase Prediction

This repository contains a machine learning project that predicts whether a customer will make a purchase based on retail behavior and demographic data. The model uses classification techniques and exploratory data analysis to provide insights into customer buying patterns.

## Dataset

The dataset includes customer information such as:
- Age, Gender, Annual Income  
- Spending behavior (Total Spend, Num_of_Purchases)  
- Engagement and support metrics  
- Target variable indicating customer purchase (derived from churn)

##  Workflow

1. **Data Loading & Understanding**  
   Load dataset and understand structure, features, and target variable.

2. **Data Preprocessing**  
   Handle missing values, encode categorical features, scale numerical columns, and split data for model training.

3. **Exploratory Data Analysis (EDA)**  
   Visualize distributions, correlations, and customer behavior patterns.

4. **Model Building**  
   Train multiple classification models:
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - K-Nearest Neighbors (KNN)

5. **Model Evaluation**  
   Compare models using accuracy, precision, recall, F1-score, and confusion matrices to select the best performer.

##  Results

Random Forest performed best with highest overall evaluation metrics. Visual comparisons and confusion matrices are included in the notebook.

