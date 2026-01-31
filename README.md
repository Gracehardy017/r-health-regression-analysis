# r-health-regression-analysis
Linear and logistic regression analysis in R using example health datasets, with description of model outputs and limitations.

## Overview
Aim of the project is to identify and interpret key predictors, describe model assumptions and limitations. Using publicly available health-related data sets, both linear and logistic regression will be applied using R. 

## Objectives
- Model healthcare costs using linear regression methods
- Model disease risk using logistic regression methods
- Interpret coefficients, odds ratios, and statistical significance
- Assess and describe model assumptions and limitations

## Datasets
- **Medical Insurance Cost Dataset** – used for linear regression
- **Pima Indians Diabetes Dataset** – used for logistic regression

 Add the above CSV files in a folder named `Data` in the project root.

## Methods
- Exploratory data analysis
- Model fitting and diagnostics
- Interpretation of results
- Discussion of limitations

## Key Outputs
- Reproducible RMarkdown analyses
- Model diagnostics and visualisations
- Written interpretation of results

# Getting Started
1. Install required packages (if not already installed)

In order to run the analysis, download the R packages as follows: 

```r
options(repos = c(CRAN = "http://cran.us.r-project.org"))
install.packages(c(
  "broom",
  "car",
  "caret",
  "MASS",
  "glmnet",
  "lmtest", 
  "ggplot2", 
  "remotes",
  "rlang",
  "here"))
```  

2. Run R code to produce the analysis reports:
 - Add Datasets to the Data folder
 - Open the RMarkdown files:
    - linear_regression_insurance_report.Rmd
    - logistic_regression_diabetes_report.Rmd
 - Select knit to generate the HTML outputs 

## Author
Grace Hardy