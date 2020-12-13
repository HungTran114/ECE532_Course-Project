# ECE532_Course-Project

1. Project Dataset: 
My chosen dataset for this project is: “Human Activity Recognition Using Smartphones” from UCI Repository. 

In this dataset, a group of 30 volunteers perform each perform six activities: walking, walking upstairs, walking downstairs, sitting, standing, and laying while wearing a smartphone. The smartphone’s accelerometer and gyroscope will capture 3-axial linear acceleration and 3-axial angular velocity at a rate of 50Hz. 
For each record, a 561-feature vector is created by calculating variables from the time and frequency domain. The detailed pre-processing is detailed in this link:
https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones

In total, there are 10929 rows of data with 563 attributes:
- 561-feature vector
- Subject: identifier of the volunteer
- Activity label: one of six (walking, walking upstairs, walking downstairs, sitting, standing, and laying)
The data has been separated into a 70% training set and 30% test set.

2. Algorithms: 
The algorithms that I use with this dataset are: 
- linear regression, 
- KNN,
- SVM kernel regression
These algorithms will be trained on the training set and compare with each other based on the accuracy on the test set. You can find the necessary ipynb file in this folder. The two data file (train.csv and test.csv) can be found in the file input.zip.


