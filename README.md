#  Phishing URL Prediction

A machine learning project to detect whether a given website URL is **legitimate** or **phishing** using various classification models.

## 📌 Project Overview

Phishing attacks are a major cyber threat where attackers trick users into revealing sensitive information by impersonating trustworthy websites. This project aims to detect phishing websites based on various features extracted from the URL and webpage content.

We use a labeled dataset and apply multiple machine learning models to predict whether a given website is phishing or not.

##  Features

- Exploratory Data Analysis (EDA)
- Feature engineering & preprocessing
- Multiple ML models (Logistic Regression, Random Forest, XGBoost, etc.)
- Model evaluation (accuracy, confusion matrix, ROC-AUC)
- Visualization of results
- Final prediction on new unseen sample 

## 📁 Dataset

**Source**: [UCI Machine Learning Repository – Phishing Websites Dataset](https://archive.ics.uci.edu/ml/datasets/phishing+websites)

- Instances: ~235795
- Features: 54
- Target: `-1` (Phishing), `0` (Legitimate)

## 🛠 Tech Stack

- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib / seaborn
  - xgboost 

##  Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Naive Bayes
- Support Vector Machine (SVM)


## 📊 Results

| Model              | Accuracy |
|--------------------|----------|
| Logistic Regression| 99%      |
| Random Forest      | 99%      |
| Naive Bayes        | 85%      |
| SVM                | 99%      |
| Decision Tree      | 99%      |
*(Note: Actual values may vary based on train-test split and parameters)*

## 📝 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/phishing-url-prediction.git
   cd phishing-url-prediction
