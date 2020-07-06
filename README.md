# Artificial Neural Network in Banking
Example of usage of Artificial Neural Network in determining behaviour of bank client

## Business problem
There is significant churn in the bank with no obvious reasons. The goal is to analyse behaviour of bank customer previous year to predict which customer might leave the bank this year to prevent that. 

## Dataset
Data are stored in 'Churn_Modelling.csv' file. There are 10 independent variables:
 - CreditScore (int) \[0-1000\], 
 - Geography (String) \[name of country\], 
 - Gender (String) \[male or female\], 
 - Age (int) \[number of years\], 
 - Tenure (int) \[number of years\], 
 - Balance (big int) \[cash in euro\], 
 - NumOfProducts (int) \[quantity of bank products\], 
 - HasCrCard (bool) \[if the customer has credit card\], 
 - IsActiveMember (bool) \[if customer is actively using cc\], 
 - EstimatedSalary (big int) \[salary in euro\] <br><br>
 There is one dependent variable that present if the customer left the bank last year 'Exited' (bool) 
 
 ## Result
 To check output of script read 'artificial_neural_network.ipynb'