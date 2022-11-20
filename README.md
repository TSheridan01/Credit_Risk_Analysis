# Credit_Risk_Analysis



## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

I was tasked with using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. After that I was asked to evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


## Summary 

When working with machine learning and determing accuracy, the highest accuracy between 0 and 1 and is closest to 1 is the best for our model. From the given data, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were under the threshold of 80% which is determined as unreliable data for our stakeholders. 

EasyEnsembleClassifier

Accuracy Score: 93%
Precision Score: 99%
Recall Score: 94%

