# Customer Retention Analysis
# Problem statement
To understand the churn rate of the given dataset and analyse the different factors involved in the customer retention.
Create a dashboard for the reflecting the KPIs.
Get the feedbak for the dataset.

# Data Visualization

Dashboard for the analysis is shown below:

<img width="1040" alt="Screenshot 2021-08-21 at 3 03 22 PM" src="https://github.com/sruthi-sru/power-bi/assets/71058362/b2789eb6-24a6-42cf-a684-6fddd0f272cd">




# Feedbacks

* Percentage of male and female are same 50%.
 
* 16% of customers are only Senior Citizens.
  
* churn rate is 27% from total of 7043 Customers.
  
* In Internet Service, Fiber Optics is used more.
  
* Month to month contrat is highest.

# Calculations 

churn rate = DIVIDE(CALCULATE(COUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[Churn] = "Yes"),COUNT('01 Churn-Dataset'[customerID]))* 100

gender % = DIVIDE(CALCULATE(COUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[gender] = "Female"),COUNT('01 Churn-Dataset'[customerID]))* 100

Device protection% = DIVIDE(CALCULATE(COUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[DeviceProtection] = "Yes"),COUNT('01 Churn-Dataset'[customerID]))*100


paper % = DIVIDE( CALCULATE(COUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[paperlessBilling] = "Yes"),COUNT('01 Churn-Dataset'[customerID]))* 100

senior % = DIVIDE(CALCULATE(COUNT('01 Churn-Dataset'[customerID]),'01 Churn-Dataset'[SeniorCitizen] = "Yes"),COUNT('01 Churn-Dataset'[customerID]))*100






