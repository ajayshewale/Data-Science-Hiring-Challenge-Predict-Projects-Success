# Data-Science-Hiring-Challenge-Predict-Projects-Success (Rank - 54 )
This repository contains solution for Data Science Hiring Challenge (Jan 16, 2018, 12:00 PM IST - Jan 29, 2018): Predict Project's Success.

Hackerearth Problem Link: https://www.hackerearth.com/challenge/hiring/data-science-hiring-challenge/machine-learning/funding-successful-projects-c40d55cb-92e5b384/


## Problem Statement
Kickstarter is a community of more than 10 million people comprising of creative, tech enthusiasts who help in bringing creative project to life. Till now, more than $3 billion dollars have been contributed by the members in fuelling creative projects. The projects can be literally anything – a device, a game, an app, a film etc.

Kickstarter works on all or nothing basis i.e if a project doesn’t meet it goal, the project owner gets nothing. For example: if a projects’s goal is $500. Even if it gets funded till $499, the project won’t be a success.

Recently, kickstarter released its public data repository to allow researchers and enthusiasts like us to help them solve a problem. Will a project get fully funded ?

In this challenge, you have to predict if a project will get successfully funded or not. 


## Data Description
There are three files given to download: train.csv, test.csv and sample_submission.csv The train data consists of sample projects from the May 2009 to May 2015. The test data consists of projects from June 2015 to March 2017. 

## Submission
A participant has to submit a csv file with project_id and predicted labels. Check the sample submission file for reference. Also, share your source code.



## Prerequisite

### Useful Libraries

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)


You will also need to install Jupyter Notebook:
[Jupyter Notebook Tutorial: Introduction, Setup, and Walkthrough](https://www.youtube.com/watch?v=HW29067qVWk)

Here is an excellent link to [How to run Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/running.html)


## This repository contains following files:
- Dataset (Train and Test )

     train.csv
     
     text.csv 

- Graph

- Jupyter Code

     *Predict Projects Success .ipynb
     
     
 - Notebook PDF (For visualization I uploaded PDF code of the solution)

     *Predict Projects Success .ipynb 
     
     
## Solution 
Jupyter Code file contains notebook files where coding part of the problem has been given. It also contains comments on necessary steps.


# Improve Algorithms Performance

Data pre-processing is an important step that can be required to prepare raw data for modeling, to meet the expectations of data for a specific machine learning algorithms, and can give unexpected boosts in model accuracy.
It is important to get the intuition behind the data, every data speaks and you have to listen what it is saying by using various methods. 
Here are some tricks you can use to improve performance:

   1. Improve Performance With Data.
   2. Improve Performance With Algorithms.
   3. Improve Performance With Algorithm Tuning.
   4. Improve Performance With Ensembles.
    
For further reference check this [link](https://machinelearningmastery.com/improve-deep-learning-performance/)


## Ensemble Methods
Ensemble methods are techniques that create multiple models and then combine them to produce improved results. Ensemble methods usually produces more accurate solutions than a single model would. This has been the case in a number of machine learning competitions, where the winning solutions used ensemble methods.

### Types of Ensembling:

- Bayes optimal classifier.
- Bootstrap aggregating (bagging)
- Boosting.
- Bayesian parameter averaging.
- Bucket of models.
- Stacking.

I have used stacking method to improve accuracy. 
 **Stacking** is a similar to boosting: you also apply several models to your original data. The difference here is, however, that you don't have just an empirical formula for your weight function, rather you introduce a meta-level and use another model/approach to estimate the input together with outputs of every model to estimate the weights or, in other words, to determine what models perform well and what badly given these input data.


## Accuracy: 0.68656
After submitting the result I managed to score **0.68658** accuracy on which I got 54 Rank on Leaderboard. There are plenty of modifications you can apply to increase the accuracy, as I haven't given much time and done proper Exploratory Data analysis so my rank drops.


**Areas to improve:**

- Dealing with text data in dataset
- Using different ensembling methods to improve accuracy
- Feature Engineering
- Using multiple algorithms
- Validation

*The primary aim of the solution is to get familiar with data and to capture the idea, to begin with, for further improvements.*
 

### Useful Links and References

[8 Proven Ways for improving the “Accuracy” of a Machine Learning Model](https://www.analyticsvidhya.com/blog/2015/12/improve-machine-learning-results/)

[Ensemble-methods-machine-learning](https://www.toptal.com/machine-learning/ensemble-methods-machine-learning)



### Collections of past solutions

http://ndres.me/kaggle-past-solutions/

https://www.kaggle.com/wiki/PastSolutions
 
https://github.com/ShuaiW/kaggle-classification/
