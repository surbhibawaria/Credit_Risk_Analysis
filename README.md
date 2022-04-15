# Credit_Risk_Analysis

## Overview of the Analysis

A peer to peer lending services company wants to use machine learning to predict credit risk. Management believes that this will provide a quicker and more reliable loan experience. It also believes that machine learning will lead to a more accurate identification of good candidates for loans which will lead to lower default rates. The company wants to build and evaluate several machine learning models or algorithms to predict credit risk. Techniques such as resampling and boosting is to be used to make the most of the models and data. Once it is designed and implemented, their performances are evaluated to see how well the models predict data.

### Purpose of this Analysis

The purpose of this analysis is to to apply machine learning to solve a real-world challenge: credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, the purpose here is to employ different techniques to train and evaluate models with unbalanced classes using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversampling the data using the RandomOverSampler and SMOTE algorithms, and undersampling the data using the ClusterCentroids algorithm. Then, to use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, to compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once it's done, to evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results

- ### Oversampling

#### Balanced Accuracy Score

<img width="1027" alt="Screen Shot 2022-04-15 at 3 12 32 PM" src="https://user-images.githubusercontent.com/95826875/163622541-36f1d9b3-91ab-4cd1-8d08-ab83ea718f4a.png">

#### Imbalanced Classification Report

<img width="1023" alt="Screen Shot 2022-04-15 at 3 14 32 PM" src="https://user-images.githubusercontent.com/95826875/163622708-0032427e-184a-4bb1-9495-7d7488674f4f.png">

- ### SMOTE Oversampling

#### Balanced Accuracy Score

<img width="1025" alt="Screen Shot 2022-04-15 at 3 20 39 PM" src="https://user-images.githubusercontent.com/95826875/163623246-bc4a9687-40be-43ed-b9f7-3d6819b9afb2.png">

#### Imbalanced Classification Report

<img width="1021" alt="Screen Shot 2022-04-15 at 3 20 53 PM" src="https://user-images.githubusercontent.com/95826875/163623261-054cfb5e-40e7-4f7d-839c-4c65f4d68d22.png">

- ### Undersampling

#### Balanced Accuracy Score

<img width="1024" alt="Screen Shot 2022-04-15 at 3 21 51 PM" src="https://user-images.githubusercontent.com/95826875/163623347-dd9cbfa4-d497-438d-8dc4-83ecb1a8a20b.png">

#### Imbalanced Classification Report

<img width="1024" alt="Screen Shot 2022-04-15 at 3 22 05 PM" src="https://user-images.githubusercontent.com/95826875/163623351-cb0c978b-4957-4230-a520-a8ee93a1b427.png">

- ### Combination (Over and Under) Sampling

#### Balanced Accuracy Score

<img width="1025" alt="Screen Shot 2022-04-15 at 3 23 06 PM" src="https://user-images.githubusercontent.com/95826875/163623478-730df536-6b20-4c3f-964e-035182f292c2.png">

#### Imbalanced Classification Report

<img width="1026" alt="Screen Shot 2022-04-15 at 3 23 31 PM" src="https://user-images.githubusercontent.com/95826875/163623496-9daa7720-bcc9-47b2-8236-63a7646cb565.png">

- ### Balanced Random Forest Classifier

#### Balanced Accuracy Score

<img width="1025" alt="Screen Shot 2022-04-15 at 4 00 44 PM" src="https://user-images.githubusercontent.com/95826875/163626609-9d711274-80f8-461d-95ad-42e11ac2b7cb.png">

#### Imbalanced Classification Report

<img width="1026" alt="Screen Shot 2022-04-15 at 4 00 58 PM" src="https://user-images.githubusercontent.com/95826875/163626620-e53dcee2-3193-4855-af5e-90624ffdffe2.png">

- ### Easy Ensemble AdaBoost Classifier

#### Balanced Accuracy Score

#### Imbalanced Classification Report



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
