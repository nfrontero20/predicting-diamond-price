# Predicting Diamond Price

I worked with two peers in STAT-225 Nonparametric Statistics to predict the prices of diamonds.  

We performed exploratory data analyses, and then used 6 quantitative predictors and 3 qualitative predictors to fit three different regression models: 

1) Ordinary least squares (OLS)
2) JHM (rank based)
3) Generalized additive model (GAM)

We assessed the model fit of each model, and ultimately proposed the use of a GAM model as our final model.  

Our proposed model predicts diamond price (actually the log of diamond price) using depth, length, width, carat, color, and clarity (with a smoothing spline on length and width). 

An excerpt from our report can be seen below.

![](README-images/report-preview.png)

## Navigating the repository

This repository contains the files pertianing to our project report and project presentation. 

  - Report: [report.Rmd](https://github.com/nfrontero20/predicting-diamond-price/blob/master/report.Rmd), [report.pdf](https://github.com/nfrontero20/predicting-diamond-price/blob/master/report.pdf)
  - Presentation: [presentation.Rmd](https://github.com/nfrontero20/predicting-diamond-price/blob/master/presentation.Rmd), [presentation.pdf](https://github.com/nfrontero20/predicting-diamond-price/blob/master/presentation.pdf), [presentation.html](https://github.com/nfrontero20/predicting-diamond-price/blob/master/presentation.html)
  
