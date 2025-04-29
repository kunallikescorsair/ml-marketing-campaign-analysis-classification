📊 Marketing Campaign Analysis – Predictive Modeling
This project analyzes a telecommunications marketing campaign dataset to predict customer subscription likelihood and extract actionable business insights.
It was developed as part of the Statistical Thinking for Data Science (36103) course at the University of Technology Sydney (UTS).

📄 Project Overview
Built and evaluated Logistic Regression (parametric) and Random Forest (non-parametric) models.

Identified key customer attributes (e.g., call duration, contact method) influencing subscription likelihood.

Applied cross-validation, hyperparameter tuning, and threshold optimization to improve model performance.

Compared model metrics (Accuracy, Precision, Recall, AUC-ROC) for marketing campaign strategy recommendations.

📚 Dataset
Source: Telecommunications company’s marketing campaign.

Target variable: Subscribed (binary outcome: Yes/No).

Features include: Call duration, previous contacts, education level, contact method, and other demographic factors.

🛠️ Methods
Data Preprocessing: Handled missing values, feature encoding, and feature engineering.

Model Training:

Logistic Regression with L2 Regularization.

Random Forest Classifier with hyperparameter tuning.

Model Evaluation:

Stratified train-test split.

AUC-ROC, Precision, Recall, F1-Score comparisons.

Threshold tuning to balance recall and precision.

🔥 Key Results
Random Forest achieved higher AUC-ROC (0.937) and accuracy (88%) compared to Logistic Regression.

Call Duration was the most influential predictor of subscription likelihood across both models.

Custom thresholds optimized model performance for different marketing strategies (broad vs targeted).

📈 Insights
Longer and meaningful customer calls greatly increase subscription rates.

Repeated contact attempts improve engagement and conversion.

Random Forest is recommended for targeted marketing campaigns; Logistic Regression is suitable for broad customer outreach.

📌 Technologies Used
Python (Pandas, Scikit-learn, Matplotlib)

Jupyter Notebook

Cross-validation and Grid Search

🚀 Future Improvements
Incorporate external features (e.g., customer satisfaction scores).

Explore ensemble learning or deep learning models for enhanced prediction accuracy.

Apply techniques to larger multi-industry datasets for generalization.

📜 Acknowledgements
This project was developed as part of coursework for the Master of Data Science and Innovation program at UTS.
All code and analysis presented are original work by Kunal Gurung.
