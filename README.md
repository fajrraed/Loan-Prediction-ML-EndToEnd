# Loan Approval Prediction System

## Project Overview
The goal of this project is to automate the loan eligibility process based on customer details provided in an online application form. These details include Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others.

##  The Machine Learning Pipeline
This project follows a complete End-to-End Machine Learning workflow:

1. **Data Collection**: Utilizing the classic Loan Prediction Dataset.
2. **Data Cleaning**: 
    - Implemented **Mean Imputation** for numerical missing values (LoanAmount).
    - Implemented **Mode Imputation** for categorical missing values (Credit_History, Gender, etc.).
    - Handled special cases like converting '3+' in Dependents to numerical '3'.
3. **Feature Engineering**: 
    - Used **Label Encoding** to convert text data into machine-readable numerical format.
4. **Model Building**: 
    - Built a baseline model using **Logistic Regression**.
    - Developed a more robust model using **Random Forest Classifier**.
5. **Prediction**: Generated final loan status predictions (Yes/No) for 360+ test cases.



##  Technologies Used
- **Python** (Core Language)
- **Pandas** (Data Manipulation)
- **Scikit-Learn** (Machine Learning Library)
- **Matplotlib / Seaborn** (Data Visualization)
- **Jupyter Notebook** (Development Environment)

## Key Insights
- **Credit History** is the most significant factor in determining loan approval.
- High Applicant Income does not always guarantee loan approval if the Credit History is poor.

##  Project Structure
- `notebooks/`: Contains the Jupyter Notebook with the full code.
- `data/`: Contains the `test.csv` file used for predictions.
- `README.md`: Project documentation.
