# Linear-Regression

Linear Regression is one of the most fundamental algorithms in the Machine Learning world. It is the door to the magical world ahead. But before proceeding with the algorithm.Linear Regression is one of the most fundamental and widely known Machine Learning Algorithms which people start with. Building blocks of a Linear Regression Model are:

1. Discreet/continuous independent variables

2. A best-fit regression line

3. Continuous dependent variable. i.e., A Linear Regression model predicts the dependent variable using a regression line based on the independent variables. The equation of the Linear Regression is:

                                         Y=a+b*X + e 
Where, a is the intercept, b is the slope of the line, and e is the error term. The equation above is used to predict the value of the target variable based on the given predictor variable(s).

## Simple Linear Regression
Simple Linear regression is a method for predicting a quantitative response using a single feature ("input variable"). The mathematical equation is:

                                           ð¦=ð½0+ð½1ð¥
What do terms represent?

1. ð¦ is the response or the target variable
2. ð¥ is the feature
3. ð½1 is the coefficient of x (slope)
4. ð½0 is the intercept
5. ð½0 and ð½1 are the model coefficients. To create a model, we must "learn" the values of these coefficients.

## Multiple Linear Regression
Till now, we have created the model based on only one feature. Now, weâll include multiple features and create a model to see the relationship between those features and the label column. This is called Multiple Linear Regression.

                                          ð¦=ð½0+ð½1ð¥1+...+ð½ðð¥ð
Each ð¥
 represents a different feature, and each feature has its own coefficient. In this case:

ð¦=ð½0+ð½1Ãðð+ð½2Ãððððð+ð½3Ãððð¤ð ððððð
Let's use Statsmodels to estimate these coefficients
