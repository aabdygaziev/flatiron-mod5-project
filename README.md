# FLATIRON MODULE 5 PROJECT
____
This project's aim is to build an algorithm that uses classification techniques to predict whether a person has or has not a cardivascular disease. 

**Models Used:** Logistic Regression, Decision Trees, Naive Bayes, Support Vector Machine, KNeighbors Classifier, Random Forest, ExtraTreesClassifier and AdaBoost.

## The Data
___
The Dataset is downloaded from Kaggle. This data is stored in [cardio_train.csv](https://github.com/aabdygaziev/flatiron-mod5-project) file. Data cleaning, data processing and modelling are in the [jupyter notebook](https://github.com/aabdygaziev/flatiron-mod5-project/blob/master/cardio.ipynb). 

## Packages to install
___
This project uses variety of tools for the data cleaning and modelling.Please make sure you have this packages to run the algorithm.
* Pandas, (conda install -c anaconda pandas)
* scikit-learn, (conda install -c anaconda scikit-learn)
* Matplotlib, (conda install -c conda-forge matplotlib)
* Searborn, (conda install -c anaconda seaborn)

## Problems & Solutions
___
Throughout the project I faced several problems. One of the main problems is that implemention of models such as SVM takes a lot of time,  fit time scales at least quadratically with the number of samples and may be impractical beyond tens of thousands of samples. In this case, I used [LinearSVM](https://scikit-learn.org/stable/modules/generated/sklearn.svm.LinearSVC.html) and [SGDClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.SGDClassifier.html#sklearn.linear_model.SGDClassifier) to save time.
