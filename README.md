# Bank Customer Churn
*Exploratory Data Analysis of an European Bank's Customer Churn patterns*

## 1. Project Background

The dataset used for the following project was provided by Maven Analytics and it comprises account information of 10,000 customers  from an undisclosed European Bank. The Bank’s Marketing Team requests to identify possible causes of impact on customer retention.

As a data analyst, I have carried out an EDA on the data with the aim to discover and  thoroughly synthesize Customer Churn patterns and trends. Based on the available information, insights and recommendations are drawn by applying these types of Market Segmentation:

- **Demographic Segmentation**: based on available objective information (gender, age, income, ext.)
- **Geographical Segmentation**: where the customers are located (country)
- **Behavioral Segmentation**: how the client makes use of the services (product quantity, activity, tenure)

### 1.1 Data Structure
The dataset’s structure as seen below consists of 2 tables: Customer_info and Account_info with a total row count of 20,002 records. The dataset was cleaned and relieved of duplicates and considerable outliers.
![ERD - Bank Customer Churn](https://github.com/user-attachments/assets/08df895b-bd90-49ce-b561-9dcd7a176f4d)
### 1.2 Data Analysis
Excel was the tool used for the data cleaning and transformation. A dashboard was developed to offer the Marketing Team the opportunity to globally monitor customer retention. All can be viewed [Here](Bank_Churn_Clean.xlsx)


## 2. Executive Summary

The Bank’s Customer Accounts databases analysis shows an overall churn rate of 20% with Females being more inclined to exit.
Germany is the country with the highest churn rate with 32%

Ages between 50 and 60 have the greatest retention rate, Germany however has the greatest loss with clients in all age ranges under 50 years which raises concerns.

The median salary of churned customers is higher than the retained for all estimated salary ranges aside from range 50,000 – 100,000 where the present users have a higher income. The estimated salary range with the maximum churn rate is €150,000 - €200,000.

100% of customers using 4 products have left the bank  and all those users with credit score under 400 also followed. 65% of churned users are inactive.

Customers have the tendency to churn after the second year in Spain and France, while after the first year in Germany.

The following table highlights how Activity, Gender and Number of Products are the variables which have an impact on customer churn based on the country in consideration: Gender and whether or not a user is active or inactive have a very strong influence on client’s retention.

![Summary Table](https://github.com/user-attachments/assets/ce1e3eb4-7bf9-47fa-8ea9-7ebffdb1015f)

![Summary Legend](https://github.com/user-attachments/assets/389f0c24-3ffe-4974-8a21-dea2f07bf570)


## 3. Analysis

### 3.1 Demographic Segmentation
The bank’s customers database comprises a relatively even gender distribution with 55% being Male while 45% Female and it is observed that the second have a higher churn rate of 11% compared to the 9% of the opposite gender.
