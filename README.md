# Consumer Complaint analysis

This repository borrows data from CFPB's [Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/#download-the-data). 
Complaints that the CFPB sends to companies for response are published in the Consumer Complaint Database after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first.

The aim of my analysis is to identify treat the Company's response to a complaint as the target variable. I have analysed the variables that are relevant in determining how the company responded to a consumer complaint, and build a random forest based predictive model to make predictions on the target variable. Finally, I have compared this with a decision tree model, which resulted in an almost similar prediction capability. The scoring metric used here is the F1 Score since the data is highly imbalanced.
