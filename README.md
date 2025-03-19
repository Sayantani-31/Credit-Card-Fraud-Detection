# Credit Card Fraud Detection  

## Overview  
This project focuses on detecting fraudulent credit card transactions using machine learning models. Given the highly imbalanced nature of fraud detection datasets, various resampling techniques were applied to improve model performance. The results were compared across different models to evaluate their effectiveness in identifying fraudulent transactions.  

## Dataset  
The dataset consists of real-world credit card transactions with the following characteristics:  
- **Features**: A set of anonymized numerical variables representing transaction details.  
- **Target Variable**: Binary classification where:  
  - **0** → Legitimate transaction  
  - **1** → Fraudulent transaction  

## Data Preprocessing  
To handle data imbalance, the following techniques were applied:  
- **Oversampling**: Synthetic Minority Over-sampling Technique (SMOTE) was used to generate synthetic fraud cases.  
- **Undersampling**: Randomly reduced the number of non-fraud cases to balance the dataset.  

## Models Used  
The following machine learning models were trained and evaluated on both oversampled and undersampled datasets:  
- **Decision Tree**  
- **Logistic Regression**  
- **Random Forest**  

## Results  
Each model's performance was compared using key metrics such as:  
- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1-Score**  
- **ROC-AUC Score**  

Comparing the models under both resampling strategies provided insights into how different approaches affect fraud detection performance.  
