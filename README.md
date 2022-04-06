# Lending Club Case Study
> You work for a consumer finance company which specialises in lending various types of loans to urban customers. 
>When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
>Two types of risks are associated with the bank’s decision:
>	If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
>	If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial 
>	loss for the company
>The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. 
>The aim is to identify patterns which indicate if a person is likely to default, 
>which may be used for taking actions such as denying the loan, reducing the amount of loan, 
>lending (to risky applicants) at a higher interest rate, etc..


## Table of Contents
* [Purpose of Case Study:Here we used EDA to understand how consumer attributes and loan attributes influence the tendency of default](#general-information)
* [Technologies Used:Python jupyter notebook](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business Objectives:
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. ?
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.?
- Loan Data Set is used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion: 
Annual income with DTI (Debt-to-income ratio) is negatively correlated, however the correlation between them is weak. 
Loan amount-funded amount, loan amount-funded amount investor and funded amount-funded amount investor have positive correlation.
Annual income and Loan amount are positively correlated. Number of charged off count is high for the purpose of debt consolidation
and paying credit card bill. Count of loan application is increasing year to year, increase in number of loan applications are causing
to more Number of charged off applications. Notice that with increase in annual income charged off proportion got decreased. 
Interest rate is increasing with increase in loan amount. Interest rate is increasing with increase in loan amount.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python libraries:
pandas
numpy
matplotlib.pyplot
seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This Project is intiated by Upgrade as part of Case Study,This was done by myself and Sabyasachi,Its good learning experience to me
while doing project we learned important many things which are going to useful in real time working life.Thanks to Upgrade team for
encouraging to do this case study.


## Contact
Created by [@Sreddy-51773947] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
