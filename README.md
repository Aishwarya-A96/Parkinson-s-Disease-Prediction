# Parkinson-s-Disease-Prediction
To build a model which predicts whether a patient is suffering from Parkinson’s disease or not using XGBClassifier
This dataset contains 195 rows and 24 columns
Separating the whole dataset into dependent variable( y which is also known as labels) and independent variable( x which is also known as features) 
I have done feature scaling using minmaxscalar and made the values ranges from -1 to 1
The dataset is divided into training set and test set
Training set contains 156 rows and 22 columns
Test set contains 39 rows and 22 columns
I fitted the model using XGB Classifier and found the accuracy score to be 94.87%
I evaluated the model using confusion matrix and found that two persons were misclassified
1 person in false positive indicate that the person is predicted to have parkinson's disease but he/she does not possess that disease 
1 person in false negative indicate that the person is predicted that they dont have parkinson's disease but he/she actually possess that disease
Precision score,Recall score and f1score was found to be 96.5%
