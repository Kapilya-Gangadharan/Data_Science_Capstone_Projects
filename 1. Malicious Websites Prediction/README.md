**Malicious Websites Prediction**

## Dataset

The file dataset.csv has been used from Kaggle repository. The dataset consists of website details like url, server, Content Length, counrty, date of updation, Ip's, remote Ip,s etc.

----


## Install Necessary Modules:

Open your [![Anaconda](https://img.shields.io/badge/Anaconda-342B029.svg?&style=flate&logo=anaconda&logoColor=white)](https://www.anaconda.com/products/individual) Prompt <img alt="propmt" src="https://img.shields.io/badge/-__-000000?style=flat-square&logo=Plex&logoColor=white"> and type and run the following command (individually):

 -       pip install pandas
       
 -       pip install numpy  
 
 -       pip install matplotlib
 
 -       pip install --upgrade pip
 
 -       pip install xgboost

Once Installed now we can import it inside our python code.

----

## Model Descriptione 

The Malicious Websites are predicted using XGBoost Classifier model. Classifer worked better than the Regressor in accuracy and accuracy_score. 

----

## Code Description:

The model is scripted in pyton. The steps followed in the model is as mentioned below

1. Import the libraries
2. Import the dataset and split the dependednt and independent variables
3. Perform data cleaning
   a. clean up column names
   b. remove non-numeric columns
   c. Take care of the missing data
4. Perform XGBoost Classifer Model  
   a. Split the dataset into Training set and Test set
   b. Split the Training data into inputs & output
   b. Train XGBoost on the Training set
   c. split testing data into inputs & output
   d. Perform predictions & actual values, from test set
5. Plot the confusion Confusion Matrix
6. Identify the accuracy Score
7. Applying k-Fold Cross Validation
   a. Identify the Accuracy 
   b. Standard Deviation
----
