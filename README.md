# Unit-11---Risky-Business

![risk](https://www.summitcpa.net/hs-fs/hubfs/risk%20or%20reward%20animation.gif?width=300&name=risk%20or%20reward%20animation.gif)
Background

In this assignment I had to  build and evaluate several machine learning models to predict credit risk using data you'd typically see from peer-to-peer lending services. I had to employ different techniques for training and evaluating models with imbalanced classes. I used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:




## Instructions

 ### Resampling
- I used the imbalanced learn library to resample the LendingClub data and build and evaluate logistic regression classifiers using the resampled data.
To begin:


1. I had to read the CSV into a DataFrame.


2. I split the data into Training and Testing sets.


3. I scaled the training and testing data using the StandardScaler from sklearn.preprocessing.


4. I used the provided code to run a Simple Logistic Regression:

5. I fit the logistic regression classifier.
6. I calculated the balanced accuracy score.
7. I displayed the confusion matrix.
8. I also printed the imbalanced classification report.



My Next Steps were :


1. Oversample the data using the Naive Random Oversampler and SMOTE algorithms.


2. Undersample the data using the Cluster Centroids algorithm.


3. Over- and undersample using a combination SMOTEENN algorithm.


For each of the above I had to :


1. Train a logistic regression classifier from sklearn.linear_model using the resampled data.


2. Calculate the balanced accuracy score from sklearn.metrics.


3. Display the confusion matrix from sklearn.metrics.


4. Print the imbalanced classification report from imblearn.metrics.


I then had to answer provided questions







### Ensemble Learning
In this section, I had to train and compare two different ensemble classifiers to predict loan risk and evaluate each model. I used the Balanced Random Forest Classifier and the Easy Ensemble Classifier. 
- My steps were 

1. Read the data into a DataFrame using the provided starter code.


2. Split the data into training and testing sets.


3. Scale the training and testing data using the StandardScaler from sklearn.preprocessing.


For each of the above I had to :


1. Train the model using the quarterly data from LendingClub provided in the Resource folder.


2. Calculate the balanced accuracy score from sklearn.metrics.


3. Display the confusion matrix from sklearn.metrics.


4. Generate a classification report using the imbalanced_classification_report from imbalanced learn.


5. For the balanced random forest classifier only, I printed the feature importance sorted in descending order (most important feature to least important) along with the feature score.

I then had to answer provided questions

![pic](./credit-risk.jpg)
