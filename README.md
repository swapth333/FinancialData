   # Consumer Complaint analysis

**Dataset** 

This repository borrows data from CFPB's [Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/#download-the-data). These are Complaints from customers on financial products and services. There are more that 2500K complaints with 18 attributes. These are real world complaints of customers on financial products and services. Each complaint is lebelled with specific product, sub product, issue, sub issue, customer complaint narrative, customer disputed, hence it can become a real supervised machine learning problem with classification. 
The CFPB sends these complaints to companies for response are published in the Consumer Complaint Database after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first.

**Exploratory Data Analysis**

We have done Exploratory data analysis to find which product had maximum complaints, what was their issues, which company received maximum complaints, did customer dispute?. 

**Predictions: Classification Models:** 

Since most of the attributes are categorical this becomes classifications problem. 

1. The aim of our analysis is to identify treat the Company's response to a complaint as the target variable. I have analysed the variables that are relevant in determining how the company responded to a consumer complaint, and build a random forest based predictive model to make predictions on the target variable. Finally, I have compared this with a decision tree model, which resulted in an almost similar prediction capability. The scoring metric used here is the F1 Score since the data is highly imbalanced.

2. In second part we took product and customer compolaint narrative for our analysis. We find out what were the mostly used unigrams and bigrams for each product. Text classifier also helps to predict product based on complaint. 


