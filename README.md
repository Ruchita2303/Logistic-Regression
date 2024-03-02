# Logistic-Regression
We'll create a model for a telecommunication company, to predict when its customers will leave for a competitor, so that they can take some action to retain the customers.

In this notebook, you will learn Logistic Regression, and then, you'll create a model for a telecommunication company, to predict when its customers will leave for a competitor, so that they can take some action to retain the customers.

# What is different between Linear and Logistic Regression?
While Linear Regression is suited for estimating continuous values (e.g. estimating house price), it is not the best tool for predicting the class of an observed data point. In order to estimate the class of a data point, we need some sort of guidance on what would be the most probable class for that data point. 
As you know, Linear regression finds a function that relates a continuous dependent variable, y, to some predictors (independent variables x1, x2, etc.). For example, Simple linear regression assumes a function of the form:

                                                                          y=θ0+θ1∗x1+θ2∗x2+...
 

and finds the values of parameters θ0, θ1, 𝜃2, etc, where the term 𝜃0 is the "intercept". It can be generally shown as:

                                                                             hθ(x)=θTX
