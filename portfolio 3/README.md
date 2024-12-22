# 🏦 Loan Approval Prediction & Risk Assessment 📊

## Introduction: 📚

This repository contains an analysis of loan approval data. The main goal of this project is to develop and train classification models to predict whether a loan application will be approved or denied based on various personal and financial factors.

## Dataset Structure: 📋

The **Loan Approval** dataset contains 20,000 records with the following key features:

- **ApplicationDate** - 📅 Loan application date
- **Age** - 👤 Applicant’s age
- **AnnualIncome** - 💵 Yearly income
- **CreditScore** - 💳 Creditworthiness score
- **EmploymentStatus** - 🏢 Job status
- **EducationLevel** - 🎓 Highest level of education attained
- **Experience** - ⏳ Work experience
- **LoanAmount** - 💸 Requested loan amount
- **LoanDuration** - 📆 Loan repayment period
- **MaritalStatus** - 💍 Applicant’s marital status
- **NumberOfDependents** - 👶 Number of dependents
- **HomeOwnershipStatus** - 🏡 Homeownership type
- **MonthlyDebtPayments** - 💳 Monthly debt obligations
- **CreditCardUtilisationRate** - 📈 Credit card utilisation percentage

## Explorations: 🔍

### Data Preparation: 🧹
- The dataset was cleaned and pre-processed to ensure proper handling of missing values, categorical variables, and feature scaling.

### Predictive Modelling: 🤖
- **Classification Models**: Various models were trained to predict loan approval outcomes, including:
  - Logistic Regression
  - Decision Trees
  - Random Forest
- **Performance Metrics**: Models were evaluated using accuracy, precision, recall, and F1-scores to determine their effectiveness.

### Data Ethics: 🤔
- Ethical concerns related to privacy, bias, and the fairness of using personal financial data for loan decisions were thoroughly assessed.

## Descriptive Statistics: 📈
- **Total records**: 20,000
- **Features**: 15 demographic and financial features
- **Target Variable**: Loan approval outcome (Approved/Denied)

## Python Libraries Used: 🐍

- pandas 🐼
- numpy 🔢
- scikit-learn 🤖
- seaborn 🎨
- matplotlib 📊

## Findings: ✅
- The training accuracy is 96.58%, while the testing accuracy is 96.68%, indicating that the model generalises well to unseen data.
- The F1-scores for both the training and testing data are also very similar, with the testing F1-score at 0.931 and the training F1-score at 0.928.
- For the 1-NN (1-Nearest Neighbour) classifier, the F1-score on the training data shows perfect accuracy, suggesting it classifies all training samples correctly.
- The overfitting in the model is caused by the 1-NN classifier, which memorises the training data without any regularisation.
- The optimal number of neighbours in the KNN model is 17.
- The best performance is with the Euclidean (L2) distance metric, showing the highest accuracy (93.32%) and F1-score (0.8521) compared to other metrics.

This project develops predictive models to assess loan approval outcomes, providing insights into how personal and financial factors affect loan decisions. Additionally, the ethical implications of using sensitive data are examined, ensuring responsible data usage in financial risk modelling.
