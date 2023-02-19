# R-Analysis
## Linear Regression to Predict MPG
When running a linear regression model on the data from MechaCar_mpg.csv there are a number of interesting take-aways.

Two variables provide a non-random amount of variance to the mpg values in the dataset. vehicle length has a p value of 2.60e-12, and ground clearence has a p value of 5.21e-08. The p-value of the linear regression as a whole is 5.35e-11.

Given that our level of significance is 0.05, our p-vaoue for the model is significantly lower. Therefore the regression does not have a slope of zero.

The linear regression has an R-squared value of 0.7149, so the model has an efficiency of 70%. It is an effective predictor of mpg.

Insert image

## Summary Statistics on Suspension Coils

The design specification for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 PSI. The current manufacturing data meets this design specification if you look at the data as a whole. When grouping lot numbers the variance is 62.3 PSI. However, when breaking the data out by lot number only lots 1 and 2 meet design specification with variences of 0.9 and 7.5 respectively. Lot 3 fails to meet design specification with a variance of 170.3.

