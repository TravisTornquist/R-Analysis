# R-Analysis
## Linear Regression to Predict MPG
When running a linear regression model on the data from MechaCar_mpg.csv there are a number of interesting take-aways.

Two variables provide a non-random amount of variance to the mpg values in the dataset. vehicle length has a p value of 2.60e-12, and ground clearence has a p value of 5.21e-08. The p-value of the linear regression as a whole is 5.35e-11.

Given that our level of significance is 0.05, our p-vaoue for the model is significantly lower. Therefore the regression does not have a slope of zero.

The linear regression has an R-squared value of 0.7149, so the model has an efficiency of 70%. It is an effective predictor of mpg.

Insert image

## Summary Statistics on Suspension Coils

The design specification for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 PSI. The current manufacturing data meets this design specification if you look at the data as a whole. When grouping lot numbers the variance is 62.3 PSI. However, when breaking the data out by lot number only lots 1 and 2 meet design specification with variences of 0.9 and 7.5 respectively. Lot 3 fails to meet design specification with a variance of 170.3.

Insert image

## T-Tests on Suspension Coils
When running a T-Test on all three lots comparing the mean PSI of the sample to the population mean PSI, the p-value is .06. Therefore, the variance in mean PSI in the sample has a 6% chance of being explainable by sampling error, which does not meet our level of significant of 5%. There is not a significant difference in the sample mean of the combined lots and the population mean.

We get some different number when we break out the different lots. The P values when comparing mean PSI of lots 1 and 2 to the population mean are 1 and .61 respectivly. Therefore, there is a 100% chance of the varience in lot 1 being explainable by sampling error, and a 60% chance of the varience in Lot 2 being explainable by sampling error. There is not a statistically significant difference in means of Lots 1 and 2, and the population mean. 

When running a T-Test on only Lot 3 comparing the mean PSI of the sample to the pupulation mean PSI, the p-value is .042. Therefore, the variance in PSI in the sample has a 4% chance of being explainable by smapliong error, which does meet our level of significant of 5%. There is a significant difference in the sample mean of Lot 3 and the population mean.

Insert Image

