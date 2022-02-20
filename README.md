# telco churn 
**What is churning and why is it important to study..???**
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs."
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another.
In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate.
Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
**Goal of project:**
In this project, we will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.
**Feature information:**
CustomerID:  A unique ID that identifies each customer.
Gender:  The customer’s gender: Male, Female
-Senior Citizen: Indicates if the customer is 65 or older: Yes, No
Partner:  Whether the customer is married or not
Dependents:  Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc.
Tenure in Months:  Indicates the total amount of months that the customer has been with the company 
Phone Service:  Indicates if the customer subscribes to home phone service with the company: Yes, No
Multiple Lines:  Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No
Internet Service:  Indicates if the customer subscribes to Internet service with the company: No, DSL, Fiber Optic, Cable.
Online Security:  Indicates if the customer subscribes to an additional online security service provided by the company: Yes, No
Online Backup: Indicates if the customer subscribes to an additional online backup service provided by the company: Yes, No
Device Protection Plan:  Indicates if the customer subscribes to an additional device protection plan for their Internet equipment provided by the company: Yes, No
Premium Tech Support:  Indicates if the customer subscribes to an additional technical support plan from the company with reduced wait times: Yes, No
Streaming TV:  Indicates if the customer uses their Internet service to stream television programing from a third party provider: Yes, No. 
Streaming Movies: Indicates if the customer uses their Internet service to stream movies from a third party provider: Yes, No. 
Streaming Music: Indicates if the customer uses their Internet service to stream music from a third party provider: Yes, No. 
Contract: Indicates the customer’s current contract type: Month-to-Month, One Year, Two Year.
Paperless Billing: Indicates if the customer has chosen paperless billing: Yes, No
Payment Method: Indicates how the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check
Monthly Charge: Indicates the customer’s current total monthly charge for all their services from the company.
Total Charges : Indicates the customer’s total charges.

**Insights we Got From analysis:**
Customers with spouses and childrens might churn less to keep the service running for family.
-more monthly charges increases total charges.
- more expensive contract leads churning.
- senior citizens tend to churn less may due to extra process of terminating contracts.
- cutomers who are using additional services are lessly likely to churn
-individual who are new in the services are mostly prefer to take month to month plan,
as period of staying increases upto 60-70 month i.e individual who are staying 5-6 years are more likely to sign contract of two year because of trust building
- churning rate is quite high in the cutomers who are bounded to service in between 0-12 month, as bound increases churning decreases

**model prediction:**
Support Vector Machine algorithm with Grid search cv giving higher accuracy.
