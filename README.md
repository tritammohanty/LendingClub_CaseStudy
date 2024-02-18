# Lending Club Case Study
> This case study revolves around a consumer finance company specializing in lending various types of loans to urban customers. The case study is expected to perform Exploratory Data Analysis and find out the driving factors for lending which loan can lead to a 'Default' or 'Charged Off'.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Lending Club is an urban company that is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. If they can identify the risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.
- When the company receives a loan application, the company has to decide on loan approval based on the applicant’s profile.
- The aim is to identify patterns that indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- The data used is Lending Club, Loan Data. The data given contains information about past loan applicants and whether they ‘defaulted’ or not. 

## Reccomendations
- Verify applicants before providing loans
- Consider revisiting or improving the verification process as verified applicants also default more
- Recommend applicants from Grades A and B. Applicants from Grade C and above have higher default rates
- More caution and verification is recommended for funding higher amounts with a tenure of 60 months as they tend to default more
- Recommend  more controls while funding applicants with multiple open accounts as they default more
- Recommend lower interest rates with thorough evaluation of other factors like annual income etc. before choosing higher interest rates
- Recommend caution while funding small businesses in general and specially in income range below 50K
- Loans borrowed for education and renewable energy also default more. More verification/controls to be exercised in these categories
- Loans funded with amounts 12K and above default more in all income groups specially in 6-10Y+.  A better verification process needs to be exercised here
- Recommend Not to fund applicants with Inquiries in last 6 months
- Recommend Not to consider applicants with public records and public record bankruptcies
- Recommend more verification for applicants coming from  Nebraska, Nevada Idaho, California and Florida

## Technologies Used
- python     - version 3.11.5
- pandas     - version 2.0.3
- numpy      - version 1.24.3
- seaborn    - version 0.12.2
- matplotlib - version 3.7.2

## Acknowledgements
- This project was part of Upgrad's Exploratory Data Analysis Project.
- References if any...
  - [Seaborn Documentation](https://seaborn.pydata.org/api.html)
  - [Matplotlib Documentation](https://matplotlib.org/stable/api/index.html)
  - [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)

## Contact
Created by [@tritammohanty] - feel free to contact me!