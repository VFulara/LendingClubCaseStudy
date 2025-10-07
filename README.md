# Lending Club Case Study: Analyzing Loan Defaults

> This project analyzes loan default risk for a consumer finance company using exploratory data analysis (EDA). By examining historical loan data, the project identifies key factors and patterns that contribute to loan defaults, helping the company make informed lending decisions and minimize financial losses.

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

1. Interest rate, revolving utilization, term, grade, home_ownership, purpose, address_state and earliest_cr_line seem to have direct impactful relationship with high ‘Charge offs’
 
2. Interest ranges between 15%-25% have highest loan default percentage (charge off/total loan records) 
    a. This suggests that applicants who are offered higher interest rates—likely due to higher perceived risk—are more likely to default on their loans.
    b. Loan amounts are also increasing in range 15-25 with highest loan amounts being in 22.5-25% interest rate category
    c. Recommendation would be to put a cap loan amounts at higher interest rate to limit the losses
    
3. Loan term significantly impacts default rates. Although 36-month loans are more common, 60-month loans have a much higher proportion of defaults—about 25% of 60-month loans default compared to only 10% of 36-month loans. This indicates that longer-term loans are riskier and more likely to result in charge-offs.

4. Credit grade is a strong indicator of loan default risk. Lower credit grades (such as F and G) have significantly higher default rates, with grade G experiencing defaults in over 30% of cases, compared to only 6% for grade

5. High Revolving utilization for a customer is also an indicator of risk
    a. If revolving utilization crosses 70-75 mark it is safer to reject loans

6. Loans with purpose of small_business(25%) and renewable energy(18%) has highest charge off rate

7. ‘earliest_cr_line ’ seems to have interesting pattern where people starting their credit relations in 2007 (20%), 2006(19%), 1973 (18%) has the most charge offs, it should be investigated what is common from new accounts policy perspective in these years

8. Older credit relations are trusted with more loan amount earliest_cr_line  with 1973 had an average loan amount of ~13000 whereas for 2006-07 average loan amount is ~7000-7500.
    
    
 


## Technologies Used
- Python libraries
- pandas
- numpy 
- matplotlib
- seaborn


## Acknowledgements
- This project was inspired by the Lending Club loan default risk analytics case study from UpGrad and EDA best practices.
- References:
  - Lending Club Loan Dataset and Data Dictionary document.
  - Official pandas, numpy, matplotlib, and seaborn documentation

## Contact
Created by 
- Sharath Hosakote Sudhakrishna
- Vaibhav Fulara
- Banetta Nedunchezhiyan
- Karthik Reddy
- Tarun Garg
