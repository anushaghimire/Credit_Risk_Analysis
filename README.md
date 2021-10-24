# Credit_Risk_Analysis

# Overview
Use the following machine learning models to predict credit card risk analysis:
- Oversampling
  - Naive Random Oversampling
  - SMOTE Oversampling
- Undersampling
- Combination (Over and Under) Sampling
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

 **Data used : LoanStats_2019Q1.csv**


## Purpose: 
The purpose of the study is to apply machine learning to solve a real-world challenge: credit card risk. I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. I Used the credit card credit dataset from LendingClub, a peer-to-peer lending services company, then I oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 


## Results:  
- **Credit Risk Resampling Techniques**
- Naive Random Oversampling<img width="843" alt="Screen Shot 2021-10-24 at 1 26 16 PM" src="https://user-images.githubusercontent.com/85364095/138611629-83b393b0-203d-4d99-8623-89fb82971d23.png">





- SMOTE Oversampling

<img width="825" alt="Screen Shot 2021-10-24 at 1 27 44 PM" src="https://user-images.githubusercontent.com/85364095/138611674-e6558d9b-1245-4130-bd5b-29ea3ce0e625.png">

- Undersampling


<img width="825" alt="Screen Shot 2021-10-24 at 1 27 44 PM" src="https://user-images.githubusercontent.com/85364095/138611719-1a0c0a29-8553-4f2d-9625-0c2899714862.png">

- Combination (Over and Under) Sampling
<img width="740" alt="Screen Shot 2021-10-24 at 1 29 05 PM" src="https://user-images.githubusercontent.com/85364095/138611756-664f36cc-6c09-4983-93f1-2f68e635754e.png">

- Ensemble Learners
- Balanced Random Forest Classifier
<img width="729" alt="Screen Shot 2021-10-24 at 1 31 25 PM" src="https://user-images.githubusercontent.com/85364095/138611800-1358b3ba-ec70-4ebc-8361-d1a65e8a03a7.png">

- Easy Ensemble AdaBoost Classifier

<img width="756" alt="Screen Shot 2021-10-24 at 1 32 36 PM" src="https://user-images.githubusercontent.com/85364095/138611824-b21812a4-646f-421b-a58d-a6a64b4bd307.png">




- 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
