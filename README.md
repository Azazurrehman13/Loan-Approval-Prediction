✅ Task 4: Loan Approval Prediction – Elevvo Pathways Internship
This repository showcases my work on the Loan Approval Prediction task, part of the Elevvo Pathways Internship Program. The objective is to predict whether a loan application will be approved or rejected based on customer financial history and credit-related features.

📄 Project Description
Dataset Used: Loan Approval Prediction Dataset (https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)

Goal: Build a classification model that accurately predicts loan approval status

Focus: Deal with imbalanced data, evaluate using precision, recall, and F1-score

📊 Dataset Features
Feature Name	Description
no_of_dependents	Number of dependents
education	Applicant education level
self_employed	Self-employed status
income_annum	Annual income
loan_amount	Requested loan amount
loan_term	Duration of the loan
cibil_score	CIBIL credit score
residential_assets_value	Value of residential assets
commercial_assets_value	Value of commercial assets
luxury_assets_value	Value of luxury assets (cars, etc.)
bank_asset_value	Bank balance and assets
loan_status	Target label – Approved or Rejected

🔧 Tools & Libraries
Python 🐍

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

⚙️ ML Workflow
✅ Preprocessing:

Handled missing values

Encoded categorical features

Applied SMOTE for class balancing

✅ Modeling:

Trained and evaluated Logistic Regression and Decision Tree classifiers

Compared models using classification metrics

📈 Model Results
🔹 Logistic Regression
yaml
Copy
Edit
Accuracy       : 93%
Precision      : Approved - 0.95, Rejected - 0.91
Recall         : Approved - 0.94, Rejected - 0.91
F1-Score       : Approved - 0.95, Rejected - 0.91
🔹 Decision Tree Classifier
yaml
Copy
Edit
Accuracy       : 98%
Precision      : Approved - 0.98, Rejected - 0.97
Recall         : Approved - 0.98, Rejected - 0.97
F1-Score       : Approved - 0.98, Rejected - 0.97
📌 Decision Tree outperformed Logistic Regression with near-perfect classification accuracy.

📂 Output
All classification reports and visualizations (ROC curves, confusion matrices) are saved in the outputs/ folder for detailed inspection.

🧠 Concepts Applied
Binary Classification

Handling Imbalanced Datasets

Feature Encoding

SMOTE Oversampling

Model Evaluation (Precision, Recall, F1-score)

🔚 Conclusion
This task provided practical experience in:

Preprocessing real-world finance data

Balancing class distributions

Comparing baseline and tree-based models

✅ Achieved 98% accuracy using a Decision Tree with well-prepared data.

