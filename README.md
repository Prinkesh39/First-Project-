# First-Project-


Installations and Library used:

This project needs python and it's libraries mainly Pandas, Numpy, Matplotlib, Seaborn and Scikit Learn which can be installed using terminal command pip install <library name> 

Project Motivation:

Being a finance personal working with a Bank, we face many challanges to not only add more customer for our credit business but also to ensure that our rate of defaults remain low. This project can help in indentify the correct demography which a company can target to grow their business. This is a data based approach towards predicting the default in repayment. This is a simple model but still shows a promising result. More features can be added in the data as well as better modern algorithims like Deep Learning may also be employed to achieve even more accuracy.

File Descriptions:

For this purpose we will use the data from KAGGLE Website.

This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

There are 25 variables:

ID: ID of each client
LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit
SEX: Gender (1=male, 2=female)
EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)
MARRIAGE: Marital status (1=married, 2=single, 3=others)
AGE: Age in years
PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, … 8=payment delay for eight months, 9=payment delay for nine months and above)
PAY_2: Repayment status in August, 2005 (scale same as above)
PAY_3: Repayment status in July, 2005 (scale same as above)
PAY_4: Repayment status in June, 2005 (scale same as above)
PAY_5: Repayment status in May, 2005 (scale same as above)
PAY_6: Repayment status in April, 2005 (scale same as above)
BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)
PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)
default.payment.next.month: Default payment (1=yes, 0=no)

How to Interact with the project:

Jupyter notebook/COLAB can be used to download the python file and used for training the dataset. 

Files in the repository:

1). README.md
2). Dataset of Taiwan Credit Card defaults 
3). .py file consists of the actual analysis and model to predict the probability of default

Technical Details:

Logistic Regression and Random Forrest ensemble method is used for our model. Grid Search technique employed in both of our model.

Summary:
With this model we will mainly look into 3 important questions:

1) How a customer's demography mainly Gender, Education and Marital Status effects the probability of default in repayment ?

Inference: There is no definite relationship between the customer's Gender or Edcation level with the probability of their default

2)Is there any relation between customer's age and the repayment habit of the customer?

Inference: We can see that young customer's in their 20s and 30s are more prone to defaults.

3)How accurately we can predict the default in repayment?

Inference: Logistic Regression is a simple model with accuracy (~82%) matching to our Random Forrest model.

Acknowledgements:

This code is inspired by various posts and analysis already done in this dataset. 
