# TitleToBeDefined - Jordi Bayer
### (Ironhack Data Analytics Full Time)

## Overview

Electronic payments are growing so fast 11% from 2016 to 2017 (Mckinsey study graphic here). So I'm really worried about the electronic payments field and I want to create an algorithm to predict if a transaction is a fraud or not. I'm going to focus on the credit card fraud (but I think that replicate the process in mobile payment would be something similar).
I want to be able to build a model that's able to classify correctly (True positives and true negatives in the confusion matrix) the 95% of the sample.

## Data Preparation

Overview:
I found this dataset in [Kaggle] (https://www.kaggle.com/ananta/credit-card-data) uploaded by Anant Prakash Awasthi. The dataset's a dummy Credit Card Database with 4 tables (need to define the type of each variable):
⋅⋅* **Card Base:** Contains info about the Card Number, Card Family (Premium, Gold, and Platinum), Credit Limit, and Customer ID
⋅⋅* **Customer Base:** Contains info about the Customer ID, Age, Customer Segment, Customer Vintage Group (VG1 for Diamond, VG2 for Platinum, VG3 for Gold)
⋅⋅* **Transaction Base:** Contains info about all the Transaction ID, Transaction Date, Credit Card ID, Transaction Value and  Transaction Segment.
⋅⋅* **Fraud Base:** Contains info about the Transaction ID and if the transaction is flagged as fraud.

## Data Ingestion & Database

If you downloaded a dataset (either public or private), describe where you downloaded it and include the command to load the dataset.
If you obtain the data via API/web scraping, provide the scripts.
Provide a schema of your tables.
Data Wrangling and Cleaning

Your full process of data wrangling and cleaning.

Document your workflow and thinking process.

## Data Analysis

Overview the general steps you will go through to analyze your data in order to test your hypothesis.
Document each step of your data exploration and analysis.
Print charts to demonstrate the effect of your work. Charts make your presentation look good too.
If you use ML in your final project, also describe your feature selection process.

## Model Training and Evaluation

Train your ML model, produce results, and evaluate.
This is an iterative process. Try your best to improve your model performance by:
Try different models and select one that is the simplest yet produce the best result.
Try advanced techniques and see if they improve the result.

## Conclusion

Summarize your data analysis result.
State your conclusion of your hypothesis testing.
Interpret your findings in terms of the human-understandable question you try to answer.
What are the next steps?

