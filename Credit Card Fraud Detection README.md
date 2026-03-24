This project focuses on detecting fraudulent credit card transactions using machine learning models. The goal is to build a system that can identify fraud cases accurately despite the dataset being highly imbalanced.
Credit card fraud is a major issue in the financial industry. In this project, we use different machine learning algorithms to classify transactions as fraudulent (1) or legitimate (0).
We compare multiple models and evaluate them using metrics like Confusion Matrix and ROC-AUC Score.

Dataset used: creditcard.csv
Target column:
Class = 0 → Legitimate transaction
Class = 1 → Fraud transaction
The dataset is highly imbalanced, meaning fraud cases are very rare compared to normal transactions.

Technologies Used: Python,NumPy, Pandas, atplotlib, Seaborn, Scikit-learn
Machine Learning Models Used: Logistic Regression, Decision Tree Classifier, Random Forest Classifier
Each model is trained and evaluated to compare performance.

Workflow:- 
Load the dataset
Split data into features and target
Train-test split (80% training, 20% testing)
Feature scaling using StandardScaler
Train models
Evaluate using: Confusion Matrix, ROC Curve,AUC Score
Visualize results

Future Improvements: Use SMOTE for better imbalance handling, Hyperparameter tuning,Add more advanced models like XGBoost, Deploy as a web app.
