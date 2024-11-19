# Lending-Club-Case-Study

## Table of Contents
* [Problem Statement](#problemstatement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## Problem Statement
### Introduction
Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

### Business Understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

    - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

    - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

    - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

### Results Expected

1. Write all your code in one well-commented Python file; briefly mention the insights and observations from the analysis 
    - Present the overall approach of the analysis in a presentation: 
    - Mention the problem statement and the analysis approach briefly 
    - Explain the results of univariate, bivariate analysis etc. in business terms
2. Include visualisations and summarise the most important results in the presentation


## Conclusions
Listing down some important facts, you will find more insights in presentation and .ipynb file.
- The number of loan applicants has significantly increased each year from 2007 to 2011 in both "Fully Paid" and "Charged-Off" categories.
- The major purposes for loans are debt consolidation, credit card, other, home improvement, major purchase, and similar.
- People with rented or mortgaged homes are taking out more loans.
- Loan amounts range from 0 to 35,000, with the 25th percentile at 5,000, the 50th percentile around 10,000, and the 75th percentile at 15,000. Outliers are above 30,000.
- Charged-off (defaulted) loans have the highest interest rates, especially for 60-month tenures.
- The highest number of loan applications occurs in December each year.
- The higher the number of public bankruptcy records thus higher chances of defaulting the loan.
- California (CA) has the highest number of loan applications in both "Fully Paid" and "Charged-Off" categories.
- Risk analysis of defaulters:
    - Grade G has the highest default percentage.
    - Loans for small business purposes have high default rates.
    - Borrowers with over 10 years of employment have the highest default percentage.
    - Most interest rates for defaulters range around 20%.

## Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
