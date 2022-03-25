# CS_6900_Project
## Topic
Finding Important features for distinguishing structures using scGAM.
## Problem being analysed
Can scGAM be used to determine important features in a cell?
## Table of Contents
1. General Info
2. Technologies
3. Setup
4. Status
### General Info
K-Nearest Neighbor and Support vector Machine (One-vs-Rest Multi class classification) can be used for classifying features ranked by importance.
### Technologies
Python 3.7
#### Libraries
* numpy
* matplotlib
* pandas
### Setup
To setup this project, clone this repositiory to your local and run it using python
### Status Update
#### KNN Classifier
* KNN classification has been implemented on the data. The accuracy achieved with KNN when k =10 is 23.7%. 
* Based on my findings, extracting features by their importance is not possible. 
#### SVM One Vs Many Classifier
* SVM One Vs Many Classifier has been executed. The accuracy achieved by this model is 23% as well.
### Next Steps
* The next step in the project would be to find better techniques for ranking features by their importance. 
* Technique like Decision Tree Feature Importance can be used. Eg: Classification and Regression Trees(CART) and XGBoost Feature Importance. 
% 
