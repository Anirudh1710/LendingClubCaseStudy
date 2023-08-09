# Lending Club Case Study
> The current dataset belongs to a consumer finance company Lending Club which specializes in lending various types of loans to urban customers.
> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures.
> When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
> When a person applies for a loan, there are two types of decisions that could be taken by the company:
> 1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
>    - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
>    - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
>    - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
> 2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset).


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendations](#recommendations)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **About Company:**
>  Lending Club, a consumer finance company which specializes in lending various types of loans to urban customers.
  Lending Club is the largest online loan marketplace facilitating personal loans, business loans, and financing of medical
  procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
- **Business Understanding :**
>  When Lending Company receives a loan application, the company has to make a decision for loan approval based on the
applicant’s profile. Two types of risks are associated with the bank’s decision:
>   1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
>   2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.      
>  
>  Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.
- **Goals & Business Objectives :**
>  The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as
denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
  - **Goals:**
      >  1. Mitigate high risky lending.
      >  2. Reduce credit loss for company by identifying risky loan applicants.
  - **Objectives:**
      >    1. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.
      >    2. The objective of this EDA is to identify the risky loan applicants at the time of loan application.
      >    3. So that such loans can be reduced and thereby cutting down the amount of credit loss
      >    4. In other words, to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.
      >    5. The company can utilize this knowledge for its portfolio and risk assessment. And thus minimize the risk of losing money while lending to customers.
-  To perform Exploratory Data Analysis on Lending Club Case Study **loan.csv** dataset is used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
> **Conclusion 1 from the analysis**
  - A Higher Loan amount leads to a higher default rate. This is one significant factor leading to Default.
> **Conclusion 2 from the analysis**
  - Loans for a longer-term will have higher chances of defaulting. This is one significant factor leading to Default
> **Conclusion 3 from the analysis**
  - Loans with high-interest rates will have higher chances of defaulting. This is one significant factor leading to Default.
> **Conclusion 4 from the analysis**
  - A lower grade means that the applicant is more likely to default. This is one significant factor leading to Default.
> **Conclusion 5 from the analysis**
  - Home Ownership as "Others" is more likely to default. This is one significant factor leading to Default.
> **Conclusion 6 from the analysis**
  - Lower the income, more is the chances to default i.e. Applicant with Annual Income less than $40,000. This is one significant factor leading to Default.
> **Conclusion 7 from the analysis**
  - "Small businesses" as purpose are generally risky and are most likely to default. This is one significant factor leading to Default.
> **Conclusion 8 from the analysis**
  - Applicants belonging to State NV(Nevada), TN(Tenessee), and AK(Alaska) are most likely to default.
> **Conclusion 9 from the analysis**
  - Higher the DTI, the higher the chances to default.
> **Conclusion 10 from the analysis**
  - Higher the Revolving Balance Utilization, the higher the chances of Default. This is one significant factor leading to Default.
> **Conclusion 11 from the analysis**
  - Applicants who have already been bankrupt are in very poor financial conditions and are more likely to Default. This is one significant factor leading to Default.
> **Conclusion 12 from the analysis**
  - High-Interest Rate with Longer Loan Term is risky and is an important combination for determining the default rate.
> **Conclusion 13 from the analysis**
  - Low grades such as D, E, F, G with Bankruptcy is an important combination for determining default rate.
> **Conclusion 14 from the analysis**
  - Home Ownership type as "Other" and Low annual income is an important combination for determining defaultrate.
> **Conclusion 15 from the analysis**
  - Very High revolving balance utilization and "Small Business" as loan purpose is an important combination for determining default rate.
> **Conclusion 16 from the analysis**
  - Delinquency above and equal to 4 with bankruptcy is an important combination for determining the default rate. This is one significant combination leading to Default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Recommendations
-  If the applicant is having a low grade with a previous record of Bankruptcy then the loan should be disapproved.
-  If the requested Loan Amount is high with a longer loan repayment term then the applicant's background should be checked thoroughly before approving the loan.
-  If the Interest Rate on Loan Amount is high with a longer loan repayment term then the loan repayment term should be reduced.
-  Background verification of applicants with High Revolving Balance Utilization or a high number of delinquencies should be properly done before approving the loan.
-  When the purpose is "small business" then check the applicant thoroughly as they have a high tendency to default.
-  If the applicant has mentioned Home Ownership as "Others" and has a low annual income then the loan should be disapproved after a thorough check.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@https://github.com/Anirudh1710/] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
