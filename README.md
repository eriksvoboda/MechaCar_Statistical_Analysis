# MechaCar Statistical Analysis

## Project Purpose

The purpose of the project is to perform statistical analysis to identify which variables in the dataset predict the MPG of the MechaCar prototypes. And then review these insights and help the manufacturing team.

## Linear Regression to Predict MPG

The most sigificant variables in the dataset that provided a non-random amount of variance to the MPG values were Vehicle Length and Ground Clearance. The P-Values for these variables are 2.60e-12 and 5.21e-08 respectively. The intercept is also statistically significant with a P-Value of 5.08e-08.

The slope can't be considered to be zero. This is because the P-Value is so low at 5.35e-11 that the null hypothesis is rejected. Tells us that the releationship between MPG and the dataset variables is subject to more than random chance. 

The r-squared value is at 0.7149 meaning the linear regression model is 71% accurate. Meaning there are more than likely other variables that are significant. So the model is somewhat effective however it could be improved.

![](images/deliv1.png)

## Summary Stats on Suspension Coils
![](images/total_summary.png)
![](images/lot_summary.png)

Looking at the Total Summary, the variance is below 100 at 62.29 and meets expectations. However Lot 3 has a variance of 170.28 which is greater than the limit of 100. This means Lot 3 does not meet the design specification. 

## T-Tests on Suspension Coils

All Lots T-Test
![](images/cumulative_t_test.png)

Lot 1 T-Test
![](images/lot1_ttest.png)

Lot 2 T-Test
![](images/lot2_ttesttest.png

Lot 3 T-Test
![](images/lot3_ttesttest.png)

## Study Design: MechaCar vs Competition
