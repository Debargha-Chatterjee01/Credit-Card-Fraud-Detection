# Credit Card Fraud Detection

This project aims to build a machine learning model to detect fraudulent credit card transactions. The dataset, available on [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), contains anonymized transaction features and class labels indicating fraud.

## Project Overview

1. **Data Preprocessing:**  
   The data is cleaned and normalized. Missing values and outliers are handled, and categorical variables are transformed.

2. **Class Imbalance Handling:**  
   Techniques like **SMOTE** and **undersampling** are used to balance the dataset due to the class imbalance, where fraud is rare.

3. **Modeling:**  
   Classification algorithms such as **Logistic Regression**, **Decision Trees**, and **Random Forest** are trained to predict fraudulent transactions.

4. **Evaluation:**  
   Model performance is evaluated using **precision**, **recall**, and **F1-score** to ensure effective fraud detection.

## Technologies Used

- **Python**  
- **Libraries:** scikit-learn, pandas, imbalanced-learn, matplotlib  
- **Data Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## File Description

- **`credit_card_fraud_detection.ipynb`**: Contains the full project workflow, from data preprocessing to model evaluation.
