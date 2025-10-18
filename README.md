# 🏦 Loan Approval Prediction using Machine Learning

### Overview
This project predicts whether a loan will be **approved** or **rejected** based on applicant information. It uses a Random Forest Classifier trained on Kaggle’s Loan Prediction dataset.

### Algorithms Used
- Random Forest Classifier  
- Label Encoding  
- Train-Test Split  

### Features
| Feature | Description |
|----------|--------------|
| Gender | Male/Female |
| Married | Applicant’s marital status |
| Education | Graduate/Not Graduate |
| Self_Employed | Employment type |
| ApplicantIncome | Applicant income |
| LoanAmount | Requested loan amount |
| Credit_History | Credit record (1 = good, 0 = bad) |

### Results
Achieved **accuracy ~80–85%** depending on preprocessing and model tuning.

### Dependencies
bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
