# Customer_Churn_ML_Project
### Group members:
- Shaima Alharbi 
- Ebtisam Alrehili 
---
### In this project we work on  [Customer Churn data set](https://github.com/gumdropsteve/intro_to_machine_learning/raw/main/day_05/data/churn_data.csv).

### First: Exploratory data analysis(EDA):
- The price of the Fiber service is higher than the price of the DSL service
- We expect that the customers who subscribed to the Fiber service left the company due to the high price of the service, while most of the customers who had the DSL service did not leave it.
- Some services depends on other services like(online security and multiple lines )
- There are services that are not demanded by many customers like Online Security ,Oline backup, device protictio and tech support.
- Customer who has Month to month contracts more than another contrat.
- Most of the Customer who leave the company were the ones who had a month to month contract.
- Most of the Customer payied by electronic check and leave the compny.
- The number of customer who has not dependent and stay in the company is twice the number of customer who has dependent.
- We expect the customer leave company because have dependents, that's mean the customer who have dependents need more services. (More price)


### Second: Build LogisticRegression Model and Improve it:
We noticed some null values and replace it, we extract Categorical features, we split our data to test and train data then make best hyperparams to build LogisticRegression model and improve it.

### Third: Ideas for customer retention programs:
- We noticed the prices for the Fiber service are expensive, some discounts may help people increase their demand for the service.
- The company should apply discounts or offer on the most important service (Internet services) to increase the customers.
- We noticed the most costumers have dependents don't stay in the company long because they payied more price, should on the company make more offers for this class.
- Most of the Customer who leave the company were the ones who had a month to month contract, The company should focus on improve months to months contract to customer retention.
