# Lending-Club
Building a ANN model that can predict whether or nor a borrower will pay back their loan using historical data

Data collected from kaggle : https://www.kaggle.com/wordsforthewise/lending-club

Contains 2 csv files one for data and the other is specifically for feature information

Steps involved :

1) Load the Data

2) Data Preprocessing:

    a) Created a function for filling missing values based on the values of the other column
    
    b) Removed a feature for which the label is same across all of it's categories
    
    c) Removed features which are just subsets of other features
    
3) Created a Model by Grabbing a sample for training 

4) Created a Model on the whole dataset

5) Compared thier performances and Evaluated on a new data
