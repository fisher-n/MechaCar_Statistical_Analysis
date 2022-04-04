# MechaCar_Statistical_Analysis
Analysis for client to review production data to help manufacturing team on new car prototype. Using R linear regression and t-tests.
 
## Linear Regression to Predict MPG
Using the data from csv file to get the linear regression displayed below
![This is an image](https://github.com/fisher-n/MechaCar_Statistical_Analysis/blob/main/images/d1.png)

Summary of linear regression to determine p-value and r-squared
![This is an image](https://github.com/fisher-n/MechaCar_Statistical_Analysis/blob/main/images/d2.png)

### Summary
There are no variable that provide a non-random amount of variance to the mpg values.
The slope of the linear model is not 0 because all variables are directly proportional to the mpg values.
Since the p-value is below 0.05 this does not effectivly predict mpg of Mechacar prototype

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

### The suspension coil's PSI across all manufacturing lots
In the total_summary table (displayed below) was created to display the Mean, Median, Variance and SD of the prototype. As shown the total variance meets the parameter for suspension coils and does not exceed 100 per square inch.

![This is an image](https://github.com/fisher-n/MechaCar_Statistical_Analysis/blob/main/images/D2a.png)

### Suspension coil's PSI for each lot
In the lot_summary table created shows that not all the lots meet the parameters for suspension coils. Specfically lot 3 has a higher PSI variance than required which is not acceptable. 

![This is an image](https://github.com/fisher-n/MechaCar_Statistical_Analysis/blob/main/images/d2b.png)

## T-Tests on Suspension Coils
 T-test to determine if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.
 
 ### For all lots
 With a p-value of 1 it is not significant and the null hypothesis can be accepted.
 ![This is an image](https://github.com/fisher-n/MechaCar_Statistical_Analysis/blob/main/images/d3a.png)
 
 ### For individual lots
 #### Lot 1
 With a p-value less than 0.05, we fail to accept the null hypothesis and significantly different.
 ![This is an image](https://github.com/fisher-n/MechaCar_Statistical_Analysis/blob/main/images/d3b.png)
  
 #### Lot 2
 With a p-value less than 0.05, we fail to accept the null hypothesis and significantly different.
 ![This is an image](https://github.com/fisher-n/MechaCar_Statistical_Analysis/blob/main/images/d3c.png)
 
 #### Lot 3 
 With a p-value greater than 0.05, we accept the null hypothesis and it is not significantly different.
 ![This is an image](https://github.com/fisher-n/MechaCar_Statistical_Analysis/blob/main/images/d3d.png)
  
 The analysis for the total of all all lot they are signifiantly different and we accept the null hypothesis. This is also the same for Lot 3. However the anlaysis for lots 1 and 2 show there is not a significant difference and we fail to accept the null.
 
 ## Study Design: MechaCar vs Competition
 
 Further analysis to describe the MechaCar prototype against competition would be to compare the highway mpg, cost, and maintence cost. The null hypothesis would be there is no difference between the MechaCar sample mean and population mean against competition brands. The mean of metricA from the MechaCar can be equal or different than the mean of metricA of competition. Using a t-test we can calculate the p-value to determine if we reject or fail to reject the null. Since we are comparing the means of two populations we will use a two sample t-test. If we want to know whether one mean is greater or less than the other we can use a one tailed t-test. To run this test we need the mean of both samples, the standard deviation of both samples, and the number of observations.
 
 
