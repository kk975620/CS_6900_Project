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
### Status
* KNN classification has been implemented on the data. The accuracy achieved with KNN when k =10 is 23.7%. 
* The next step in the project would be to analyse the data to improve the accuracy of KNN algorithm and make better predictions. 
* Short term goal is to implement SVM as a One-Vs-Many classifier. 
* Long term goal is to find the list of features ranked by their importance.
