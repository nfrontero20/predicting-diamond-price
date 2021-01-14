# Predicting Diamond Price

I worked with two peers in STAT-225 Nonparametric Statistics to predict the prices of diamonds.  

We created a **[report](https://github.com/nfrontero20/predicting-diamond-price/blob/master/report.pdf)** of our findings and also gave a **[presentation](https://github.com/nfrontero20/predicting-diamond-price/blob/master/presentation.pdf)**.

Our report includes:

  - Exploratory data analysis
  - Three different regression models: 
      1) Ordinary least squares (OLS)
      2) JHM (rank based)
      3) Generalized additive model (GAM)
  - Assessment of model fit
  - Proposed model (the best model)
  - Discussion
  
## Findings

Our proposed model is a GAM that predicts diamond price (actually the log of diamond price) using depth, length, width, carat, color, and clarity (with a smoothing spline on length and width). 
  
