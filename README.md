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
- SVM,
- neural networks
These algorithms will be trained on the training set and compare with each other based on the accuracy on the test set.

3. Update 1:
My first algorithm is linear regression. So, my plan is to build 6 different models and then choose the predicting the label for which the corresponding classifier reports the highest confidence score.
I tried least square and ridge regression for my model. As I was getting very high singular value, I think regularization is necessary. I will try LASSO after regularization, and maybe some cross validation to see which value of lambda work best.
However, I am getting really high error rate, which makes me think that linear regression may not be the best way for this problem. 

4. Update 2: 
So, I found out that multi-class classification, logistic regression is a much better way instead of linear regression by applying it repeatedly as one-vs-all classification, because logistic regression predict results that are interpreted as class probabilities.
I am studying sklearn package to build logistic regression and SVM model. 
I am planning to use PCA from sklearn to pick out meaningful features. Then potentially build a logistic regression model from the new matrix created by PCA.
Also, I am reseaching the GridSearchCV function of sklearn package to understand how to tune hyperparameter. 

I have updated the files on my GitHub.
Going ahead, my plan will be:
- Finish up and understand logistic regression and SVM using sklearn
- Neural network: I think this will fit well with the non-linearity nature of my dataset.


