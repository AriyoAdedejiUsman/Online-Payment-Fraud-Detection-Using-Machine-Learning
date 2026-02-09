💳 Financial Transaction Fraud Detection Using Machine Learning

This project develops a machine learning–based fraud detection system designed to identify high-risk financial transactions using behavioral and balance-based transaction data. The goal is to improve fraud detection sensitivity while minimizing false positives in real-world financial operations.

📊 Dataset

The dataset contains transactional and behavioral features including:

step – Time index of transaction

type – Transaction category (CASH_OUT, PAYMENT, TRANSFER)

amount – Transaction value

oldbalanceOrg, newbalanceOrg – Sender balances

oldbalanceDest, newbalanceDest – Receiver balances

isFraud – Fraud label

isFlaggedFraud – System fraud flag indicator

⚙️ Methodology
Data Preprocessing

Handled missing values and inconsistent records

Encoded categorical transaction types

Performed exploratory data analysis to understand fraud patterns

Feature Engineering

Balance change ratios

Transaction behavior indicators

Derived risk-based transaction features

Modeling

Built supervised classification models

Compared multiple algorithms (e.g., Random Forest, Logistic Regression)

Addressed class imbalance using weighted learning / resampling strategies

Evaluation Metrics

Fraud detection performance evaluated using:

Precision

Recall

F1-score

ROC-AUC

Confusion Matrix

(Accuracy reported only as supplementary metric)

📈 Results

Achieved strong fraud detection performance with high recall on fraudulent transactions

Reduced false negatives, improving early fraud identification capability

Built an end-to-end ML pipeline ready for production integration

🛠️ Tools & Technologies

Python

Pandas

Scikit-learn

Matplotlib

Seaborn

🚀 Future Improvements

ROC curve visualization

Threshold optimization

Model explainability (SHAP / Feature Importance)

API deployment for real-time fraud scoring
