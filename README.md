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

![total_summary_df.png](https://github.com/kejtkjet1/MechaCar_Statistical_Analysis/blob/main/images/total_summary_df.png)
![Lot_summary_df.png](https://github.com/kejtkjet1/MechaCar_Statistical_Analysis/blob/main/images/Lot_summary_df.png)

- The new design is quite nice and allows us to search by multiple different criteria. We should add a feature that allows us to clear the filter instantly without having to manualy change all the filter options. 