# NFL Season Wins Analysis

## Overview

This repository contains an analysis of data from an unspecified NFL season, specifically focusing on team season wins. The primary objective is to predict the number of wins a team is likely to achieve in the upcoming season. The dataset used for this analysis, "nfl_project2.csv," was obtained from [nflsavant.com](http://nflsavant.com/).

## Analytical Process

1. **Data Exploration and Visualization:**
   - Construct scatter plots to visualize potential relationships between independent variables and the dependent variable (team season wins).

2. **Statistical Analysis:**
   - Compute correlation coefficients and p-values for each independent variable in relation to the dependent variable.
   - Utilize the sklearn library to identify the most suitable features for predictive models.

3. **Regression Models:**
   - Develop simple and multiple linear regression models.
   - Evaluate models using statistical metrics such as R-squared (R2), T-testing/F-testing, mean squared error (MSE), and residual mean squared error (RMSE).

4. **Model Selection:**
   - Compare and refine options down to two models based on the aforementioned metrics.
   - Choose the final model through a comprehensive analysis involving residual analysis, including residual plots, variance inflation factors (VIF) calculation, and visual inspection of QQ plots/histograms for normality.

5. **Evaluation:**
   - Reevaluate MSE and RMSE using both training and testing datasets.

6. **Predictions and Confidence Intervals:**
   - Compute predictions and confidence intervals based on the selected final model.

## Detailed Report
The findings and detailed analysis of the regression models will not be presented in this README.md file. Instead, a comprehensive report will be generated separately to explain the chosen model.
Please refer to the report for a thorough examination of the analysis, model selection, and the rationale behind it. The report will present the final model and its performance metrics.
For further details, please review the accompanying code and the detailed report.

## Interactive Program

In addition to the analytical process, an interactive program has been developed. This program allows users to input variable values and obtain predictions for NFL team season wins, along with associated confidence intervals based on the selected final model. The aim is to enhance the practical utility of the analysis, making it more accessible and user-friendly.

