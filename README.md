# Survival-weibull

The project aims to perform the Survival Analysis on Lung cancer patients' survival time data with the help of Bayesian Data Analysis sampling in Stan.

Two models are made:
- Weibull model with the option to include censored data for analysis
- Weibull hierarchical model for division the analysis for specific institutions

Structure:
- Data description and EDA: description.rmd
- Model description: weibull.Rmd
- Weibull model (incl. censored) in Stan: weibull_censored.stan
- Weibull model (incl. censored) run and convergence analysis: weibull_censored.R
- Weibull hierarchical model (incl. censored): weibull_hier.stan
