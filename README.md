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

- Mean of the sample is 1498.78. P-Value of 0.06 is higher than the common significance level of 0.05, there is NOT enough evidence to support rejecting the null hypothesis. Mean of all three of these manufacturing lots is statistically similar to the presumed population mean of 1500


T-Test for samples
![ttest_samples.png](https://github.com/kejtkjet1/MechaCar_Statistical_Analysis/blob/main/images/ttest_samples.png)

- Next looking at each individual lots:

    -  Lot 1 sample has mean of 1500. P-Value of 1, clearly we cannot reject (i.e. accept) the null hypothesis that there is no statistical difference between the observed sample mean and the presumed population mean (1500).
    - Lot 2 is similar, sample mean  1500.02, a p-Value of 0.61; the null hypothesis cannot be rejected, and the sample mean and the population mean of 1500 are statistically similar.
    - Lot 3 is diffeernt than other 2. Mean is 1496.14 and the p-Value is 0.04, which is lower than the common significance level of 0.05. We can reject the null hypothesis that this sample mean and the presumed population mean are not statistically different - therefore assume the are statistically differnt.

## Study Design: MechaCar vs Competition

Colect data for different models from all other manufacturers for past 3 years for a variety of  metrics:

- Current Price (Selling): Independent Variable
- Safety Rating: Independent Variable 
- Engine Type (Electric, Hybrid, Gasoline): Independent Variable
- Kelly Blue Book Resale Value: Dependant Variable
- MPG (Gasoline Efficiency): Independent Variable
- Weight: Independent Variable
- Manufacturer: Independent Variable


Hypothesis: Null and Alternative
After determining which factors are key for the MechaCar's genre:

Null Hypothesis (Ho): MechaCar Resell priece is same as other similar competitors based on all the measured metrics. 
Alternative Hypothesis (Ha): MechaCar resale value is dissimilar and influenced by some factors beyond manufacturer type


Statistical Tests
A multiple linear regression would be used to determine the factors that have the highest correlation/predictability with the resell price. It can be one or many of the facstors that affect the price based on the manufacturer.