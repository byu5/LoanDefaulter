# LoanDefaulter
This project is to analyze the relationship between each feature and risk flag. Using training data to build models and test data to qualify the performance. Also, the model helps to predict the possible defualters for smal business loans. 

## Table of Content
* [Features](https://github.com/byu5/LoanDefaulter/blob/main/README.md#features)
* [Get Started](https://github.com/byu5/LoanDefaulter/blob/main/README.md#get-started)
* [Contributors](https://github.com/byu5/LoanDefaulter/blob/main/README.md#contributors)

## Features
The data analysis will provide:
- Logistic Regression
- Correlation Matrix
- ANOVA Table


## Get Started
+ The columns in test data and training data include: Id, Income, Age, Experience, Married_Single, House_Ownership, Car_Ownership, Profession, CITY, STATE, CURRENT_JOB_YRS, CURRENT_HOUSE_YRS and Risk_Flag. 

+ The x variables are: Car_Ownership, Profession, CITY, STATE, CURRENT_JOB_YRS, CURRENT_HOUSE_YRS
+ The y variables is: Risk_Flag
+ The accuracy score of Logistic Regression is 0.8716785714285714
+ The correlation between STATE and Car-Ownership is relatively high which is 0.026.
+ In the ANOVA table, since the p-value is less than 2e-16, we can reject our null hypothesis. R-squared value shows the goodness of fit in a model. In this case, R-squared value is 0.004 which is not a good fit. 
+ In the ANOVA table, we can tell that Married_Single, House_Ownership, House_Ownership, Car_Ownership, Age, Experience, CURRENT_JOB_YRS are significant, because the p-values are less than 0.05.  


## Contributors
- Weijia Wang
- Barry Yu
- Giani Kurniawan
