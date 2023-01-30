### Objective: 

Develop a simple neural network model using Keras library and predict the likelihood of customer accepting the loan that was offered to them by the bank.

### Data:
The dataset UniversalBank.csv below contains data on 5000 customers. The data include customer demographic information (age, income, etc.), 
the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (PersonalLoan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

It is available via the link https://www.kaggle.com/datasets/lowecoryr/universalbank

Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

It has the following fields:

Age: Customer’s age in completed years
Experience: Number of years of professional experience
Income: Annual income of the customer ($)
Family: Size Family size of the customer
CCAvg: Average spending on credit cards per month ($)
Education Education Level: 1: Undergrad; 2: Graduate; 3: Advanced/Professional
Mortgage: Value of house mortgage if any ($)
Securities Account: Coded as 1 if customer has securities account with bank
CD Account: Coded as 1 if customer has certificate of deposit (CD) account with bank
Online Banking: Coded as 1 if customer uses Internet banking facilities
Credit Card: Coded as 1 if customer uses credit card issued by Universal Bank
Personal Loan: 1 if the customer accepted the loan offered else 0 (target variable)
