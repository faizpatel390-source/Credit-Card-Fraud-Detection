# 💳 Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview

Credit Card Fraud Detection is a Machine Learning project that identifies fraudulent credit card transactions and distinguishes them from legitimate transactions.

The main objective of this project is to build a classification model that can detect suspicious transactions and help reduce financial fraud.

This project uses Python and Machine Learning algorithms to analyze transaction data and predict whether a transaction is fraudulent or legitimate.

## 🎯 Objectives

- Analyze credit card transaction data.
- Perform data cleaning and preprocessing.
- Handle imbalanced datasets.
- Perform Exploratory Data Analysis (EDA).
- Build Machine Learning classification models.
- Evaluate model performance using different metrics.
- Identify fraudulent transactions accurately.

## 📂 Dataset

**Dataset:** Credit Card Fraud Detection Dataset (Kaggle)

The dataset contains credit card transactions made by European cardholders.

Dataset characteristics:
- Total transactions: 284,807
- Legitimate transactions: 284,315
- Fraudulent transactions: 492
- Target column: `Class`

Target variable:
- `0` – Legitimate Transaction
- `1` – Fraudulent Transaction

The dataset contains anonymized transaction features (`V1` to `V28`), along with `Time`, `Amount`, and `Class`.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Checked dataset shape and structure.
- Examined column names and data types.

### 2. Data Cleaning
- Checked for missing values.
- Checked for duplicate records.
- Removed duplicate records where necessary.

### 3. Exploratory Data Analysis (EDA)
- Analyzed fraudulent and legitimate transactions.
- Visualized transaction distribution.
- Examined transaction amounts.
- Identified class imbalance.

### 4. Data Preprocessing
- Separated independent and dependent variables.
- Applied feature scaling where appropriate.
- Split the dataset into training and testing sets.
- Used stratified splitting to maintain class distribution.

### 5. Model Building

Machine Learning algorithms:
- Logistic Regression
- Random Forest Classifier

### 6. Model Evaluation

Evaluated models using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

**Note:** Precision, Recall, and F1-score are particularly important because fraudulent transactions represent a very small percentage of the dataset.

## 📊 Expected Outcome

The model predicts whether a credit card transaction is:

- Legitimate (0)
- Fraudulent (1)

The project demonstrates how Machine Learning can be applied to financial fraud detection problems.

## 🚀 How to Run This Project

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

**Step 2: Install required libraries**

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

**Step 3: Open Jupyter Notebook**

```bash
jupyter notebook
```

**Step 4:** Open the project notebook and run the cells sequentially.

## 📁 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── data/
│   └── creditcard.csv
│
├── credit_card_fraud_detection.ipynb
│
├── README.md
│
└── requirements.txt
```

## 💡 Key Learnings

- Understanding real-world financial datasets.
- Data cleaning and preprocessing.
- Exploratory Data Analysis.
- Handling imbalanced
