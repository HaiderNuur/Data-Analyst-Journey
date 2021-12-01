# Using Data Analysis for Detecting Credit Card Fraud
Companies today are employing analytical techniques for the early detection of credit card frauds, a key factor in mitigating fraud damage. 
The most common type of credit card fraud does not involve the physical stealing of the card, but that of credit card credentials, 
which are then used for online purchases.

Imagine that you have been hired as a Data Analyst to work in the Credit Card Division of a bank. And your first assignment is to join your team 
in using data analysis for the early detection and mitigation of credit card fraud.  

In order to prescribe a way forward, that is, suggest what should be done in order for fraud to get detected early on, 
you need to understand what a fraudulent transaction looks like. And for that you need to start by looking at historical data. 
Here is a sample data set that captures the credit card transaction details for a few users. 
![MNep_ZY-ScaXqf2WPrnG0Q_3be5abeee8944747ab0a58a705df415c_DA_1-Q7-Data-Table](https://user-images.githubusercontent.com/20629270/142776748-18cd611c-35cd-48d9-9ec4-acf9613c57c3.png)


Descriptive techniques of analysis, that is, techniques that help you gain an understanding of what happened,
include the identification of patterns and anomalies in data. Anomalies signify a variation in a pattern that seems uncharacteristic, or, 
out of the ordinary. Anomalies may occur for perfectly valid and genuine reasons, but they do warrant an evaluation because they can be a sign of fraudulent activity.  

Past studies have suggested that some of the common events that you may need to watch out for include:  
- A change in frequency of orders placed, for example, a customer who typically places a couple of orders a month, 
suddenly makes numerous transactions within a short span of time, sometimes within minutes of the previous order.
- Orders that are significantly higher than a user’s average transaction.
- Bulk orders of the same item with slight variations such as color or size—especially if this is atypical of the user’s transaction history.
- A sudden change in delivery preference, for example, a change from home or office delivery address to in-store, warehouse, or PO Box delivery.
- A mismatched IP Address, or an IP Address that is not from the general location or area of the billing address.

###### Before you can analyze the data for patterns and anomalies, you need to:
- Identify and gather all data points that can be of relevance to your use case. 
For example, the card holder’s details, transaction details, delivery details, location, and network are some of the data points that could be explored. 
- Clean the data. You need to identify and fix issues in the data that can lead to false or incomplete findings, 
such as missing data values and incorrect data. You may also need to standardize data formats in some cases, for example, the date fields. 
- Finally, when you arrive at the findings, you will create appropriate visualizations that communicate your findings to your audience. 

The graph below samples one such visualization that you would use to capture a trend hidden in the sample data set shared earlier on in the case study.
![kumNKCbZSdqpjSgm2Ynaxw_0326b11a493e49e1b10bc7b2a1f5d7e2_DA_1-Q9-Chart](https://user-images.githubusercontent.com/20629270/142776762-f5090b28-d07a-4b8b-a506-fce2d5e349f8.png)


## In the next section you will be asked to answer the following 5 (five) questions based on this case study:

#### Question 1:List at least 5 (five) data points that are required for the analysis and detection of a credit card fraud. (3 marks)
Answer: IP address, user ID, Account number, Shipping address, Transaction date, Transaction TIme, Transaction value. 

#### Question 2: Refer to the data table below and identify 3 (three) errors/issues that could impact the accuracy of your findings. (3 marks)
![MNep_ZY-ScaXqf2WPrnG0Q_3be5abeee8944747ab0a58a705df415c_DA_1-Q7-Data-Table](https://user-images.githubusercontent.com/20629270/142776799-299528ed-8a24-4c59-a938-2572d98871fb.png)

Answer: 1. Two transaction ids are missing 2. one transaction value is missing 3. Age of the user ellend is missing

Good Answer: Missing transaction value, Missing IP Address, Date format inconsistency

#### Question 3: Refer to the data table below and identify 2 (two) anomalies or unexpected behaviors, that would lead you to believe the transaction may be suspect. (2 marks)
Answer:
1. Shipping address of johnp in the 4th, 5th & 6th transaction are different than usual home address. And point to note that ,  
value of these orders are pretty higher than normal, also 4th & 5th order are done in minutes. 
3. For ellend, the 3rd transaction is suspecious because the ip addrees is different, postal address is different and value is pretty bigger

Good answer: 
- Significantly higher Transaction Value where Shipping Address has been changed from home/office address to P.O. Box.
- Higher Transaction Value and increased frequency of transactions.
- IP Address change and significantly higher Transaction Value.
- IP Address change and Shipping Address change

#### Question 4: Briefly explain your key take-away from the provided data visualization chart. (1 mark)
![M1sTK7IQQAibEyuyEAAIBw_62598de906f0424494f10efc877a7c5c_DA_1-Q9-Chart](https://user-images.githubusercontent.com/20629270/142777044-652cce71-7bf0-499a-9e0e-a8d65af850d9.png)
Answer: There is a high chance the ellend's 3rd transaction is fradulant and also the 3rd, 4th & 5th of johnp

Good Answer: The visualization depicts the transaction values per transaction for all three users. The key take-away from this visualization is the sharp rise in the transaction values for users johnp and ellend, which may be indicative of an anomaly.  


#### QUestion 5:Identify the type of analysis that you are performing when you are analyzing historical credit card data to understand what a fraudulent transaction looks like. 
Hint: The four types of Analytics include: Descriptive, Diagnostic, Predictive, Prescriptive. (1 mark)
Answer: it is a Descriptive technique, the data helped me to understand what happends and let me find anomalies in data. 

Good Answer: The learner identified 'Descriptive Analytics' as the type of analysis that they are performing when they are analyzing historical credit card data to understand what a fraudulent transaction looks like.

