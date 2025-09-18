💰 Loan Status Prediction using Logistic Regression

📌 Project Overview

This project builds a machine learning model using Logistic Regression to predict loan approval status for applicants.

The dataset includes historical loan applications with features such as income, employment type, number of dependents, credit score, and asset values.

The goal is to provide a data-driven decision support tool for banks and financial institutions, helping them evaluate loan risk efficiently.

⚙️ Workflow
1. Data Loading & Exploration

Dataset loaded using Pandas.

Checked for missing values and cleaned column names.

2. Feature Engineering

Selected features:

no_of_dependents

education

self_employed

income_annum

loan_amount

loan_term

cibil_score

residential_assets_value

commercial_assets_value

luxury_assets_value

bank_asset_value

Applied Label Encoding for target variable (loan_status).

Applied One-Hot Encoding for categorical features.

3. Preprocessing

Dropped rows with missing values.

Ensured train and test sets have matching columns after encoding.

4. Train-Test Split

Data split into 80% training and 20% testing using train_test_split.

5. Model Training

Implemented Logistic Regression (max_iter=1000).

Trained on encoded feature set.

6. Evaluation & Visualization

Evaluated accuracy score on test data.

Visualized performance using Confusion Matrix:

📊 Results

✅ Accuracy on Test Data: 83.1%
✅ Confusion Matrix shows true positives, true negatives, false positives, and false negatives.
✅ Strong predictive capability using logistic regression and selected features.

🛠️ Tools & Technologies

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Scikit-Learn

Environment: Jupyter Notebook / Google Colab

🌍 Real-World Applications

Banks & Financial Institutions → Risk assessment and loan approval automation.

Loan Officers → Reduce manual evaluation time and improve decision consistency.

Data Analysts → Identify key features affecting loan approval.

Customers → Understand factors that improve loan approval chances.

⚖️ Limitations & Future Work

Dataset size & quality may limit generalizability.

Feature limitations: Some financial or behavioral factors are not included.

Model choice: Logistic Regression is interpretable, but advanced models (Random Forest, XGBoost) may improve accuracy.

🔮 Future Improvements:

Incorporate more features such as applicant history, co-applicants, and collateral.

Hyperparameter tuning with GridSearchCV.

Explore advanced models for better predictive performance.

Deploy as an interactive web application for loan prediction.

📂 Dataset

File: loan.csv
Size: 
Columns: loan_id, no_of_dependents, education, self_employed, income_annum, loan_amount, loan_term, cibil_score, residential_assets_value, commercial_assets_value, luxury_assets_value, bank_asset_value, loan_status

🧑‍💻 Author
Daud Ibrahim Hassan
📌 Data Analyst & Computer Science Student (BRAC University)
