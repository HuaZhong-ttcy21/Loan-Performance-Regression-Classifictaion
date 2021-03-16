# Loan-Performance-Regression-Classifictaion
(Repo for a machine learning proejct I completed during my master's study in JHU. Through this project, I got a better understanding of the process of building regression and classification models and some details of data processing) 

The aim of this project is to develop prediction models for the length of time that Federal National Mortgage Association(FNMA) holds a mortgage loan and for predicting foreclosure of a loan, based on information available to FNMA at the time the loan is put on their books. The data used is a portion of the single family loan
portfolio for FNMA originating in the second quarter of 2000.


### Loans Data set
The original raw data set is stored in `TRAIN.csv` with 200,000 rows and 108 columns. See `AbbreviatedColumnNames.txt` and	`ColumnNames.txt` to know more about the features of the data set.
### 1st Part -Regression
The response for the regression model is `'MONTHS'`, the number of months until the mortgage is taken off the books due to foreclo-sure, prepayment, etc.. The mertic used here is `Mean Absolute Value`. Since I completed features selection that is also essential to the classification in this part , this regression part should be read first. 
### 2nd part -Classification
The response for the classification model is `'FORCLOSED'`, a boolean variable that indicates whether the mortgage foreclosed (True) or not (False). The mertic used here is overall `Accuracy`. However I sacrifice accuray a bit to imporve the `True Positive Rate`, which I think is more significant in this problem. 



