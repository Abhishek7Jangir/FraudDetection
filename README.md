# Employee Attrition Prediction

## Overview

This project predicts employee attrition using machine learning techniques. It involves data preprocessing, feature engineering, model training, and evaluation to determine key factors influencing employee turnover.

## Dataset

The dataset is sourced from:
[GitHub - YBI Foundation](https://github.com/YBI-Foundation/Dataset/raw/refs/heads/main/EmployeeAttrition.csv)
It contains various employee-related attributes such as:

- Age
- Job Role
- Salary
- Years at Company
- Work-Life Balance
- Attrition Status (Target Variable)

## Project Structure

- **EmployeeAttrition.ipynb** - Google Colab Notebook containing data loading, preprocessing, exploratory data analysis (EDA), model training, and evaluation.

## Dependencies

Run the following command in a Colab cell to install dependencies:

```python
!pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
```

## Steps to Run the Notebook

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `EmployeeAttrition.ipynb` or open it from Google Drive.
3. Run all cells sequentially.

## Machine Learning Models Used

- Random Forest Classifier
- Logistic Regression

## Key Features of the Code

- Data preprocessing with **Label Encoding** and **Standard Scaling**
- Handling class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**
- Model training and evaluation using accuracy, precision, recall, F1-score, and confusion matrix

## Key Findings

- Work-life balance and salary have a strong correlation with attrition.
- Employees in specific job roles are more likely to leave.
- The **Random Forest model** provides better accuracy compared to Logistic Regression.

## Future Improvements

- Use additional models like **XGBoost** or **Neural Networks**.
- Perform hyperparameter tuning for better accuracy.
- Implement feature selection for better interpretability.

## Author

[Abishek Jangir]

## License

This project is for educational purposes only.

