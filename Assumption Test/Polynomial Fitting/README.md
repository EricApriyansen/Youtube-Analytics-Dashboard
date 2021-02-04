# History

While working on the After Outlier 2 model, the author had noticed some curvature pattern on the scatter plot (between residuals and predictors chart). Two linear trendlines were introduced into the chart, a simple linear and polynomial model. Based on the r square degree, the polynomial model has a slightly higher rate rather than the normal trendline. Polynomial regression was selected as the final regression model test.

There are multiple types of polynomial model which depends on the fitting degree. The author had identified Quadratic (^2) and Cubic (^3) after several inspections on the r square degree. 

The basic principles of the polynomial model revolve around the hierarchy. For example, the simple equation of the regression model is as follow:

Y = B + B1X1 + B2X2 + ... + BnXn+ e

With the polynomial model, the equation is adjusted as the following:

Y = B + B1X1 + B1X1^2+ B2X2 + B2X2 ... + BnXn + BnXn^2+ e

Therefore, a polynomial model can not have the higher hierarchy stand alone on the model as the example below:

Y = B + B1X1^2 + B2X2 ^2 + e

### Polynomial Result

All of the quadratic and cubic models have given the p-value above 0.05 for the higher hierarchy model. In other words, it is the same as just using the normal linear regression model. Therefore the polynomial model is rejected for future use. 
