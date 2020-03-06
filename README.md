
Advertising Project using Logistic Regression, Decision Tree Classifier and Random Forest Classifier

Introduction

The goal of this project is to utilize machine learning algorithms to classify whether or not a particular internet user clicked on an Advertisement on a company website.

Datasets
In this project, I have used some fake advertising data set, indicating whether or not a particular internet user clicked on an Advertisement. I have worked with three Machine learning algorithms Logistic Regression, decision Tree classifier and Random Forest classifier to create a model that predicts accurately whether or not users will click on an ad based off the features of that user.
This data set contains the following features:
1.	'Daily Time Spent on Site': consumer time on site in minutes
2.	'Age': cutomer age in years
3.	'Area Income': Avg. Income of geographical area of consumer
4.	'Daily Internet Usage': Avg. minutes a day consumer is on the internet
5.	'Ad Topic Line': Headline of the advertisement
6.	'City': City of consumer
7.	'Male': Whether or not consumer was male
8.	'Country': Country of consumer
9.	'Timestamp': Time at which consumer clicked on Ad or closed window
10.	'Clicked on Ad': 0 or 1 indicated clicking on Ad

Machine Learning Algorithm Process

The machine learning algorithm process highlights the steps taken to get the models up and running from start to end. The machine learning algorithm process includes:

1.	Load data into Jupyter notebook and perform exploratory analysis.
2.	Used seaborn to explore the data
3.	Split the data into input and output columns.
4.	Since the data was already in standard form I didn’t do any preprocessing 
5.	Pass the data into grid search Logistic Regression, Decision Tree classifier and RandomForest classifier
6.	Evaluate the performance of the models using confusion matrix and classification report.

Code for project can be found on my GitHub

Results

The results of the 3 machine learning models evaluated are as follows:
1.	Logistic regression with Precision, Recall, F1 score as 91%, did not performed well as compared to other models.
2.	Decision tree with Precision, Recall, F1 score as 94%
3.	Random forest with Precision, Recall, F1 score as 95%

Conclusion

Random forest classifier performed best with Precision, Recall, F1 score as 95%. Random forest classifier is a combination of decision trees and is protected from the problem overfitting due to it ensemble method. This project was an interesting to learn from and the outcomes from the result was used to further my knowledge in machine learning.

¥	Precision – What percent of your predictions were correct?
¥	Recall – What percent of the positive cases did you catch?
¥	F1 score – What percent of positive predictions were correct?

