# Project Overview
The idea of this project is to gather insights about customer behavior. The idea is to gather insights of how customers respond to differnt offers that they receive. There are three different offer types: discount, BOGO (buy one get one free) and merely informational offers. THe task was to determine if there is a correlation between demographic features and the success rate of different offer types.


## Input Data
The data for this project consists of three JSON files:
1.	portfolio.json: Contains offer IDs and metadata about each offer (duration, type, difficulty, reward, and channels).
2.	profile.json: Contains demographic data for each customer (age, gender, income, and membership date).
3.	transcript.json: Contains records for transactions, offers received, offers viewed, and offers completed.

## Baseline Model 
The baseline model for this project is a simple logistic regression model. 


# Problem Statement
The problem to be solved is determining which demographic groups respond best to different types of Starbucks offers. This involves analyzing customer transaction, demographic, and offer data to identify patterns and relationships. By solving this problem, Starbucks can improve its targeted marketing strategies and increase the effectiveness of its offers.


# Metrics
The evaluation metrics used in this project are: 

1. Accuracy: Accuracy measures the proportion of correct predictions (both true positives and true negatives) out of all predictions made. It is a widely used metric that gives a general sense of how well the model performs. However, accuracy can be misleading if the dataset is imbalanced, as it might give high scores when the model only predicts the majority class well.
2. F1 Score: F1 score is the harmonic mean of precision and recall. It is used when we need to consider both false positives and false negatives equally. F1 score is particularly useful when dealing with imbalanced datasets, as it provides a balanced measure of the model's performance.
3. Recall: Recall (also known as sensitivity or true positive rate) measures the proportion of actual positive cases that the model correctly identifies as positive. It is important in situations where we want to minimize the number of false negatives (e.g., not identifying a customer who would respond well to an offer).
4. Precision: Precision measures the proportion of positive predictions that are actually correct. It is important in situations where we want to minimize the number of false positives (e.g., not targeting a customer who would not respond well to an offer).

# Links for Porject:
## - Code of the Project can be found here: 
https://github.com/ljdrg/capstone_starbucks_ml/blob/master/Starbucks_Capstone_notebook.ipynb

## - Reviewed Project Proposal can  be found here: 
https://github.com/ljdrg/capstone_starbucks_ml/blob/master/ML_Nanodegree_Project_Proposal.pdf

## - Project Report can be found here:
