# Assignemnt 2 on Regularized Regression - Housing Dataset

> Building a regression model with regularization to predict the actual value of prospective properties in the Australian market.

## Table of Contents
* [Problem Statement & Objective](#1)
* [Business Goal](#2)
* [Analysis Steps](#3)
* [Libraries Used](#4)
* [Conclusions & Recommendations](#5)
* [Acknowledgements](#6)
* [Contact](#7)

## <a name="1">Problem Statement & Objective</a>
- Surprise Housing, a US-based housing company, aims to enter the Australian market. They utilize data analytics to purchase houses below market value and sell them at a profit. To achieve this, they have collected a dataset containing information on house sales in Australia.
- The company seeks to build a regression model with regularization to predict the actual value of potential properties, aiding them in making informed investment decisions.
- Key objectives:
    * Identify significant variables for predicting house prices.
    * Assess how well these variables describe house prices.

## <a name="2">Business Goal</a>
- The primary goal is to develop a model for predicting house prices based on available independent variables. This model will guide the management in understanding the price dynamics and making strategic decisions to maximize returns.

## <a name="3">Analysis Steps</a>
- Data quality checks will be performed to ensure data integrity.
- Column names will be standardized for clarity.
- Regularization techniques (Ridge and Lasso) will be applied to build the regression model.
- The optimal value of lambda for Ridge and Lasso regression will be determined.
- Significance of variables in predicting house prices will be assessed.

## <a name="4">Libraries Used</a>
- numpy
- pandas
- matplotlib
- seaborn
- statsmodel
- sklearn
- -datetime

## <a name="5">Conclusions & Recommendations</a>
- The Ridge model's R2 score is higher than Lasso model with an R2 score of 90.4% and 88.9% respectively on the test set.
- Yet the Lasso model is preferred since it eliminates more than 85% of the variables and thereby creating a simpler model. As per Occam's Razor we always go with the simpler model and plus the business prefers means to understand what variables contribute to the selling price rather than acheiving a model with high predictive power.
- The top 5 predictive variables according to the chosen model are
  1. Overall Quality
  2. Above ground living area square feet
  3. Size of garage (in cars)
  4. Property Age
  5. Overall Condition

## <a name="6">Acknowledgements</a>
- This project is a part of the Executive PG Programme in Machine Learning & AI offered by upGrad.
- [upGrad Content on Advanced Regression](https://github.com/ContentUpgrad/Ridge-Regression)
  
## <a name="7">Contact</a>
- Created by the [owner](https://github.com/Kris3317/) of this Repo.
- Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/krismichaeldsilva/)

