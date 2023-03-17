# Causal Machine Learning Project

This project focuses on the analysis of different Double Machine Learning (Double ML) models and their evaluation using the `DoubleML` package in R.

## Overview

Double ML is a framework for causal inference and program evaluation. It combines machine learning methods with econometric and statistical techniques to estimate treatment effects in observational data.

In this project, we will explore various Double ML models and evaluate their performance in estimating treatment effects using the `hdm` package data. This data was used in [Chernozhukov and Hansen (2004)](https://direct.mit.edu/rest/article/86/3/735/57586/The-Effects-of-401-K-Participation-on-the-Wealth) to investigate the effect of participation in the employer-sponsored 401(k) retirement savings plan (*p401*) on net assets (*net_tfa*).

## Getting Started

To get started with this project, you will need to have a basic understanding of machine learning concepts and causal inference. You will also need to have R installed on your computer along with the necessary libraries for data analysis and machine learning.

## Data

The dataset we will be working with consists of ten covariates/regressors/predictors:

- *age*: age
- *db*: defined benefit pension
- *educ*: education (in years)
- *fsize*: family size
- *hown*: home owner
- *inc*: income (in US $)
- *male*: male
- *marr*: married
- *pira*: participation in individual retirement account (IRA)
- *twoearn*: two earners

The outcome variable is `net_fa` and the treatment variable is `p401`.

## Analysis

The analysis will involve fitting various Double ML models to the data using the `DoubleML` package in R. We will use the `mlr3learners` package for our estimators and also use `mlr3tuning` for hyperparameter tuning of our learners. We will evaluate their performance in estimating treatment effects using a range of evaluation metrics.

## Results

The results of our analysis will be presented in a clear and concise manner. We will provide detailed explanations of our findings along with visualizations to help convey our results.

## Conclusion

This project provides an in-depth analysis of different Double ML models and their performance in estimating treatment effects using the `hdm` package data. The results obtained from this project can be used to inform future research on causal inference using machine learning methods.