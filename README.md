# ECE532_Course-Project

1. Project Dataset: 
I will use the dataset “Human Activity Recognition Using Smartphones” from UCI Repository (the .csv version is from Kaggle).
https://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions
https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones/version/2
Dataset: “Human Activity Recognition Using Smartphones” from UCI Repository, 10929 rows of data with 563 attributes, multiclass classification into 6 different activities performed (walking, walking upstairs, walking downstairs, sitting, standing, laying)

Notes: 
The dataset was built from the recordings of 30 study participants performing activities of daily living while carrying a waist-mounted smartphone with embedded inertial sensors. The objective is to classify activities into one of the six activities performed (walking, walking upstairs, walking downstairs, sitting, standing, laying). 
Notes: The data has been pre-processing as followed:
Using the phone’s embedded accelerometer and gyroscope, the dataset captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. 
For each record in the dataset the following is provided:
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope.
- A 561-feature vector with time and frequency domain variables.
- Its activity labels.
- An identifier of the subject who carried out the experiment.

2. Algorithms: 
The algorithms that I am planning to use with this dataset are: 
- linear regression, 
- KNN,
- SVM kernel regression
These algorithms will be trained on the training set and compare with each other based on the accuracy on the test set. You can find the necessary ipynb file in this folder. The two data file (train.csv and test.csv) can be found in the file input.zip.


