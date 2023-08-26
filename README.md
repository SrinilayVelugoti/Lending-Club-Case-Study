# Lending Club Case Study
> The goal is to identify potential loan defaulters , to prevent losses to the lending firm .Insights on parameters(features) were obtained by doing comphrehensive exploratory data analysis .




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## General Information
- The project is about identifying potential loan defaulters through eda 
- The project starts with a dataset of a certain lending  firm through the years 2007 to 2011 .
- The dataset contains the borrowers annual income , the funded amount , installment , term of loan , interest rate , loan status , debt to income ratio , the state the borrower belongs to , the grade which specifies the risk involved in lending the loan , noof bankruptcies , the year and month the loan was issued
- The project contains a jupyter notebook , a pdf document explaining insights  

## Technologies Used
- pandas - version 1.5.3
- numpy - version 1.24.2
- matplotlib - version 3.7.1
- seaborn - version 0.12.2
- re - version 2.2.1



## Conclusions
- Default Rate (Charged Off) decreases as income increases
- Lower risk grade have lower default rate . Grade has the lowest risk rate followed by B and so on 
- Noof loans given out increased over time , the year with highest default rate is 2007 ,followed by 2008 and 2011 . All 3 years have a default rate higher than 15% (0.15)
- As the dti ration increases so does the default rate . That is to say borrowers with loans that surpass their income tend to default more often 
- The states NV,SD,AK,FL have high default rates 
- Small Business, Other , Medical ,Debt Consolidation are the categories with high default rates








