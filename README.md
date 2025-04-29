⚠️ Academic Integrity Notice: This repository is shared publicly for learning and demonstration purposes only. Unauthorized copying or direct submission of this work for academic credit is strictly prohibited and may be considered academic misconduct.

# 📊 Marketing Campaign Analysis – Predictive Modeling

This project analyzes a telecommunications marketing campaign dataset to predict customer subscription likelihood and extract actionable business insights.  
It was developed as part of the **Statistical Thinking for Data Science (36103)** course at the **University of Technology Sydney (UTS)**.

## 📄 Project Overview
- Built and evaluated **Logistic Regression** (parametric) and **Random Forest** (non-parametric) models.
- Identified key customer attributes (e.g., call duration, contact method) influencing subscription likelihood.
- Applied cross-validation, hyperparameter tuning, and threshold optimization to improve model performance.
- Compared model metrics (Accuracy, Precision, Recall, AUC-ROC) to guide marketing strategy recommendations.

## 📚 Dataset
- **Source:** Telecommunications company’s marketing campaign dataset (provided via course materials).
- **Target variable:** `Subscribed` (binary outcome: Yes/No).
- **Features include:** Call duration, previous contact attempts, education level, communication method, consumer confidence index, etc.

## 🛠️ Methods
- **Data Preprocessing:**
  - Handled missing values and data errors.
  - Encoded categorical variables (e.g., job type, contact method).
  - Engineered new features to enhance model performance.
- **Model Training:**
  - Trained Logistic Regression with L2 Regularization for interpretable feature importance.
  - Trained Random Forest Classifier for capturing non-linear relationships and complex feature interactions.
- **Model Evaluation:**
  - Used stratified train-test split to maintain class balance.
  - Evaluated models using AUC-ROC, Precision, Recall, and F1-Score.
  - Applied custom threshold tuning to balance recall and precision for marketing needs.

## 🔥 Key Results
- **Random Forest** achieved higher AUC-ROC (0.937) and accuracy (88%) compared to Logistic Regression (AUC-ROC 0.913, accuracy 82%).
- **Call Duration** was the strongest predictor of subscription likelihood across both models.
- Custom thresholds allowed flexible targeting based on whether broad or selective outreach was preferred.

## 📈 Business Insights
- **Longer and meaningful customer calls** greatly increased subscription rates.
- **Repeated contact attempts** increased customer engagement and likelihood of subscription.
- Random Forest is recommended for **targeted marketing campaigns** where minimizing false positives is important.
- Logistic Regression is effective for **broad marketing outreach** strategies when casting a wider net.

## 📌 Technologies Used
- Python
- Libraries: Pandas, Scikit-learn, Matplotlib
- Jupyter Notebook
- Cross-validation and Hyperparameter Tuning

## 🚀 Future Improvements
- Integrate external features like customer satisfaction metrics or competitor activity.
- Apply ensemble methods beyond Random Forest (e.g., XGBoost, LightGBM) for potential performance gains.
- Expand dataset across industries to enhance generalizability.
- Explore deep learning models if dataset scale increases.

## 📜 Acknowledgements
This project was completed as part of coursework for the **Master of Data Science and Innovation** program at the **University of Technology Sydney (UTS)**.  
All code, modeling, and analysis were conducted and written by **Kunal Gurung**.
