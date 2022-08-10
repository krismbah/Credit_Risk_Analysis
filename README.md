# Credit_Risk_Analysis

## Overview

The purpose of this project is to use the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. In order to do so, the following tasks are to be completed: 

1. Use Resampling Models to Predict Credit Risk.
2. Use the SMOTEENN Algorithm to Predict Credit Risk.
3. Use Ensemble Classifiers to Predict Credit Risk.

## Results

***Deliverable 1: Use Resampling Models to Predict Credit Risk***
Using knowledge of the imbalanced-learn and scikit-learn libraries, evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, use the oversampling RandomOverSampler and SMOTE algorithms, and then use the undersampling ClusterCentroids algorithm. Using these algorithms, resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report:

Figure 1:

![Image1](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D1.png)

Figure 1.1:

![Image1.1](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D1.1.png)

Figure 1.2:

![Image1.2](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D1.2.png)

Figure 1.3:

![Image1.3](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D1.3.png)

Figure 1.4:

![Image1.4](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D1.4.png)

Figure 1.5:

![Image1.5](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D1.5.png)


***Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk***
Using knowledge of the imbalanced-learn and scikit-learn libraries, use a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report:

Figure 2:

![Image2](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D2.png)

Figure 2.1:

![Image2.1](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D2.1.png)

Figure 2.2:

![Image2.2](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D2.2.png)

Figure 2.3:

![Image2.3](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D2.3.png)


Figure 2.4:

![Image2.4](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D2.2.png)

Figure 2.5:

![Image2.5](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D2.3.png)


***Deliverable 3: 3: Use Ensemble Classifiers to Predict Credit Risk***
Using knowledge of the imblearn.ensemble library, train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report:

Figure 3:

![Image3](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D3.png)

Figure 3.1:

![Image3.1](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D3.1.png)

Figure 3.2:

![Image3.2](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D3.2.png)

Figure 3.3:

![Image3.3](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D3.3.png)


Figure 3.4:

![Image3.4](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D3.4.png)

Figure 3.5:

![Image3.5](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D3.5.png)

Figure 3.6:

![Image3.6](https://raw.githubusercontent.com/krismbah/Credit_Risk_Analysis/main/D3.6.png)


## Summary

To summarize, this project gained access to approximately 50 datasets. Each one containing reviews of a specific product, from clothing apparel to wireless products. Choosing one of these datasets (electronics), PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, PySpark was also used to determine if there is any bias toward favorable reviews from Vine members in your dataset. The following summary is to be submitted to the SellBy stakeholders:

Credit Risk Resampling w/ Oversampling:

1. An accuracy score of .
2. A precision score of .
3. A recall/sensitivity of .
4. And a F1 score of .

Credit Risk Resampling w/ Oversampling:

1. An accuracy score of .
2. A precision score of .
3. A recall/sensitivity of .
4. And a F1 score of .

Credit Risk Resampling w/ Oversampling:

1. An accuracy score of .
2. A precision score of .
3. A recall/sensitivity of .
4. And a F1 score of .

Credit Risk Resampling w/ Oversampling:

1. An accuracy score of .
2. A precision score of .
3. A recall/sensitivity of .
4. And a F1 score of .

Credit Risk Resampling w/ Oversampling:

1. An accuracy score of .
2. A precision score of .
3. A recall/sensitivity of .
4. And a F1 score of .

Credit Risk Resampling w/ Oversampling:

1. An accuracy score of .
2. A precision score of .
3. A recall/sensitivity of .
4. And a F1 score of .



