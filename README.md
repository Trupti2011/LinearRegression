Linear Regression Supervised Machine Learning Algorithm

Linear regression is a statistical method that is used to predict a continuous dependent variable(target variable) based on one or more independent variables(predictor variables).

Assumptions of Linear Regression

Regression is a parametric approach, which means that it makes assumptions about the data for the purpose of analysis. For successful regression analysis, it’s essential to validate the following assumptions.

 Linearity of residuals: There needs to be a linear relationship between the dependent variable and independent variable(s).
Linearity of residuals
2. Independence of residuals: The error terms should not be dependent on one another (like in time-series data wherein the next value is dependent on the previous one). There should be no correlation between the residual terms. The absence of this phenomenon is known as Autocorrelation.

There should not be any visible patterns in the error terms.

Independence of residuals
 

3. Normal distribution of residuals: The mean of residuals should follow a normal distribution with a mean equal to zero or close to zero. This is done in order to check whether the selected line is actually the line of best fit or not.
If the error terms are non-normally distributed, suggests that there are a few unusual data points that must be studied closely to make a better model.

Normal distribution of residual
4. The equal variance of residuals: The error terms must have constant variance. This phenomenon is known as Homoscedasticity.

The presence of non-constant variance in the error terms is referred to as Heteroscedasticity. Generally, non-constant variance arises in the presence of outliers or extreme leverage values.

The equal variance of residuals
