# Project Name
> Outline a brief description of your project.

This project analyzes loan default risk for a consumer finance company using exploratory data analysis (EDA). By examining historical loan data, the project identifies key factors and patterns that contribute to loan defaults, helping the company make informed lending decisions and minimize financial losses.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is a case study focused on risk analytics in banking and financial services, specifically analyzing loan default risk using exploratory data analysis (EDA).
- The background of the project involves a consumer finance company that provides various types of loans to urban customers. The company needs to make informed decisions on loan approvals to minimize financial losses due to defaults.
- The business problem addressed is identifying patterns and key factors that indicate whether a loan applicant is likely to default.
- The dataset used contains information about past loan applicants from 2007 to 2011, including whether they fully paid, are currently paying, or defaulted ('charged-off') on their loans. 


## Conclusions

- **Conclusion 1:**  
  Higher interest rates are strongly associated with increased loan defaults. The analysis shows that the majority of defaults occur in loans with interest rates between 15% and 25%, with the highest default rates observed in the 22.5-25% range. This suggests that applicants who are offered higher interest rates—likely due to higher perceived risk—are more likely to default on their loans.


- **Conclusion 2:**  
  Loan term significantly impacts default rates. Although 36-month loans are more common, 60-month loans have a much higher proportion of defaults—about 25% of 60-month loans default compared to only 10% of 36-month loans. This indicates that longer-term loans are riskier and more likely to result in charge-offs.

- **Conclusion 3:**  
  Credit grade is a strong indicator of loan default risk. Lower credit grades (such as F and G) have significantly higher default rates, with grade G experiencing defaults in over 30% of cases, compared to only 6% for grade

- **Conclusion 4:**  
  The purpose of the loan influences default rates. Loans taken for small business purposes have the highest default rate at around 25%, while other purposes such as credit card, home improvement, and car loans have lower default rates (typically 10–15%). This suggests that loans for small businesses are riskier for lenders compared to other loan purposes.


## Technologies Used
- Python libraries
     pandas
     numpy 
     matplotlib
     seaborn


## Acknowledgements
- This project was inspired by the Lending Club loan default risk analytics case study from UpGrad and EDA best practices.
- References:
  - Lending Club Loan Dataset
  - Official pandas, numpy, matplotlib, and seaborn documentation

## Contact
Created by [@githubusername] - feel free to contact me!