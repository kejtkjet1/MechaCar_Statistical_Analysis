# MechaCar_Statistical_Analysis

R and R Studio project

## Overview of Project

### Purpose

Analysis of the data using R Studio. 

## Linear Regression to Predict MPG

![Linear_regression.png](https://github.com/kejtkjet1/MechaCar_Statistical_Analysis/blob/main/images/Linear_regression.png)

- The regression analysis above indicates the following:
    - The vehicle length, and vehicle ground clearance are statistically significant. They have a significant impact on miles per gallon on the MechaCar prototype. Vehicle weight, spoiler angle, and (AWD) have large p-Values that indicate a non significan impact on the MPG. 

    - The p-Value for this model is 5.35e-11. It is very low much lower than the significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis. This tells me that linear regression slope is not 0. 

    - R-squared value of 0.7149, 71% of all mpg predictions will be correctly determined by the  model. 



## Summary Statistics on Suspension Coils

- The Suspension Coil dataset show results of testing the weight capacities of multiple suspension coils from multiple production lots to determine consistency.


![total_summary_df.png](https://github.com/kejtkjet1/MechaCar_Statistical_Analysis/blob/main/images/total_summary_df.png)
![Lot_summary_df.png](https://github.com/kejtkjet1/MechaCar_Statistical_Analysis/blob/main/images/Lot_summary_df.png)

- The variance of the coils is 62.29 PSI, it well within the 100 PSI variance requirement.

- Lot 1 and Lot 2 are well within the 100 PSI. Lot 3 that is creating issues with variance of 170. that lot is affecting the overall variance of all lots combined. Without lot 3 there would be nearly no variance. 

## T-Tests on Suspension Coils

T-Test overall

![ttest.png](https://github.com/kejtkjet1/MechaCar_Statistical_Analysis/blob/main/images/ttest.png)

T-Test for samples
![ttest_samples.png](https://github.com/kejtkjet1/MechaCar_Statistical_Analysis/blob/main/images/ttest_samples.png)

