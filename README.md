# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

In this analysis we performed a Linear regression to identify which car modification(s) would help with MPG improvement. 
As you can see in the image below, Vehicle Length and Ground Clearence provided a non-random amount of variance. 

When looking at the p-value you can see that the slope of the model is not considered to be zero. A P Value < .05 indicates it is significantly different then zero. 
The current model predicts an accuracy of 71% which is not a very effective prototype. 

![linear_regression_mpg.png](https://github.com/Adam-Warrick/MechaCar_Statistical_Analysis/blob/main/linear_regression_mpg.png)

## Summary of Statistics on Suspension Coils

We looked at the data from three different lots to get an understanding around the variance permitted by the design specs. The specifications cannot be over 100PSI. Lot 3 is way out of spec, however, lot 1 and 2 are within reason. 

![lot_summary.png](https://github.com/Adam-Warrick/MechaCar_Statistical_Analysis/blob/main/lot_summary.png)

![total_summary.png](https://github.com/Adam-Warrick/MechaCar_Statistical_Analysis/blob/main/total_summary.png)

## T-Test on Suspension Coils

We analyzed the suspension coils using T-Tests. We wanted to see if this was statistically different from the mean of 1,500 PSI. 

The P-Value for all lots combined is slightly higher than .05...coming in at .06. This means that there isn't a statistical difference between the sample mean and the population mean. Lot 1 and Lot 2 appear to not be statistically different. Lot 3, however, is a P-value of .04

![t_test_0.png](https://github.com/Adam-Warrick/MechaCar_Statistical_Analysis/blob/main/t_test_0.png)

![t_test_1.png](https://github.com/Adam-Warrick/MechaCar_Statistical_Analysis/blob/main/t_test_1.png)

![t_test_2.png](https://github.com/Adam-Warrick/MechaCar_Statistical_Analysis/blob/main/t_test_2.png)

![t_test_3.png](https://github.com/Adam-Warrick/MechaCar_Statistical_Analysis/blob/main/t_test_3.png)

## Study Design: MechaCar vs Competition

My next test would be to test Fuel Efficiency in town driving. We would need to perform a two sample t-test. We would use a null hypothesis examining the population means of mechcar and the competitor. We can then add to say that if mechcar has less horse power than the competition, then mechacar will have better fuel efficiency in town. 
