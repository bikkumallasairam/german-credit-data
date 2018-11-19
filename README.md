# german-credit-data-classifier

 The analyzer can analyze some data collected by a bank giving a loan. The dataset consists of 1000 datapoints of categorical and numerical dataas well as a good credit vs bad credit metric which has been assigned by bank employees.The code in this repository contains a randomforest models to try to predict the credit rating that a bank employee would assign given some datapoints.

# Dataset
The dataset consists of 1000 datatpoints each with 20 variables (dimensions) 7 are numerical and 13 are categorical. The categorical data is encoded according to terms which have meaning to the bankers such as current employment timeframe:

A71 : unemployed
A72 : ... < 1 year
A73 : 1 <= ... < 4 years
A74 : 4 <= ... < 7 years
A75 : .. >= 7 years
Or what kind of housing the person has:

A151 : rent
A152 : own
A153 : for free
Other data provided in the dataset contains numerical information such as:

Duration of the loan in months
Credit amount
Age in years
See the Description file attached to the repository for further details on the data. Source:https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29

# classifier
Random forest is a type of supervised machine learning algorithm based on ensemble learning. Ensemble learning is a type of learning where you join different types of algorithms or same algorithm multiple times to form a more powerful prediction model. The random forest algorithm combines multiple algorithm of the same type i.e. multiple decision trees, resulting in a forest of trees, hence the name "Random Forest". The random forest algorithm can be used for both regression and classification tasks


