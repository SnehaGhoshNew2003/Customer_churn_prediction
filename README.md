# Customer Credit Card Churn Prediction

## Overview
This project predicts whether a customer will churn (leave) based on their credit card usage behavior. It uses machine learning techniques to analyze key factors like credit score, account balance, and activity level.

## Dataset
- **Source**: Kaggle - Credit Card Churn Dataset
- **Features**:
  - Credit Score
  - Geography (Country)
  - Gender
  - Age
  - Tenure (Years with the bank)
  - Balance
  - Number of Products
  - Has Credit Card (Yes/No)
  - Is Active Member (Yes/No)
  - Estimated Salary
  - **Exited** (Target Variable - 1 if churned, 0 otherwise)

## Dependencies
To run this project, install the required dependencies:
```bash
pip install numpy pandas matplotlib scikit-learn seaborn
```

## Setup & Execution
1. Clone or download the repository.
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Customer_Credit_Card_Churn_Prediction.ipynb
   ```
3. Follow the notebook cells to preprocess data, train models, and evaluate performance.

## Model Used
- **Classification Models** (e.g., Logistic Regression, Random Forest, XGBoost)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC

## Results
- The model predicts customer churn with high accuracy.
- Performance is evaluated using classification metrics.

## Future Improvements
- Use deep learning models for better prediction.
- Deploy the model using Flask or FastAPI for real-time predictions.

