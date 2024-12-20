# Credit Card Fraud Detection

This repository contains a Jupyter Notebook implementing a machine learning pipeline for detecting fraudulent credit card transactions.

## Description

Credit card fraud detection is an essential task in the financial sector. This project uses machine learning to classify transactions as fraudulent or legitimate. The notebook includes data preprocessing, exploratory data analysis, model training, and evaluation.

## Dataset

The dataset used in this project is publicly available on Kaggle:

[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### Dataset Details:
- Contains 284,807 transactions, with only 492 labeled as fraudulent.
- Highly imbalanced data.
- Features include anonymized principal components (from PCA), transaction time, and amount.

## Files

- `Credit_Card_Fraud_Detection.ipynb`: The Jupyter Notebook containing the complete code for data preprocessing, model training, and evaluation.

## Requirements

To run the notebook, you will need the following Python libraries:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### Usage
1. Clone this repository:

```bash
git clone https://github.com/yourusername/Credit_Card_Fraud_Detection.git
cd Credit_Card_Fraud_Detection
```
2. Open the Jupyter Notebook:

```bash
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```
3. Run the cells step by step to preprocess the data, train the model, and evaluate its performance.