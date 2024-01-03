# Surprise Housing
> This is Advanced Regression case study to get the best model with Low Variance and Low Bias.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We need to analyze the data with appropriate tools
- We need to find out which variables are significant in predicting the price of a house.
- How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- As per stats model api OLS, we found that there is High Variance in Linear Regression model.
- As Lasso Regression, we can get the best model with 15 features ['GrLivArea','OverallQual', 'GarageCars', 'Neighborhood_NoRidge', 'TotRmsAbvGrd', 'MSSubClass', 'Neighborhood_StoneBr', 'Fireplaces', 'Neighborhood_NridgHt', 'BsmtQual_Gd', 'BsmtQual_TA', 'BsmtExposure_Gd', 'KitchenQual_TA', 'FullBath', 'Exterior1st_BrkFace'] and Alpha 0.0001 having test score of 0.83 and whole train score as 0.81.
- As Ridge Regression, we can get the best model with 15 features ['OverallQual', '2ndFlrSF', 'GrLivArea', 'Neighborhood_NoRidge', 'TotRmsAbvGrd', 'GarageCars', 'Neighborhood_StoneBr', 'FullBath', 'BsmtQual_TA', 'BsmtQual_Gd', 'KitchenQual_TA', 'Fireplaces', '1stFlrSF', 'Neighborhood_NridgHt', 'KitchenQual_Gd'] and Alpha 5 having test score of 0.81 and whole train score as 0.78.
- We have built the model with stats model where we observed High Variance.<br/>
<strong>train score: 0.93, test score: 0.73</strong><br/><br/>
- Then we have built the model with Lasso Regression where we got optimal Alpha as 0.0005 with 231 Features.<br/>
<strong>train score: 0.85, test score: 0.85</strong><br/> <br/>
- Then we have built optimized Lasso Regression model with 15 Features where we got optimal Alpha as 0.0001.<br/>
<strong>train score: 0.81, test score: 0.83</strong><br/><br/>
- We have tried Ridge regression where we got optimized Alpha as 10 with 231 Features.<br/>
<strong>train score: 0.88, test score: 0.86</strong><br/><br/>
- Then we have built optimized Ridge regression model with 15 Features where we got optimal Alpha as 5.<br/>
<strong>train score: 0.78, test score: 0.81</strong>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- statsmodel api
- sklearn
- pandas
- matplotlib
- seaborn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by Venkata Saikrishna Dussa [@CrazyDussa] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
