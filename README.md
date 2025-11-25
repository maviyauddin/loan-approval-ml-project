📌 Loan Approval Prediction — Machine Learning Project

This project predicts whether a loan application will be approved using applicant details like income, credit history, employment, and loan amount. Two machine learning models were trained and compared to determine the best performer.

📁 Dataset

Source: Loan Prediction Dataset

File: train.csv

Rows: 614

Target variable: Loan_Status (Y/N → encoded to 1/0)

🧹 1. Data Preprocessing

Handled missing values using mode (categorical) and median (numerical)

Label-encoded categorical features

Split data into training and testing sets (80/20)

🤖 2. Models Trained
✔ Logistic Regression

Accuracy: ~82.7%

Balanced performance across approved and not-approved classes

✔ Random Forest Classifier

Accuracy: ~79.5%

High recall for approved loans but weaker on non-approved cases

📊 3. Model Comparison

Logistic Regression outperformed Random Forest for this dataset, showing that a simpler linear model can effectively capture loan approval patterns.

🧠 4. Key Insights

Loan approval strongly depends on Credit History, Applicant Income, and Loan Amount

Some applicant categories show higher approval rate patterns

Logistic Regression provides a reliable baseline model

📌 5. Conclusion

This project demonstrates how machine learning can support loan decision-making. Logistic Regression was selected as the final model due to its accuracy and stable performance.

🛠 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn
