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

