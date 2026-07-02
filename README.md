# Fairness and Explainability in Machine Learning (Adult Income Dataset)

## Project Overview

This project explores fairness and explainability in machine learning using the Adult Income dataset. The goal is to predict whether an individual earns more than $50,000 per year while also evaluating whether the model behaves fairly across gender groups.

A logistic regression model was trained, and fairness was analyzed using Fairlearn metrics. SHAP and LIME were used to explain how the model makes predictions.

---

## Dataset

The dataset used is the **Adult Income dataset**, which includes demographic and employment-related features such as age, education, occupation, and gender.

Target variable:
- Income (>50K or <=50K)

Sensitive attribute:
- Gender (sex)

---

## Tools and Libraries

- Python
- Pandas
- Scikit-learn
- Fairlearn
- SHAP
- LIME
- Matplotlib

---

## Project Steps

1. Data preprocessing (handling missing values and encoding categorical variables)
2. Feature selection and target definition
3. Training a Logistic Regression model
4. Model evaluation (accuracy, confusion matrix, classification report)
5. Fairness analysis using Fairlearn
6. Explainability using SHAP and LIME

---

## How to Run the Project

1. Clone the repository
```bash
git clone https://github.com/your-username/fairness-ml-adult-income.git
``` 
2. Navigate into the folder cd fairness-ml-adult-income
3. Install dependencies
pip install -r requirements.txt
4. Run the notebook

Open the Jupyter Notebook and run all cells in order.
