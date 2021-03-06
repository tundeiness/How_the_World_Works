# How the world works Cornerstone Project
This project is an Exercise in the [Elite Datascience bootcamp](https://pro.elitedatascience.com)
It delves deep into how to implement the most simple Mean model to the complex models that can be used in Machine learning.
It also explains concepts like normalization, "toy problems", overfitting, underfitting, evaluating models visually, helper functions, re-engineering input features, and model complexity through hands on exercises. 

## Project Intro/Objective
The purpose of this project is to give students a hands on approach to Machine Learning and Data science.
It delves deep into how to implement the most simple Mean model to the complex models that can be used in Machine learning.
I was introduced to concepts like:
    - normalization, 
    - "toy problems", 
    - overfitting, 
    - underfitting, 
    - evaluating models visually, 
    - using helper functions, 
    - re-engineering input features, and 
    - model complexity   (Describe the main goals of the project and potential civic impact. Limit to a short paragraph, 3-6 Sentences)


### Technologies

* Python
* Pandas, jupyter

## Project Description

## Fake it Til You Make it
## Exercise One:
- Import required libraries like Numpy, Pandas, Matplotlib, Seaborn and pyplot
- Explored the libraries
-Generating placeholder data using np.linspace
- Creating random samples with Numpy and creating sample for sine wave and Tan wave(sine and tan wave       simulation)
- Simulating Noise to make data realistic
- Importing data using pandas read_csv
- Exploring Normal Distribution and standard deviation values as it affects normal distribution shapes
- Implement Sport Betting exercise. 


## Building Simple Mean Models and Linear Regression Models
## Exercise Two: 
- Mean Model
- visually evaluate how the mean model "fits" the training data using graphs
  1. overlay the mean model predictions with the original dataset using plt.plot() for line plot and plt.scatter() to plot the training data. 
- evaluate mean model visually
- implement linear regression model using sci-kit learn module
- evaluate linear regression model vs training data

### Introduction to Model Parameters 

                          Model     |     Model Parameter

        Mean Model                  |   average value of y
        Linear Regression Model     |   intercept and coefficient
        Polynomial Regression Model |   intercept and co-efficient


- how model parameter defines individual models
- make prediction manually using intercept and co-efficient
- assign new values to intercept and co-efficient
 

## Polynomial Regression and Model Parameters
###  Exercise 3.2: Model complexity
- Factors that influence  Polynomial regression model complexity are :
   (1) Number of model parameters ( i.e  ????1 ????2 or ????3 )
   (2) effectiveness in expressing relationship within the dataset(Model parameter effectiveness)
- where there is a model with 2 non-sequential polynomial terms: Like fitting and plotting a model with  ????,????3,and ????5 as input features. These are non sequential as observed.
- The more the parameters supplied, the better the ability of the model to express underlying relationships.

## Exercise 3.3: Normalization
- Normalizing data and re-fitting model when features are not equally scaled.
- create a normalizing helper function
## Exercise 3.4: 
- plotting polynomial regression model with a tangent underlying wave. 

## Exercise 4.1:
- sine wave plot using Decision trees
- Decision tree structure investigation

## Exercise 4.2:
- Decision tree decision paths

## Exercise 4.3:
- input dimensions for new samples/observations
- reshaping one observation to a 2D Numpy array format for use with scikit learn
- inferring `.reshape()` to return a  'n x 1' array.

## Exercise 4.4:
- plotting and fitting decision trees with noisy tangent dataset


## Exercise 5.1:
- code practice checkpoint
- a review fitting and modelling a 3rd order polynomial.
## Exercise 5.2: Creating Models for Noisy Tangent data
- implementing model for noisy tangent dataset.
- importing tangent dataset
- fitting and storing mean model, Linear model, 2nd order polynomial, 3rd order polynomial, 5th order polynomial
  10th order polynomial, decision tree without constraints, decision tree with max-depth constraints, decision tree
  with mean sample leaf constraint, random forest without constraints, random forest with random state argument
  and mean sample leaf and finally random forest with random state and max depth; all with the help of a helper method
  and using training dataset.

## Exercise 5.3: Simulating a new Noisy Tangent Data
- simulating new tangent test dataset to fit with the stored model.
- overlaying data plots on one another for insight.
- implementing model for noisy tangent dataset.
- importing tangent dataset
## Exercise 5.4: Models vs Noisy tangent Data
- evaluating the stored models on the new noisy tangent dataset and pick a winner empirically.
- Displaying M.S.E and M.A.E for the newly fitted model

## Exercise 5.5: Error Analysis and Black Swan events
- Manual calculations of absolute errors 
- Manual calculations of squared errors 
- displaying summary statistics of MSE and MAE errors
- comparing the MSE and MAE summary statistics.


## Contact
* Feel free to contact me  with any questions!