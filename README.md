# Data Mining using Tableau
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Extras/Data-Mining-2.jpg)
## What exactly the Data is?
Its a large dataset with 10000 records of a list of customers of a Bank. Bank is recently facing a problem that a lot of its customers are leaving the Bank. The dataset contains details like CustomerID, CreditScore, Geography, Age, Tenure, Balance, NumberOfProducts, IsActiveMember, EstimatedSalary and if the customer has excited the bank or not. We are trying to analyze what type of customers are most likely to leave the Bank.

Here we have drew meaningful Insights and created multiple visualizations using Tableau for Churn Investigation. We also have Visualized ad-hoc A-B test, created Bins, classification tests for analyzing variables, combined multiple charts together, and validated mined data using Chi-Squared test.


## How can one obtain the Data?
On can download the dataset using the following link.

http://www.superdatascience.com/wp-content/uploads/2015/08/Churn-Modelling.xlsx

## Individual Analysis and its Inference
## Here we have tried to analyze the total number of customers in different countries of Europe
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Map.png)

## Here we have tried to visualize ad-hoc A-B test. We can see the percentage of each gender of customers who exited the Bank. We can infer that most of the females are likely to exit the Bank.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Gender.png)

## Here we can see the actual values of customers who exited.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Gender_Actuals.png)

## Here we have added a reference line and compared percentages of customers who exited based on geography. We can infer that people from Germany are most likely to leave the Bank. We can try to find the reason by investigating further.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Country.png)

## Here we can see the actual values of customers who exited.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Country_Actuals.png)

## Here we have tried to analyze if having a credit card has a contribution in customers exiting the Bank. And actually it doesn't matters if you have a credit card or don't.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/HasCrCard.png)

## Here we can see the actual values of customers who exited.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/HasCrCards_Actuals.png)

## Here we have tried to analyze does it affects to customers leaving the Bank if they are active or no. And we can see that customers who are less active have a tendency to leave the Bank.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/IsActiveMember.png)

## Here we can see the actual values of customers who exited.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/IsActiveMember_Actuals.png)

## Here we have tried to analyze if having more number of products makes a loyal customer. For the last 2 columns we got very less observations so we can't really rely on them. But we can see that the customers who have more products enrolled with the bank, they are most likely to stay.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/NumberOfProducts.png)

## Here we have tried to validate the records. We have drawn the chart on the basis of last digit of the customerID and since it has got no relevance weather a customer will stay or leave the Bank, we can see that our data is valid.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Validation.png)

## Here we have created bin for age and tried to analyze total number of customers who fall in certain age group.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Age%20Distribution.png)

## Here we have tried to analyze the total number of customers and out of those who exited in a particular age group. We can infer that there are lot of people between age group of 45 and 60 who have left the Bank.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Age.png)

## Here we have tried to analyze if balance of customer has any connection to exiting the bank. And we can observe that balance has no relevance to the customers exiting the Bank. Whichever spikes we observe in the chart are not reliable since we have less number of records for the same.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Balance.png)

## Here we have tried to analyze if estimated salary of customer has any connection to exiting the bank. And we can observe that estimated salary has no relevance to the customers exiting the Bank.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Estimated%20Salary.png)

## Here we have tried to analyze the if credit score of customer has any connection to exiting the bank. And we can observe that credit score has no relevance to the customers exiting the Bank. We can see that customers with credit score 350, all have left the Bank but again we can't rely on it as data is very less for the same.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Credit%20Score.png)

## Here we have tried to analyze the if tenure of customer has any connection to exiting the bank. And we can observe that tenure has no relevance to the customers exiting the Bank.
![alt text](https://github.com/swarupmishal/Data-Mining-using-Tableau/blob/master/Reports/Tenure.png)




## Conclusion
##### We can create offers or something for targetting female customers, customers in Germany, non-active members, customers with less number of products and customers from age group of 45 to 60 so that they won't leave the Bank. We can connect with them on personal level to find out their problems and try to resolve them for reducing the customers exiting the Bank.
