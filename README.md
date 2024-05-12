# NHANES Socioeconomic Predictors

This data analysis uses the [2017-2018 data from the NHANES dataset](https://github.com/micdwill/NHANES-Socioeconomic-Predictors/blob/master/DEMO_J.XPT).
The variable to predict is ratio of family income to poverty. It uses LASSO regression for variable selection, employing K-fold cross validation to pick the 
optimal lambda parameter. Then, a random forest is leveraged in order to find good predictors for our response variable by analyzing mean decrease in Gini 
Coefficient.

This repository includes a report on the findings in [NHANES.pdf](https://github.com/micdwill/NHANES-Socioeconomic-Predictors/blob/master/NHANES.pdf). This includes many graphics and conclusions drawn. The RMarkdown code containing the analysis and the code for the graphics generated is included in this 
repository in [NHANES_Socioeconomic.Rmd](https://github.com/micdwill/NHANES-Socioeconomic-Predictors/blob/master/NHANES_Socioeconomic.Rmd).
