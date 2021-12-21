# Customer Churn Prediction System 

The ability to accurately predict the customers who have a higher probability to churn is critical in customer retention.  Careful analysis of available data on customers can reveal any trends or potential issues that needs to be addressed. Using this, we can also build machine learning models that can predict probability of customer churn. This helps an organization to devise suitable retention measures as churn rate is an important factor that directly affects the revenue.



## 1. Data
Telco is a fictional telecommunications company that provided home phone and Internet services to customers in California in Q3. The company is looking to identify any interesting patterns among the customers who left the company in Q3 so that they can implement strategies to retain more customers in the next quarter. The following data are used in the analysis and modelling.

> * [IBM Accelerator catalog](https://community.ibm.com/accelerators/catalog/content/Telco-customer-churn)
    This dataset includes demographics information about customer such as gender, dependents, etc. as well as specific information on type of services the customer have with the company. The target column contains the churn info. It has the value 1 if the customer has left the company. Otherwise, it has the value of 0.
> * [United States zipcodes database](https://www.unitedstateszipcodes.org/ca/#zips-list)
    This dataset maps the zip codes to county name. This helps in better management of categorical feature without losing much information on customer's geographic location.
    
## 2. Method


## 3. Data Cleaning
[Data Cleaning Report](https://github.com/VargheseTresa/SpringBoard/blob/main/CAP2/CAP2_wrangling_v1.ipynb)
[Data preprocessing Report](https://github.com/VargheseTresa/SpringBoard/blob/main/CAP2/CAP2_preprocessing.ipynb)

The dataset includes 7043 observations about telecommunication customers from California. Out of the 7043 customers, 27% of the customers left the company in the end of Q3. Each observation contains various columns related to the customer and the type of services they use. There are no missing values in any columns except `Churn Reason`. This column has a value only for those customers who left the company. The preprocessing steps performed on other columns are described below.

* **Preprocessing of numerical columns** The identified numerical columns are Tenure Months, Monthly Charges, Total Charges, Churn Score and CLTV. Out of these, Monthly Charges and Total Charges are highly correlated. Hence we keep only one of these columns. Also, as all the columns are in different scales, they are normalized to be on the same scale. This prevents columns with high magnitude such as CLTV from dominating over other low magnitude columns.

## 4. EDA
[EDA Report](https://github.com/VargheseTresa/SpringBoard/blob/main/CAP2/CAP2_EDA.ipynb)


## 5. Algorithms & Machine Learning

[ML Notebook](https://github.com/VargheseTresa/SpringBoard/blob/main/CAP2/CAP2_modelling.ipynb)

## 6. Predictions
[Final Predictions Notebook](https://colab.research.google.com/drive/1vLkoW_4SYessy_igmJxlVz_jEPlgJ06v)