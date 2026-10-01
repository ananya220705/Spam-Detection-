# Spam Ham Detection Project


## Problem statement

In this data science project, a machine learning system is built which will be able detect whether any text is spam or not. Spam means the text which are generally used when it's a spam. Ham means the text which is not a spam and it's clean. In our real life we often see the spam messages, be it in mails or in sms. So in this project, a system is built which will detect the spam and ham texts and will be classifying them as spam and ham. 

## Solution Proposed

Now the question is how to dynamically predict the type of the text ?. One of the approaches which we can use of machine learning approach, where we can detect the text based on the texts we have and predict the text type based on the domain knowledge and leverage previous text data to predict the text type.



## Tech Stack Used

1. Python
2. FastAPI
3. Machine learning algorithms
4. Docker
5. MongoDB

## Infrastructure required

1. AWS S3
2. AWS EC2
3. AWS ECR
4. Github Actions




## Models Used

* [MultinomialNB](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html)
* [GaussianNB](http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html)

* [SVC](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)

From these above models after hyperparameter optimization one model is going to be used by the system itself.

* GridSearchCV is used for Hyperparameter Optimization in the pipeline.

## `src` is the main package folder which contains

**Components** : Contains all components of Machine Learning Project

- Data Ingestion
- Data Validation
- Data Transformation
- Model Trainer
- Model Evaluation
- Model Pusher

**Custom Logger and Exceptions** are used in the Project for better debugging purposes.

## Conclusion

- This Project can be used in real-life by Users.
