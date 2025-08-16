# Loan Eligibility Prediction Model

## Project Overview
This project is a **Loan Eligibility Prediction Model** built using **Python** and machine learning techniques.  
It predicts whether an applicant is **eligible** or **not eligible** for a loan based on factors such as income, loan amount, credit history, and other demographic and financial details.  

The goal is to assist financial institutions in quickly assessing loan applications and making informed, data-driven decisions.

---

## Dataset
The dataset used for training and testing was obtained from **[Kaggle]**.

**Features include:**
- **ApplicantIncome** – Applicant's monthly income
- **CoapplicantIncome** – Co-applicant's monthly income
- **LoanAmount** – Amount of loan requested
- **Loan_Amount_Term** – Duration of the loan
- **Credit_History** – Credit repayment history (1 = good, 0 = bad)
- **Gender** – Applicant’s gender
- **Married** – Marital status
- **Dependents** – Number of dependents
- **Education** – Education level
- **Self_Employed** – Employment status
- **Property_Area** – Urban/Semiurban/Rural

**Target Variable:**
- **Loan_Status** – Eligible (`Y`) or Not Eligible (`N`)

---

## Technologies Used
- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning model building
- **Streamlit** – Web app deployment
- **Hugging Face Spaces** – Alternative deployment platform

---

## Model Development
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. **Model Training**
   - Tested multiple algorithms (e.g., Decision Tree, Logistic Regression, and Random Forest)
   - Selected the best-performing model based on accuracy, precision, recall, and F1-score

3. **Model Evaluation**
   - Confusion matrix
   - Classification report
   - Cross-validation

---

##  Deployment
The model is deployed on:
- **Streamlit**
- **Hugging Face Spaces**[Check out my Hugging Face Space](https://huggingface.co/spaces/ogunsolaoluwatosin/demo4)

