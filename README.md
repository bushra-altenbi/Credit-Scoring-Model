# Credit scoring model using classification algorithm
===================================================

📌 Project Description
----------------------
This project uses Logistic Regression, a classification algorithm, to build a credit scoring model that predicts whether a customer will experience financial delinquency within two years.
The model is trained and evaluated on real-world financial data.

💡 Features
----------------------
⚙️ Logistic Regression Implementation:
A clean and focused implementation using logistic regression for binary classification (default vs. no default).
🧠 Well-Structured Code:
Clean, step-by-step structure with clear section comments.
Easy to modify or extend with other models if needed.
📈 Feature Importance Analysis:
Highlights top contributing features based on absolute logistic regression coefficients for better interpretability.
📊 Model Evaluation:
Uses classification_report, confusion_matrix, and ROC AUC Score to assess model accuracy.
Includes ROC curve plotting for visual evaluation of classifier performance.

📦 Requirements
----------------------
You need Python 3.7+ and the following Python packages:
pip install pandas numpy matplotlib seaborn scikit-learn joblib


📂 Dataset
----------------------
 The model uses the publicly available Give Me Some Credit dataset from Kaggle, which contains financial and demographic information of individuals to predict the likelihood of serious delinquency within two years (target variable: SeriousDlqin2yrs).

https://www.kaggle.com/datasets/thanhnhannguyenly/cs-training?select=cs-training.csv

⚠️ Note: The dataset is not included in this repository due to GitHub file size limitations. Please download it manually and place the cs-training.csv file in your working directory.

⚠️ Ensure that the file is saved with the name cs-training.csv and placed in the same directory as the script to avoid file path errors.

📌 Conclusion
----------------------
This logistic regression-based model provides a strong baseline for credit scoring. It can be further improved by experimenting with other classification algorithms or advanced feature engineering techniques.
