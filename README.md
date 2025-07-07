# Marketing Campaign Analysis – Predictive Modeling

This project analyzes a telecommunications marketing campaign dataset to predict customer subscription likelihood and generate actionable business insights.

It was developed for the course Statistical Thinking for Data Science (36103) in the Master of Data Science and Innovation program at the University of Technology Sydney (UTS).

---

## Project Summary

We applied both parametric and non-parametric machine learning models to predict whether a customer would subscribe to a marketing campaign.

### Models Used:
- Logistic Regression with L2 regularization
- Random Forest Classifier

### Key Steps:
- Data cleaning and preprocessing
- Feature engineering and encoding
- Cross-validation and threshold optimization
- Model evaluation and comparison

---

## Files Included

- `KunalGurung_DataAnalysisProject_10_11_2024.ipynb`: Full EDA, modeling, and evaluation notebook
- `requirements.txt`: Python package list for environment setup

---

## Dataset

- Source: Provided via course materials
- Target variable: `Subscribed` (binary outcome: Yes/No)
- Features: Call duration, number of contacts, education, communication type, previous outcomes, consumer confidence index, etc.

---

## Methods

### Data Preprocessing
- Handled missing values
- Encoded categorical features
- Engineered new features to enhance model performance

### Model Training
- Trained Logistic Regression (interpretable baseline)
- Trained Random Forest (non-linear modeling)
- Applied cross-validation and hyperparameter tuning
- Performed threshold optimization for business use cases

### Evaluation Metrics
- Accuracy
- AUC-ROC
- Precision, Recall, F1-Score
- Confusion matrix

---

## Results

| Model              | Accuracy | AUC-ROC | Use Case              |
|-------------------|----------|---------|------------------------|
| Logistic Regression | 82%      | 0.913   | Broad targeting        |
| Random Forest       | 88%      | 0.937   | Precision targeting    |

- Call duration was the strongest predictor across both models.
- Repeated contact attempts positively influenced subscription rates.

---

## Business Insights

- Longer and more meaningful customer interactions increase the likelihood of conversion.
- Random Forest is effective for precision marketing where false positives are costly.
- Logistic Regression is suitable for wide outreach campaigns where interpretability is preferred.

---

## Technologies Used

- Python
- Libraries: pandas, scikit-learn, matplotlib, seaborn, statsmodels, imblearn, skopt
- Jupyter Notebook
- Cross-validation and hyperparameter tuning

---

## Future Improvements

- Integrate external features such as customer satisfaction or competitor activity
- Apply gradient-boosting models (e.g., XGBoost, LightGBM)
- Expand dataset across industries for broader applicability
- Explore deep learning if the dataset size increases

---

## Academic Integrity Notice

This repository is shared publicly for educational demonstration only. Unauthorized copying or submission of this work for academic credit is strictly prohibited and may be considered academic misconduct.

---

## Author

Kunal Gurung
Master of Data Science and Innovation  
University of Technology Sydney
