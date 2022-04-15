# Credit_Risk_Analysis

## Overview of the Analysis

A peer to peer lending services company wants to use machine learning to predict credit risk. Management believes that this will provide a quicker and more reliable loan experience. It also believes that machine learning will lead to a more accurate identification of good candidates for loans which will lead to lower default rates. The company wants to build and evaluate several machine learning models or algorithms to predict credit risk. Techniques such as resampling and boosting is to be used to make the most of the models and data. Once it is designed and implemented, their performances are evaluated to see how well the models predict data.

### Purpose of this Analysis

The purpose of this analysis is to to apply machine learning to solve a real-world challenge: credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, the purpose here is to employ different techniques to train and evaluate models with unbalanced classes using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversampling the data using the RandomOverSampler and SMOTE algorithms, and undersampling the data using the ClusterCentroids algorithm. Then, to use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, to compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once it's done, to evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results

- ### Oversampling

#### Balanced Accuracy Score

<img width="1024" alt="Screen Shot 2022-04-15 at 4 36 27 PM" src="https://user-images.githubusercontent.com/95826875/163629747-9f0dabf3-ac86-4799-84ab-40672bd91324.png">

#### Imbalanced Classification Report

<img width="1026" alt="Screen Shot 2022-04-15 at 4 36 46 PM" src="https://user-images.githubusercontent.com/95826875/163629753-f96907f7-9b99-41cc-b2a8-ab42df6b468d.png">

- ### SMOTE Oversampling

#### Balanced Accuracy Score

<img width="1025" alt="Screen Shot 2022-04-15 at 4 37 32 PM" src="https://user-images.githubusercontent.com/95826875/163629815-e05ddd18-166a-41a8-a970-8c5bc064569e.png">

#### Imbalanced Classification Report

<img width="1027" alt="Screen Shot 2022-04-15 at 4 37 50 PM" src="https://user-images.githubusercontent.com/95826875/163629825-32f93525-b5cc-49bc-a8fd-1c59a1fa814d.png">

- ### Undersampling

#### Balanced Accuracy Score

<img width="1021" alt="Screen Shot 2022-04-15 at 4 38 32 PM" src="https://user-images.githubusercontent.com/95826875/163629898-14f61652-37c9-4075-af27-ea05e1521378.png">

#### Imbalanced Classification Report

<img width="1022" alt="Screen Shot 2022-04-15 at 4 38 47 PM" src="https://user-images.githubusercontent.com/95826875/163629903-09a0ea4b-bdc6-4bbb-9a44-2bca05f6b7f3.png">

- ### Combination (Over and Under) Sampling

#### Balanced Accuracy Score

<img width="1024" alt="Screen Shot 2022-04-15 at 4 39 41 PM" src="https://user-images.githubusercontent.com/95826875/163629991-968a67c8-3b79-4a78-abfe-5719863f07c1.png">

#### Imbalanced Classification Report

<img width="1021" alt="Screen Shot 2022-04-15 at 4 39 55 PM" src="https://user-images.githubusercontent.com/95826875/163629996-24cf72dc-fd71-43cd-b8c7-0ce7607eeb95.png">

- ### Balanced Random Forest Classifier

#### Balanced Accuracy Score

<img width="1025" alt="Screen Shot 2022-04-15 at 4 41 38 PM" src="https://user-images.githubusercontent.com/95826875/163630146-6dd17bac-8369-4809-b114-9b7a809d2966.png">

#### Imbalanced Classification Report

<img width="1024" alt="Screen Shot 2022-04-15 at 4 42 01 PM" src="https://user-images.githubusercontent.com/95826875/163630154-62306ff5-7f7e-41f8-a9c6-cb4485b15716.png">

- ### Easy Ensemble AdaBoost Classifier

#### Balanced Accuracy Score

<img width="1023" alt="Screen Shot 2022-04-15 at 4 42 35 PM" src="https://user-images.githubusercontent.com/95826875/163630206-cff46d9f-5f04-4f6b-9f77-d5ff5c9a170b.png">

#### Imbalanced Classification Report

<img width="1022" alt="Screen Shot 2022-04-15 at 4 42 45 PM" src="https://user-images.githubusercontent.com/95826875/163630215-e275adda-ef53-4887-8726-ca5bed1f65f7.png">

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
