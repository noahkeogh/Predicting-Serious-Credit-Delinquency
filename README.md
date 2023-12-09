<h1 align="center":> Predicting Serious Credit Delinquency </h1>

## Table of Contents 
1. [➤ About The Project](#About-the-Project)
2. [➤ Dataset](#Dataset) 


## About the Project 
This project investigates different machine learning models for 
the use of predicting credit delinquency of an individual financial metrics. A Credit score  
is a score that is assigned to a borrower based upon many factors including their credit 
utilization ratio, their on-time payment history, and the number of delinquent 
loans they have had. The purpose of a credit score is to give lenders an idea of how 
risky a particular borrower may be to loan to. A higher score indicates that a borrower 
is less risky to loan money to and a lower score indicates that a borrower is 
much risky to loan money to. Models predicting how likely a given borrower 
is to experience credit delinquency in the near future has clear applications and 
uses for credit scoring models. If someone is predicted to be more likely to experience 
serious delinquency then they should receive a lower credit score as compared to someone 
that is less likely to experience serious delinquency. 

The goal of this project, therefore, is to develop a model capable of accurately predicting 
whether a given borrower is likely to experience serious delinquency in the near future. 

## Dataset 
The dataset used for this project is publicly-available from 
[Kaggle](https://www.kaggle.com/competitions/GiveMeSomeCredit/overview)
. The dataset contains a total of 150,000 entries representing 150,000 distinct borrowers. 
There are 11 features in the dataset that represent financial metrics of each borrower. The 
11 features are: 

1. <b>SeriousDlin2yrs</b>: Indicates whether a person has experienced 90 days past due delinquency or worse. This is a boolean parameter which is represented as 1 or 0 in the dataset. 1 being that the person has experienced serious delinquency or 0 meaning the person has not experienced serious delinquency.
2. <b>RevolvingUlizationOfUnsecuredLines</b>: Represents the total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits. This value is represented as a percentage and, therefore, ranges from 0 to 1.
3. <b>Age</b>: Age of the borrower in years. This is represented as an integer.
4. <b>NumberOfTime30-59DaysPastDueNotWorse</b>: Number of times that the borrower has been 30-59 days past due but no worse in the last 2 years. This is represented as an integer.
5. <b>DebtRatio</b>: Monthly debt payments, alimony, living costs divided by monthly gross income. This is represented as a percentage and, therefore, ranges from 0 to 1.
6. <b>MonthlyIncome</b>: This is the monthly income of the person. It is represented as a float in units of USD.
7. <b>NumberOfOpenCreditLinesAndLoans</b>: Number of open loans (installment like car lons or mortgages) and lines of credit (e.g. credit cards). This is represented as an integer.
8. <b>NumberOfTimes90DaysLate</b>: Number of times that the borrower has been 90 days or more past due. This is represented as an integer.
9. <b>NumberRealEstateLoansOrLines</b>: Number of mortgage and real estate loans including home equity lines of credit. This is represented as an integer value.
10. <b>NumberOfTime60-89DaysPastDueNotWorse</b>: Number of times borrower has been 60-89 days past due but no worse in the last 2 years. This is represented as an integer value.
11. <b>NumberOfDependents</b>: Number of dependents in family excluding themselves (spouse, children, etc.). This is represented as an integer value.
