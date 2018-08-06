### RFM-Analysis

#### What is RFM Analysis?

RFM  (recency, frequency, monetary) analysis is a marketing technique used to determine quantitatively which customers are the best ones by examining how recently a customer has purchased (recency), how often they purchase (frequency), and how much the customer spends (monetary).

#### Problem statement:

Use the transactions data set at the link below contains all the transactions occurring between dd/mm/yyyy and dd/mm/yyyy for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
https://archive.ics.uci.edu/ml/datasets/Online+Retail

* Calculate the RFM values for each customer (by customer id).

For detailed description of the terms, refer the link below
https://en.wikipedia.org/wiki/RFM_(customer_value)

* For Recency calculation, use 12/2011 as current month. So, the Recency should be how many months before he or she has made a purchase from the current date. If made a purchase in December, then the values should be 0 and so on so forth.
*	Frequency – At an average how often each customer make purchases in a month.
*	Monetary Value – Total Spend by the customers in the whole year.

#### Implementation

* identify top 10 customers based on frequency and monetary value. Sort them based on first frequency and then monetary value.
* identify optimal number of segments using dendogram and elbow method.
* Create final segment of customers and label the customers based on which segment they belong to. 
* Explain each segment intuitively. 
