The project is to model a group of insured that have a high chance of incurring multiple claims on their health insurance policy. The claims data is used  for this project. Random Forest, Logical Regression, Naïve Bayes were used for modeling. The project  is also to get to know how the model performance based on the change in data and different parameters

The following are the steps

Part I
•	Loaded the Claims data
•	Preprocessed the data (select input/output attributes, fill missing values, spit into training/testing, etc.)
•	Created logistic regression and random forest models on training data
•	Compared AUC of the model applied to training data and testing data
•	Predicted if the patients are likely to be high utilizers in year 2 using sample data 

Part II
•	Created a plot that shows performance (AUC) of random forest models (x axis) with 10, 20, 30, … 200 (y axis) on training and testing data 
•	Ranked input attributes in the data. Created  plot that shows dependency between number of selected top attributes (x axis) and AUC of learned model (y axis). 
•	Created a learning curve for the data to check AUC (y axis) based on size of data (x axis).
•	Created 5 more learning curves (on one plot) for different numbers of input attributes for random forest, logistic regression, and naïve Bayes.
o	Used random selection of input attributes
o	Used ranking of attributes from question 2

Part III
•	Using the high utilization data, optimize hyperparameters for Random Forest, Logistic Regression. For each of the method at least three different hyperparameters where used.
