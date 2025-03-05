# Bank Customer Churn
*Exploratory Data Analysis of an European Bank's Customer Churn patterns*

## Table of Contents


## 1. Project Background

The dataset used for the following project was provided by Maven Analytics and it comprises account information of 10,000 customers  from an undisclosed European Bank. The Bank’s Marketing Team requests to identify possible causes of impact on customer retention.

As a data analyst, I have carried out an EDA on the data with the aim to discover and  thoroughly synthesize Customer Churn patterns and trends. Based on the available information, insights and recommendations are drawn by applying these types of Market Segmentation:

- **Demographic Segmentation**: based on available objective information (gender, age, income, ext.)
- **Geographical Segmentation**: where the customers are located (country)
- **Behavioral Segmentation**: how the client makes use of the services (product quantity, activity, tenure)

### 1.1 Data Structure
The dataset’s structure as seen below consists of 2 tables: Customer_info and Account_info with a total row count of 20,002 records. The dataset was cleaned and relieved of duplicates and considerable outliers.
<img src="https://github.com/user-attachments/assets/08df895b-bd90-49ce-b561-9dcd7a176f4d" alt="Alt Text" style="width:50%; height:auto;">
### 1.2 Data Analysis
Excel was the tool used for the data cleaning and transformation. A dashboard was developed to offer the Marketing Team the opportunity to globally monitor customer retention. All can be viewed [Here](Bank_Churn_Clean.xlsx)

<img src="https://github.com/user-attachments/assets/4755a73c-0fb5-4866-b418-0efe118806d6" alt="Alt Text" style="width:50%; height:auto;">



## 2. Executive Summary

The Bank’s Customer Accounts databases analysis shows an overall churn rate of 20% with Females being more inclined to exit.
Germany is the country with the highest churn rate with 32%

Ages between 50 and 60 have the greatest retention rate, Germany however has the greatest loss with clients in all age ranges under 50 years which raises concerns.

The median salary of churned customers is higher than the retained for all estimated salary ranges aside from range 50,000 – 100,000 where the present users have a higher income. The estimated salary range with the maximum churn rate is €150,000 - €200,000.

100% of customers using 4 products have left the bank  and all those users with credit score under 400 also followed. 65% of churned users are inactive.

Customers have the tendency to churn after the second year in Spain and France, while after the first year in Germany.

The following table highlights how Activity, Gender and Number of Products are the variables which have an impact on customer churn based on the country in consideration: Gender and whether or not a user is active or inactive have a very strong influence on client’s retention.

<img src="https://github.com/user-attachments/assets/ce1e3eb4-7bf9-47fa-8ea9-7ebffdb1015f" alt="Alt Text" style="width:30%; height:auto;">

<img src="https://github.com/user-attachments/assets/389f0c24-3ffe-4974-8a21-dea2f07bf570" alt="Alt Text" style="width:30%; height:auto;">


## 3. Analysis

### 3.1 Demographic Segmentation
The bank’s customers database comprises a relatively even gender distribution with 55% being Male while 45% Female and it is observed that the second have a higher churn rate of 11% compared to the 9% of the opposite gender.

<img src="https://github.com/user-attachments/assets/7e0de4c2-341b-4276-9243-61d258fbc24b" alt="Alt Text" style="width:20%; height:auto;">

The age range between 30 and 40 being the most populated covering 43% of customers database. The ages between 50 and 60, however,  carry the highest number of churned customers with 56% of their population followed by range 60 – 70 with 35%. In particular, clients aged 56 and 60 have a churn rate of 71% and 52% respectively.

<img src="https://github.com/user-attachments/assets/e5d7b5f0-be74-4b03-af08-79f32d619ff3" alt="Alt Text" style="width:50%; height:auto;">

The churned customer count is nearly evenly distributed across the salary groups and the income range between €150,000 and €200,000 showcases the highest customer exist with 21.47% , more specifically those clients earning between € 170,000 and €180,000.

Furthermore, it is relevant to highlight that looking closely into the income range €110,000 - €120,000 it can be noticed that the churn rate is of 21.59% that is the second highest.

<img src="https://github.com/user-attachments/assets/687a8eb3-3222-4c39-aafd-9e67c0a99e5d" alt="Alt Text" style="width:50%; height:auto;"> 

It is also observed that in all salary ranges the median salary is higher in those clients who have exited, except for range  €100,000 –  €150,000 where the exited clients median salary is €1,629 lower compared to those still present.

A total of 3,331 customers fall under the “Fair” Credit Score range where the customers have an average credit score of 626 and fill 33% of the total dataset. Customers with a Poor credit score have the greatest  churn rate  (22.03%) followed by Very Good and Fair.

<img src="https://github.com/user-attachments/assets/384f1537-eee2-453e-b7fb-19acc26c9aa9" alt="Alt Text" style="width:50%; height:auto;">

Moreover, there is a 0% retention rate for all clients with credit scores under 400 while a 25.30% churn rate for credit scores between 400 and 450.

<img src="https://github.com/user-attachments/assets/32fdf74d-f6b9-4ba6-9cdc-ecd5feeca4ad" alt="Alt Text" style="width:50%; height:auto;">

### 3.2 Behavioural Segmentation
Focusing on churned customers, their greatest share has a 1 year retention duration, followed by 3 & 9 and 5 years. The churn distribution across the number of years is however relatively even.

<img src="https://github.com/user-attachments/assets/2858566f-d6a7-4b27-8a2e-b79d293a5b50" alt="Alt Text" style="width:50%; height:auto;">

Over half of the exited users are inactive while 55% of the retained clients are active.

<img src="https://github.com/user-attachments/assets/116a0870-7585-4d60-8e5f-64658f4f6ac2" alt="Alt Text" style="width:25%; height:auto;">

<img src="https://github.com/user-attachments/assets/62e4f356-747f-47fe-9e87-a958efc86111" alt="Alt Text" style="width:25%; height:auto;">

Over 60% of churned clients do not possess a card while 55% of retained users do.  Additionally, there is a perfect positive relationship between a customer being active and he/she owning a credit card.

<img src="https://github.com/user-attachments/assets/7ae9fad5-b5c4-4116-9dfd-37736c4fe209" alt="Alt Text" style="width:50%; height:auto;">

Over 90% of the current customers make use of 2 products while 72% of 1 product only. It can be observed that customers who have 4 products have all exited and that 80% of the users with 3 products have also churned.

<img src="https://github.com/user-attachments/assets/5b840611-7885-4645-9c33-a448f037e5c6" alt="Alt Text" style="width:50%; height:auto;">

Centering on the account balance of churned clients, 42% of the users are found in the bank account range  €100,000 –  €150,000 while range <€10,000 holds 25% of the exited users; almost all in the second with a balance equal to 0.

<img src="https://github.com/user-attachments/assets/d7606307-8995-484a-a218-5c12dcbae389" alt="Alt Text" style="width:50%; height:auto;">

In addition, the balance median of churned customers in range €50,000 - €100,000 is  higher  by €1,713 than that of the retained clients-

<img src="https://github.com/user-attachments/assets/08ad6644-e682-42aa-b50f-cf8903607b3e" alt="Alt Text" style="width:50%; height:auto;">


### 3.3 Geographical Segmentation
France holds the highest number of retained customers followed by Spain with a count of 2,063. Germany, however, shows the highest share of churned users that occupy 32% of the country’s global user count.

<img src="https://github.com/user-attachments/assets/0629421a-f46e-49dc-9462-b7b4969a3762" style="width:40%; height:auto;">

Please note that all discussions henceforth will focus around the churned population only.

#### 3.3.1 Salary Orientated
Germany’s highest customers count has users earning less than €50,000 whereas France and Spain both have the highest count for salary €150,000 - €200,000.

<img src="https://github.com/user-attachments/assets/91ad5b3a-43b7-48d1-b92c-691709b6da4d" style="width:50%; height:auto;">

Additionally, when it comes to France and Spain there is a strong positive relationship between salary range and churn count. In other words, the higher the client’s salary, the higher the probability of exit. In the case of Germany, on the other hand, there is a moderate negative relationship between the two variables: the higher the salary the lower the chance of customer exist.

Though the global median salary in Germany is the highest compared to other countries (same applies for the median salary of its retained customers), the country’s median salary for exited clients is the lowest with €96,498.14.

Additionally, when it comes to France and Spain there is a strong positive relationship between salary range and churn count. In other words, the higher the client’s salary, the higher the probability of exit. In the case of Germany, on the other hand, there is a moderate negative relationship between the two variables: the higher the salary the lower the chance of customer exist.

Though the global median salary in Germany is the highest compared to other countries (same applies for the median salary of its retained customers), the country’s median salary for exited clients is the lowest with €96,498.14.

<img src="https://github.com/user-attachments/assets/7d575eac-2a27-4eba-95fb-8eb0b1c7a7a4" style="width:50%; height:auto;">

Germany leads with the highest median salary in all ranges aside from  range 50,000 – 100,000  where it has the lowest. Furthermore, Germany holds the highest median salary for present users and the lowest for churned.

<img src="https://github.com/user-attachments/assets/5f90d2c0-ce9d-44c2-9c56-a4eee95ff4f4" style="width:50%; height:auto;">

<img src="https://github.com/user-attachments/assets/79319a51-c00c-4de1-aee8-cc215563bda9" style="width:50%; height:auto;">

#### 3.3.2 Age Orientated
Germany has the highest customer count for ages under 50,  France alternatively leads in ages between 50 and 60.

<img src="https://github.com/user-attachments/assets/6258837f-25f1-4feb-82d6-374d46d80cf9" style="width:50%; height:auto;">

All three countries present a negative relationship between age and churn count. More specifically,  France and Germany have a week correlation while Spain a moderate one.

#### 3.3.3 Credit Score Orientated

The following chart shows the  most populated credit score ranges across the countries: most of the terminated users in France have credit score between 600 and 700, in Germany and Spain between 600 and 650 with 154 and 78 customers respectively.

<img src="https://github.com/user-attachments/assets/8171742b-d756-4053-b051-3fc4a66f14d5" style="width:50%; height:auto;">

In other words, the greater part of the churned population falls under the Fair Credit Score Group across all the countries. In other words, the greater part of the churned population falls under the Fair Credit Score Group across all the countries.

#### 3.3.4 Prodcuts Orientated
Across all countries the number of products most popular is 1 and 2 with France and Germany with the peak  figures of clients that have the mentioned number of products.

A very strong negative relationship is discovered between the number of products and the churn frequency: the higher the number of products, less are the chances of experiences a customer loss.

#### 3.3.5 Tenure Orientated

Spain and France have the highest count of leaving clients at 2 years, then 3 and finally 1. In Germany, on the other hand , customers tend to exit most in year 1 with a significant count of 105 heads.

<img src="https://github.com/user-attachments/assets/73af816f-7916-4c56-875f-bb29d1f86263" style="width:50%; height:auto;">

However, it is observed that there is an absent to weak relationship between the number of retention years and the churn probability, which could potentially mean that customer loyalty is determined by other factors.

#### 3.3.6 Gender and Activity Orientated
It is observed that in all countries the number of females is higher than the males. France has the highest difference between genders with 24% and Germany the lowest with 18%.

<img src="https://github.com/user-attachments/assets/94709ace-38f7-44f9-b57a-ac8be00263e6" style="width:50%; height:auto;">

<img src="https://github.com/user-attachments/assets/eb1cc040-1f1a-4385-8c20-3ba8fa1f99b6" style="width:50%; height:auto;">

In fact, while carrying out a correlation analysis it is observed that both Gender and Activity have a perfect relationship with the churn probability.


## 4. Recommendations

Considering that Females have the tendency to churn, the bank must focus particular attention on the gender by offering female orientated products, incentives and/or offers.

Furthermore, incentive programs and rewards should be proposed to customers between 40 and 70 years and those whose credit score is under 400. Further investigation should be carried out in Germany to better understand the reasons behind the elevated churn of clients  under 50 years.

The Marketing department should motivate users to have as many products as possible as this reduces the chances of them leaving.

Since a large number of users exit the bank after 1 or 2 years, the marketing team should be informed via an alert or notification whenever a customer is approaching the 12 month retention target, ideally, the alert should be activated at 9 months from customer enrolment.

A notification should also be set when a user reaches an account balance of €100,000 in order to share a tailored promotional offer with the aim to retain him/her. Another alert when the account balance is €0  as the customer will surely exit at the value.

To conclude, the marketing team should develop their future strategies to tackle customer churn based on the clients Age, Gender and Activity as these are the 3 variables which have a direct influence on the overall churn rate. 


