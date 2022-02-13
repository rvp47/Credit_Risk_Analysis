# Credit_Risk_Analysis

## Overview of Analysis
The purpose of this analysis is to evaluate various machine learning algorithms and models to predict credit risk. Using a dataset provided by LendingClub, this analysis oversamples the data using the RandomOverSampler and SMOTE algorithms; undersamples the data using the ClusterCentroids algorithm; over- and undersamples using the SMOTEENN algorithm; and compares the Balanced Random Forest Classifier and Easy Ensemble Classifier model. Confusion matrices and imbalanced classification reports are generated for each model. Finally, an evaluation of the performance of these models is provided below.

Deliverable 1: Use Resampling Models to Predict Credit Risk

Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

## Results
### Deliverable 1: Use Resampling Models to Predict Credit Risk
#### Naive Random Oversampling

![Naive_Random_Oversampling_confusion_matrix](https://user-images.githubusercontent.com/90656004/153765926-ddf0ad77-9b9e-4f49-80db-e624303e889e.PNG)
![Naive_Random_Oversampling_imbalanced_classification_report](https://user-images.githubusercontent.com/90656004/153765932-4921daf1-3279-43c6-8e69-d7c6c6daab99.PNG)

#### SMOTE Oversampling

![SMOTE_Oversampling_confusion_matrix](https://user-images.githubusercontent.com/90656004/153766690-a7911864-2684-409c-8f0a-d9b445385060.PNG)
![SMOTE_Oversampling_imbalanced_classification_report](https://user-images.githubusercontent.com/90656004/153765956-fa17b298-4fc7-42e8-84ed-553a02e20a6d.PNG)

#### Undersampling

![Undersampling_confusion_matrix](https://user-images.githubusercontent.com/90656004/153765960-32535aec-2cb2-4ad7-9cbd-01a512b42476.PNG)
![Undersampling_imbalanced_classification_report](https://user-images.githubusercontent.com/90656004/153765962-48e5625b-16bc-421d-bffe-f4c2b247f58b.PNG)


### Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

![Combination_OverandUnder_Sampling_confusion_matrix](https://user-images.githubusercontent.com/90656004/153766609-9c816914-c366-45da-935a-da01095c2a44.PNG)
![Combination_OverandUnder_Sampling_imbalanced_classification_report](https://user-images.githubusercontent.com/90656004/153766612-a1e03888-1bcb-4451-9ecb-5d2450058255.PNG)


### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk


#### Balanced Random Forest Classifier

![Balanced_Random_Forest_Classifier_confusion_matrix](https://user-images.githubusercontent.com/90656004/153766670-d7d87a2f-2980-4b24-aeff-7af9167f973d.PNG)
![Balanced_Random_Forest_Classifier_imbalanced_classification_report](https://user-images.githubusercontent.com/90656004/153766675-319a1176-dfec-45c8-a27c-a1d7b5aeb96d.PNG)


#### Easy Ensemble Classifier

![Easy_Ensemble_AdaBoost_Classifier_confusion_matrix](https://user-images.githubusercontent.com/90656004/153766702-ae0d1d4d-21bc-4d05-9960-c7910a4e7752.PNG)
![SMOTE_Oversampling_confusion_matrix](https://user-images.githubusercontent.com/90656004/153766699-c8c505b0-3aa9-49f2-bd54-e933adc927d1.PNG)


## Summary
