💰 Loan Status Prediction using Logistic Regression


📌 Project Overview

This project develops a machine learning model using Logistic Regression to predict loan approval status for applicants.

The dataset contains historical loan applications with features such as income, employment type, number of dependents, credit score, and asset values.

The primary objective is to provide a data-driven decision support tool for banks and financial institutions to assess loan risk efficiently.



⚙️ Workflow

1. Data Loading & Exploration





Dataset (loan.csv) loaded using Pandas.



Checked for missing values and cleaned column names for consistency.

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



Applied Label Encoding for the target variable (loan_status).



Applied One-Hot Encoding for categorical features (education, self_employed).

3. Preprocessing





Dropped rows with missing values to ensure data quality.



Ensured train and test sets have matching columns after encoding.

4. Train-Test Split





Data split into 80% training and 20% testing using train_test_split.

5. Model Training





Implemented Logistic Regression (max_iter=1000) for binary classification.



Trained on the encoded feature set.

6. Evaluation & Visualization





Evaluated model performance using accuracy score on test data.



Visualized results using a Confusion Matrix to show true positives, true negatives, false positives, and false negatives.



📊 Results

✅ Accuracy on Test Data: 83.1%
✅ Confusion Matrix highlights the distribution of true positives, true negatives, false positives, and false negatives.
✅ Strong predictive capability achieved with logistic regression and selected features.



🛠️ Tools & Technologies





Programming Language: Python



Libraries: Pandas, NumPy, Matplotlib, Scikit-Learn



Environment: Jupyter Notebook / Google Colab



🌍 Real-World Applications





Banks & Financial Institutions → Automate risk assessment and loan approval processes.



Loan Officers → Reduce manual evaluation time and improve decision consistency.



Data Analysts → Identify key features influencing loan approval.



Customers → Understand factors that improve loan approval chances.



⚖️ Limitations & Future Work

Although the model achieves solid accuracy, some limitations exist:





Dataset Size & Quality: Limited dataset size or quality may reduce generalizability.



Feature Limitations: Excludes some financial or behavioral factors (e.g., applicant history, co-applicants).



Model Choice: Logistic Regression is interpretable but may be outperformed by more complex models.

🔮 Planned Improvements:





Incorporate additional features (e.g., applicant history, co-applicants, collateral).



Perform hyperparameter tuning with GridSearchCV.



Explore advanced models like Random Forest or XGBoost for better performance.



Deploy as an interactive web application (e.g., Streamlit/Django) for real-time loan predictions.



📂 Dataset





File: loan.csv



Size: Not specified



Columns: loan_id, no_of_dependents, education, self_employed, income_annum, loan_amount, loan_term, cibil_score, residential_assets_value, commercial_assets_value, luxury_assets_value, bank_asset_value, loan_status



🧑‍💻 Author

Daud Ibrahim Hassan
📌 Data Analyst & Computer Science Student (BRAC University)
🔗 LinkedIn | GitHub
