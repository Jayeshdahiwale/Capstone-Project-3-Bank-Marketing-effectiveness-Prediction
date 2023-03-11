# Capstone-Project-3-Bank-Marketing-effectiveness-Prediction
The Data is related to direct marketing campaigns(phone calls) of a Portugese banking institution.The marketing campaigns were based on phone calls. Often, more than one call to the same client, in order to access if the product(bank term deposit) would be 'YES' or not 'NO' subscribed. The classification goal is to predict if the client will subscribe to the term deposit (variable y).

## Table of Content
  * [Intorduction of Project](#project-summary)
  * [Problem Statement](#problem-statement)
  * [Data Summary and Variables](#dataset)
  * [Project Structure](#project-structure)
  * [Conclusion](#conclusion)

## Introduction of Project
The Data is related to direct marketing campaigns(phone calls) of a Portuguese banking institution.The marketing campaigns were based on phone calls. Often, more than one call to the same client, in order to access if the product(bank term deposit) would be 'YES' or not 'NO' subscribed. The classification goal is to predict if the client will subscribe to the term deposit (variable y).
Term Deposit
* A term deposit is a type of deposit account held at a financial institution where money is locked up for some set period of time.
* Term deposits are usually short-term deposits with maturities ranging from one month to a few years.


## Problem Statement
* Using the given dataset and developing a ML model out of it with TARGET:Deposit (YES/NO) For Classifying a new customer based on given features and also Determining the most relevant features of classification

* We need to classify the customers with very good accuracy so that organization can only contact those customers which having high chances of subscribing to the term deposit.

## Data Summary and Variables

1. Age - (numeric) Age of the customer
2. Job - (Categorical) Represents the diferent types of Jobs. eg. {'Admin','BlueCollar','Entrepreneur','Housemaid','Management','Retired'} etc.
3. Marital - (Categorical) {Divorced, Married, Single,Unknown.} Note: Divorced meaning Divorced or Widowed.
4. Education - (Categorical) '' {'Basic4y','Basic6y','Basic9y','highschool','illiterate'} etc.
5. Dafault - (Cateogircal) Has credit in default {'YES','NO', 'Unknown'}
6. Housing - (Categorical) has housing loan ? {'YES' , 'NO' , 'Unknown'}
7. loan - (Categorical) has personal loan ? {'YES' , 'NO' , 'Unknown'}
8. Contact - (Categorical) contact communication types {'Cellular', 'Telephone'}
9. Month - Categorical Last contact month of the year {'Jan' , 'Feb' , 'Mar'..........,'Dec'}
10. day_of_week - (Categorical) Last contact day of week. {'Mon','Tue','Wed','Thu','Fri','Sat'} etc.
11. Duration - (numeric) Last contact duration in seconds. Important note: This feature highly attributed to the target value Y. i.e. if the call duration is zero the output is "NO". Also after the end of the call y is obviously known. Thus this feaute should only be included for benchmark purposes and should be discarded if the intention is to build realstic predictive model.
12. Campaign - (numeric) No of contacts performed during this campaign and for this client
13. pDays - (numeric) No of days that passed by after the client was last contacted. 999 means cliendt was not contacted.
14. previous - (numeric) number of contacts performed before this campaign for this client
15. pOutcome - (categorical) Outcome of the previous campaingn. {'Success','Failure','Non-existence'}
16. y-target Variable - (Binary) has the client subscriber to a term deposit. {'Yes' , 'NO'}

```
├── README.md
├── model_pickle
│    
│
├── Classification_Capstone_Project_3.ipynb
│   ├── Project Summary
│   ├── Github Link
│   ├── Problem Statement
│   ├── Variable Explaination
│   ├── Data Loading and Data Insights
│   ├── Data Cleaning
│   ├── Data Visualization and Plotin correlation heatmap
│   ├── Feature Engineering
│   ├── Categorical Variables Encoding
│   ├── Splitting Data Into Training and Testing Sets
│   ├── Scaling Data Using Standardscaler
│   ├── Model Selection Based On Cross Val Scores (XGBoost, RandomForest)
│   ├── Model Optimal Parameter Selection Using GridCV
│   ├── Model building using above results
│   ├── Finding Most Important Features Of Classification
│   ├── Plotting Confusion Matrix
│
│
├── Classification Capstone Project 3 Report.pdf
│
├── Data 
│   ├── bank-full.csv

```

