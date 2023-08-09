# BikeAssignmentUpgrad
> To build a multiple linear regression model for the prediction of demand for shared bikes. 

## Table of Contents
* [Problem Statement & Objeective](#1)
* [Analysis Steps](#2)
* [Libraries Used](#3)
* [Conclusions & Recommendations](#4)
* [Acknowledgements](#5)
* [Contact](#6)

## <a name="1">Problem Statement & Objective</a>
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A dataset is provided by a company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    * Which variables are significant in predicting the demand for shared bikes?
    * How well those variables describe the bike demands?
- Therefore a model needs to be built for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## <a name="2">Analysis Steps</a>
- Data quality checks are performed, to make sure there are no null data or any inconsistent data.
- Column names are changed to avoid any ambiguity
- Pairplot analysis is performed on the numerical data to get an overview of the dataset.
- Boxplot analysis is performed to see the impact of categorical features on the target variable.
- Categorical variables are converted to appropriate dummy variables.
- No new metrics are derived since there is a strong number of variables present after the creation of dummy variable and also derivable variables such as day, month are already present in the dataset, fortunately.
- Variables that are either not feature variables or are identifying variables are dropped.
    
## <a name="3">Libraries Used</a>
- numpy
- pandas
- matplotlib
- seaborn
- statsmodel
- sklearn

## <a name="4">Conclusions & Recommendations</a>
- After building almost 10 models, we can conlcude that with the given dataset we are able to account for almost 85% of the variance in the data, i.e., R2 vallue = ~85%
- We can achieve this score either by using 15 variables that scores a R2 value of 84.5% or just by using 9 variables achieving a R2 score of 82.3%
- Based on the business requirements of whether they need a simple model or not we can suggest among the 2 models and explain how the selected variables impact the bike rentals and correspondingly translate into a marketing plan. 

## <a name="5">Acknowledgements</a>
- This project is a part of the Executive PG Programme in Machine Learning & AI curated by upGrad.
- [upGrad Content on Linear Regression Example 1](https://github.com/ContentUpgrad/Linear-Regression/blob/main/Industry%20Relevance%20of%20Linear%20Regression/Media%2BCompany%20(1).ipynb)
- [upGrad Content on Linear Regression Example 2](https://github.com/ContentUpgrad/Linear-Regression/blob/main/Multiple%20Linear%20Regression%20in%20Python/Housing%2BCase%2BStudy%2Busing%2BRFE%20(2).ipynb)
- [upGrad Content on Linear Regression Example 3](https://github.com/ContentUpgrad/Linear-Regression/blob/main/Multiple%20Linear%20Regression%20in%20Python/Multiple%2BLinear%2BRegression%2B-%2BHousing%2BCase%2BStudy%20(2).ipynb)   
- If you too would like to be a part of this extremely informative and detailed Exec Programme, enroll yourself [here](https://app.upgrad.com/4Xxq/4zgb85pa) and feel free to use my referral code (ZlrGO7) to avail high fee waivers.

## <a name="6">Contact</a>
- Created by the [owner](https://github.com/Kris3317/) of this Repo, surprise.
- Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/krismichaeldsilva/)
