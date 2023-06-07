# Lending Club Case Study
> This study will help in analyzing how real business problems are solved using Exploratory Data Analysis(EDA). It will also help in understanding risk analytics in banking and financial services and understanding how data is used to minimize the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Project Information
- We are working for a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
   - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
   - If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the company
 
### Project Background
- Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
### Business Problem
- Since lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss).In this case, the customers labelled as 'charged-off' are the 'defaulters'. The company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
### Dataset
- Dataset is a .csv file containing the Loan data

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1.The charged off loans have higher interest rate across all loan amount groups. So if the interest rate is high there are more chances of loan getting default.

2.The Loan defaulting is increasing from A to G grade.

3.As the loan amount and employment length is increasing the risk of defaulting is also increasing.

4.Applicants whose loan amount is high are likely to default.

5.Applicants taken loan for small business and the loan amount is between 12k to 14.5k, then the applicants are more likey to default.

6.We can observe that loan amount is higher for applicants who defaulted and with annual income between 186k to 233k.

7.Applicants most likely to default in the months between oct to dec mostly december, applicants defaulted mostly in the year 2011

8.As the installment is increasing the chances of loan defaulting is also increasing.

9.Applicants with 60 months loan term are likely to default compared to 36 months term.

10.When applicants are verified and loan amount is greater than 15k then loan is likely to default.

11.If the annual income is high across all interest rate groups then there less chances of loan getting default.

12.Applicants with highest salary applied loans for home improvement and also they are once likely to default.

13.If the applicants have high annual income and their home ownership is any then they are not likely to default.

#### Driving factors:
1. Interest rate
2. Loan Amount
3. Installment
4. Grade
5.Term
6. Annual Income
7. Purpose
8. Sub Grade

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - 3.8.10
- Numpy - version 1.24.3
- Pandas - version 2.0.1
- Seaborn - version 0.12.2
- MatplotLib - version 3.7.1
- Plotly - 5.14.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by Upgrad Programme for ML and AI.


## Contact
Created by [@kumargauravb and @yogeshwararanjith] - feel free to contact us!


<!-- Optional -->
## License
- This project is open source and available in GitHub.

<!-- You don't have to include all sections - just the one's relevant to your project -->
