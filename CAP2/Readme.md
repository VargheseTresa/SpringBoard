# Customer Churn Prediction System 

The ability to accurately predict the customers who have a higher probability to churn is critical in customer retention.  Careful analysis of available data on customers can reveal any trends or potential issues that needs to be addressed. Using this, we can also build machine learning models that can predict probability of customer churn.



## 1. Data
Telco is a fictional telecommunications company that provided home phone and Internet services to customers in California in Q3. The company is looking to identify any interesting patterns among the customers who left the company in Q3 so that they can implement strategies to retain more customers in the next quarter. The following data are used in the analysis and modelling.

> * [IBM Accelerator catalog](https://community.ibm.com/accelerators/catalog/content/Telco-customer-churn)
    This dataset includes demographics information about customer such as gender, dependents, etc. as well as specific information on type of services the customer have with the company. The target column contains the churn info. It has the value 1 if the customer has left the company. Otherwise, it has the value of 0.
> * [United States zipcodes database](https://www.unitedstateszipcodes.org/ca/#zips-list)
    This dataset maps the zip codes to county name. This helps in better management of categorical feature without losing much information on customer's geographic location.