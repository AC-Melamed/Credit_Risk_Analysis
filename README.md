# Credit_Risk_Analysis

## **Overview**
This project constitutes a comparative assesment of various machine learning techniques and their relative utilities for the purpose of assessing credit card loan risk based on a historical dataset provided by a fictional peer-to-peer lending service.

### **Purpose**
The algorithms designed and deployed for this project were selected on the premise that credit risk as a statistical problem entails a notable degree of 'unbalanced classification', i.e., a data landscape wherein non-risky loans are assumed to significantly outnumber risky loans.  Being necessarily trained on unbalanced classes, the models employed for this project were therefore specificially chosen so as to best compensate for such imbalances so that they might provide the company with an accuarate predictive model of the risks involved in granting future credit loans.

--------------------------------
## Results
The results of this project's comparative analyses were as follow:

### **1) Oversampling Techniques**
evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm.

resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

- RandomOverSampler
- SMOTE

### **2) Combintation Over-Undersampling Technique**
combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1

resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

- SMOTEENN

### 3) **Ensemble Techniques**
train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. 

Using both algorithms, you’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

- BalancedRandomForestClassifier
- EasyEnsembleClassifier

--------------------------------

## **Summary**
 

### Recommendation for Alternative Model
After some additional exploration, including experimentation with increased epoch lengths for the model training period, it appears that the implementation of a random forest classifier would potentially increase the accuracy of the desired predictions for this dataset.  This is because, as was observed when the training period epochs were doubled or even tripled without any significant increase in accuracy, the risk of overfitting for this dataset seems low.  That makes it a possibly ideal fit for random forest classification, which takes advantage of multiple decision trees as a means of resolving issues with accurate classification. 
