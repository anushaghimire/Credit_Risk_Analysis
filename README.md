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
- Naive Random Oversampling
  - The accuracy score is 65% which means the classifier is correct only 65% with the model.
  -  From our results, the precision for the high-risk is low about 1% and for low-risk precision is high 100%.
  -  The recall value for high-risk is slightly lower than the low-risk.
<img width="843" alt="Screen Shot 2021-10-24 at 1 26 16 PM" src="https://user-images.githubusercontent.com/85364095/138611629-83b393b0-203d-4d99-8623-89fb82971d23.png">





- SMOTE Oversampling
  - The balanced accuracy score is 65%.
  - From our results, the precision for the high-risk is low about 1% and for low-risk precision is high 100%.
  - The recall value for high-risk is higher than the low-risk.

<img width="760" alt="Screen Shot 2021-10-24 at 1 50 47 PM" src="https://user-images.githubusercontent.com/85364095/138612477-cbba7281-aa1c-4964-9b00-dc4b6b23887e.png">


- Undersampling(ClusterCentroids resampler)




- Combination (Over and Under) Sampling


- Ensemble Learners
- Balanced Random Forest Classifier
  - The balanced accuracy score is 79%.
  - From our results, the precision for the high-risk is low about 3% and for low-risk precision is high 100%.
  - The recall value for high-risk is lower(0.7) than the low-risk(.87).
<img width="722" alt="Screen Shot 2021-10-24 at 2 11 15 PM" src="https://user-images.githubusercontent.com/85364095/138613111-d03cd5b4-593d-4806-a3f5-77611d591561.png">

- Easy Ensemble AdaBoost Classifier




<img width="791" alt="Screen Shot 2021-10-24 at 2 09 21 PM" src="https://user-images.githubusercontent.com/85364095/138613055-291596d0-2ecd-4301-af56-24db2c35d0e2.png">


- 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
