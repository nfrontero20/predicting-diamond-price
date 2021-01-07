# Predicting Diamond Price

In the Nonparametric Statistics course that I took as an undergraduate, I worked with two other students to predict the prices of diamonds.  

After performing exploratory data analyses, we used 6 quantitative predictors and 3 qualitative predictors to fit three different regression models: 

1) **Ordinary least squares (OLS)**
2) **JHM (rank based)** 
3) **Generalized additive model (GAM)**

We assessed the model fit of each model, and ultimately proposed the use of a GAM model to predict log(`price`) from `depth, length, width, carat, color, and clarity` (with a smoothing spline on length and width).
