# Fraud Detection using Machine Learning  

## Overview

This project focuses on detecting fraudulent transactions using machine learning techniques. The dataset contains transaction details, and the goal is to build a model that accurately classifies transactions as fraudulent or non-fraudulent.

## Dataset

The dataset used is sourced from Kaggle:
[Kaggle Fraud Detection Dataset](https://www.kaggle.com/datasets)
It contains transaction-related attributes such as:

- Transaction Type
- Amount
- Sender & Receiver Information
- Balance Before & After Transaction
- Fraudulent Indicator (Target Variable)

## Project Structure

- **fraud\_detection.ipynb** - Google Colab Notebook containing data loading, preprocessing, exploratory data analysis (EDA), model training, and evaluation.

## Dependencies

Run the following command in a Colab cell to install dependencies:

```python
!pip install pandas numpy scikit-learn imbalanced-learn
```

## Steps to Run the Notebook

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `fraud_detection.ipynb` or open it from Google Drive.
3. Run all cells sequentially.

## Machine Learning Models Used

- Random Forest Classifier
- Logistic Regression

## Key Features of the Code

- Data preprocessing with **Label Encoding** and **Standard Scaling**
- Handling class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**
- Model training and evaluation using accuracy, precision, recall, F1-score, and confusion matrix

## Key Findings

- Certain transaction types are more prone to fraud.
- Fraudulent transactions tend to have specific patterns in amounts and balances.
- The **Random Forest model** provides better accuracy compared to Logistic Regression.

## Future Improvements

- Use additional models like **XGBoost** or **Neural Networks**.
- Perform hyperparameter tuning for better accuracy.
- Implement real-time fraud detection mechanisms.

## Author

[Abhishek Jangir]

## License

This project is for educational purposes only.

