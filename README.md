# Random_Forest_Classifier_Customer_churn_prediction

Dataset link: https://drive.google.com/file/d/1D9xtn7Si1QRvX4d8GhaM9SpOHSnDrO71/view?usp=sharing

# Business Problem
In the Telecom sector, a massive amount of data is being generated on a day by day foundation because of a sizable customer base.Decision makers and commercial enterprise analysts emphasized that achieving new clients is deared than maintaining the present ones. Business analysts and purchaser dating management analyzers want to recognize the reason behind churning clients.

# About Dataset
### Context
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets]

### Content
Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

### The data set includes information about:
Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

# Table of Contents of the notebook
1. Business Problem and Dataset Information
2. Data Exploration
3. Data Cleaning
   * Performed Data manipulation
   * Performed null value analysis
   * Perform duplicate value analysis
4. Data Visualization
   
![image](https://github.com/user-attachments/assets/0462050a-93f3-4eb1-b481-91d8201dde69)

  
5. Conclusion from Data Analysis
   * 75% of customer who have Month-to-Month Contract have opted to move out as compared to 13% of customers who have signed One Year Contract and 3% of customers who have signed Two Year Contract.
   * Majority of the customers who moved out were having Electronic Check as Payment Method and others who opted for Credit-Card automatic transfer / Bank Automatic Transfer and Mailed Check as Payment Method were less likely to switch.
   * Fiber optic service which was choosen by a lot of customers and it's evident that there's high churn rate among these customers. This could expose an issue in the Fiber optic service which dissatisfied most of it's customers, further looking into the issue might find a better and apt solution.
   * Customers who opted for DSL service are larger in number and is found to have less churn rate compared to Fibre optic service
   * Customers without dependents and customers who have partners are more likely to churn while senior citizens being the most of churn.
   * The absence of online security, Paperless Billing system and services with no TechSupport were the similiar trend are of the customers who are most likely churn.
   * There's a small fraction of customers who are more likely to churn and it's been found that they don't have a phone service.
6. Feature Selection

![image](https://github.com/user-attachments/assets/783550d1-6097-4aac-8e51-35022e35b33f)
 
   * Chi-Square Test
     
     
7. Feature Engineering
   * Label Encoding
   * Train Test Split
   * Data Oversampling using SMOTE
8. Model Building
9. Model Evaluation
    * Used Accuracy score to evaluate model performance
    * Achieved 0.76 (76%) accuracy score.
11. Hyperparameter Tuning
    * Marginallt improved accuracy score(0.77 ~ 77%)
