# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
  Conducted Analysis with the following technique

- Data understanding and exploration
- Data cleaning
- Data preparation
- Model building and evaluation
- Observation and inference

## Conclusions
- Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test, it is better to use Lasso, since it brings and assigns a zero value to insignificant features, enabling us to choose the predictive variables. It is always advisable to use simple yet robust model.
- Equation can be formulated using the features and coefficients obtained by Lasso
- Log(Y) = C + 0.125(x1) + 0.112(x2) + 0.050(x3) + 0.042(x4) + 0.035(x5) + 0.034(x6) + 0.024(x7) + 0.015(x8) + 0.014(x9) + 0.010(x10)
+ 0.010(x11) + 0.005(x12) - 0.007(x13) - 0.007(x14) - 0.008(x15) - 0.095(x16) + Error term(RSS + alpha * (sum of absolute value of coefficients)


## Technologies Used
- Python 
- Pandas
- Matplotlib
- Seaborn
- sklearn
- statsmodels
- Lasso
- Ridge
- Jupyter Notebook

## Contact
Created by [@ajayjgupta] - feel free to contact me!