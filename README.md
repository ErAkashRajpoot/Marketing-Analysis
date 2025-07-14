# Marketing Analysis Project

## Description

This project aims to obtain a deeper understanding about consumer behaviour by taking advantage of different datasets, which contain information about customers, orders, products,
 customers reviews and more.
Four main marketing analytics techniques have been implemented to reach this goal:
* **RFM model**: this model aims to compute a score for each customer, the so called 'RFM score', through the analysis of three values, i.e. Recency (time passed from last purchase),
   Frequency (number of purchases in a given time period) and Monetary (total amount spent); a valuable customer is represented by a high RFM score.
* **Churn analysis and model**: this method is used to determine which customer is likely to abandon the company, or some of its products/services; a model has been developed to
  help predict customer churn.
* **MBA**: Market Basket Analysis is a marketing technique that aims to predict the associations between products, i.e. the customer's 'basket'; it is particuralry useful to understand
  which goods tend to get buyed togheter, so the company can better its product placement or suggests more specific products and discounts to each customer, enriching its profyling.
* **Sentiment Analysis**: it's a method used to analyze the sentiment expressed by the cusotmers, usually through reviews and feedbacks, in order to understand how the customer base
 of a company perceives a product/service.

## Repository structure

This repository is structured as follows:

```
.
├── MA data                        
│   ├── tbl_addresses.csv           
│   ├── tbl_customer_accounts.csv   
│   ├── tbl_customer_reviews.csv    
│   ├── tbl_customers.csv           
│   ├── tbl_labelled_reviews.csv     
│   ├── tbl_orders.csv              
│   └── tbl_products.csv            
├── MA notebooks                   
│   ├── 1.Preprocessing.ipynb       
│   ├── 2.EDA.ipynb                 
│   ├── 3.RFM+Churn+MBA.ipynb       
│   ├── 4.Sentiment analysis.ipynb  
│   └── 5.Extra Point 1+2.ipynb     
├── README.md
└── presentation.pdf                 
```

All the necessary packages are listed at the beginning of every notebook. 


