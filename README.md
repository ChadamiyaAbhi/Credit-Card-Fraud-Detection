# Credit Card Fraud Detection

This project implements a machine learning model to detect fraudulent credit card transactions.

## Setup Instructions

1. Download the dataset:
   - Go to https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
   - Download the creditcard.csv file
   - Place it in the project root directory

2. Install dependencies:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib imbalanced-learn joblib
```

3. Run the Jupyter notebook:
```bash
jupyter notebook "Credit Card Fraud Detection.ipynb"
```

## Project Structure

- `Credit Card Fraud Detection.ipynb`: Main Jupyter notebook containing the analysis and model training
- `credit_card_model.pkl`: Trained model saved for future use
- `requirements.txt`: List of Python package dependencies
- `creditcard.csv`: Dataset file (needs to be downloaded)

## Model Performance

The project implements multiple models:
1. Logistic Regression
2. Decision Tree Classifier

After handling class imbalance using SMOTE, the Decision Tree Classifier achieves:
- Accuracy: 99.82%
- Precision: 99.76%
- Recall: 99.88%
- F1 Score: 99.82%