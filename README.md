# Project Overview

The Starbucks project was my capstone project for the Udacity Machine Learning Engineer Nanodegree. This data was provided by Starbucks to simulate their customers and transactions to see if there are better approaches to sending customers specific promotional deals.

# Installation

+ Python version 3.7
+ Libraries:
    * Pandas
    * Numpy
    * Matplotlib
    * Seaborn
    * Scikit learn

# File Description

## 1) Data files

### profile.json 
Rewards program users (17000 users x 5 fields)

+ gender: (categorical) M, F, O, or null
+ age: (numeric) missing value encoded as 118
+ id: (string/hash)
+ became_member_on: (date) format YYYYMMDD
+ income: (numeric)

### portfolio.json
Offers sent during 30-day test period (10 offers x 6 fields)

+ reward: (numeric) money awarded for the amount spent
+ channels: (list) web, email, mobile, social
+ difficulty: (numeric) money required to be spent to receive reward
+ duration: (numeric) time for offer to be open, in days
+ offer_type: (string) bogo, discount, informational
+ id: (string/hash)
### transcript.json
Event log (306648 events x 4 fields)

+ person: (string/hash)
+ event: (string) offer received, offer viewed, transaction, offer completed
+ value: (dictionary) different values depending on event type
    * offer id: (string/hash) not associated with any "transaction"
    * amount: (numeric) money spent in "transaction"
    * reward: (numeric) money gained from "offer completed"
+ time: (numeric) hours after start of test

## 2) Starbuck_Capstone_notebook.ipynb
Jupyter Notebook that shows the start to finish of the this project. This starts with data cleanup and exploration, top level statsitics of customers and their transactions, and cluster analysis for better approaches of sending customers promotions.


```python

```
