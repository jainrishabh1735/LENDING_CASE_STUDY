# Project Name
> The project is a case study of lending club here we are provided with dataset which contains 39717 rows and 111 columns and we need to derive the key factors which will help the approval to decide whether to approve a loan or not using the EDA techniques .There were 3 type of loan status current ,charged off and fully paid .For the scope of this project we will consider only charged off and fully paid loans

## Table of Contents
* [General Info]-We have done lot of analysis both descriptive as well as graphical to decide on which columns to keep and which to drop and also done in depth using the domain knowledge acquired by reading various articles onle
* [Technologies Used]-we have used numpy library to do the scientific numerical calculation ,pandas for dataframe manipulation ,matplotlib and 
seaborn for visualizationand used univariate ,bivariate and multivariate analysis to get to the conclusion 
* [Conclusions]-We find the important driving which the approver should keep in mind before approving the loan
* [Acknowledgements]--Would like to thanks Upgrad and IIIT-B team for providing all the required support and help


## General Information
- We are provided with a dataset which contains the information of the loans provided in the lending club .The data contains three types of loans ,one which is completely paid off ,other is defaulted i.e the borrower has stopped paying the loan such types of loans are also called bad loans and this types of loans account for major credit loss in BFSI and the third type of loan is current loan these type of loans are currently on going and we are not certain whether this loan  will transform into good loans or bad loans in future .So for the scope of this case study we will consider only the completely paid off and defaulted loans .Using the data we have to identify the key driving factors which are responsible for loan  default 

- The background of the project is in lending club the borrower need money and lender gives money and there is a approval who act as a intermediater between these 2 so we have to act as approver and give some insights to lender whether he should lend money or not to the borrower 
- we are trying to find out the driving factors which decides whether a loan is going to be paid sucessfully or whether the borrower will default on it
- The dataset was a csv file of 34.8 MB containing 39717 rows and 111 columns 


## Conclusions
- when the loan amount is high there is high chances of default(Loan charged off)
- when the interest rate is high there is high chances of default(Loan charged off)
- The deafult chance are high when the installments are high or very high
- low income are moderate income group are more prone to default
- high and very high dti group have high chance of default 
- high and very high revol_util_groups have high chance of default 
- longer loans are more chance to default
- grade G has highest chance of default followed by F,E,D
- subgrades of G has highest chance of default followed by F,E,D
- small business ,educational and renenwal has high chances of default
- state with NV ,NE and FL has high chances of default
- when the loan amount is high and purpose is credit card and small business then there is high chance of default
-  when the loan amount is greater than 15000 and home_ownership is mortgage then there is more chance of default
-  when the loan amount is less than 15000 and subgrade is G then there is more chances of default
-  when the loan amount is greater than 20000 and verification_status is verified then there is more chances of default
-  when the loan amount is greater than 15000 and and annual_inc_groups is moderate annual income then there is high chance of default
-  with higher rate of interest irrespective of verification_status there is chance of default
-  if the int rate is higher then there is a chance of default when the grade is G ,F,E

## Technologies Used
- python - version 3.6.8
- pandas - version 0.25.3
- numpy - version 1.19.2
- seaborn - version 0.11.2
- numpy - version 1.19.2

## Acknowledgements

- This project was inspired by fraud happening in BFSI and to stop them
- Online articles ,geeks for geeks ,medium articles 



## Contact
Created by [@jainrishabh1735] - feel free to contact me!



