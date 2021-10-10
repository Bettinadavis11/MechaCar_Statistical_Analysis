# MechaCar_Statistical_Analysis
## Project Overview:
The MechaCar is AutosRU's newest prototype is having production issues that are blocking the manufacturing team's progress, and we were called to perform Data Analysis study to help the manufacturing team.

## Linear Regression to Predict MPG:
![Linear Regression](https://user-images.githubusercontent.com/86321353/136704229-c38ff76f-d24f-44eb-9330-2f1f76d2536b.jpg)

### Based on our results we can conclude:
* The vehicle length and ground clearance provide a non-random amount of variance to the mpg since the p values lower than our 0.05 significance level.
* The slope of the linear model cannot be considered zero, as the p value of our analysis is 5.35e-11 which is much lower than our significance level of 0.05, rejecting the null   hypothesis.
* the r-squared value of our model is .71 which means a 71% of the data points will fit in our linear model making it effective at predicting the mpg of MechaCar prototypes.

## Summary Statistics on Suspension Coils:

### Total Summary:
![Total Summary](https://user-images.githubusercontent.com/86321353/136703431-ddd8efe4-1076-4b03-affb-35167a75ac1c.jpg) <br>
The suspension coils variance of 62.29 meets specifications since it does not exceed 100 PSI.
<br>
<br>
### Lot Summary:
![Lot summary](https://user-images.githubusercontent.com/86321353/136703428-81c3bd4d-041d-4f30-ad39-d544d4495953.jpg) <br>
Lot 1 and 2 meet specifications. However, lot 3 does not meet specifications since its calculated variance equals 170.28.

## T-Tests on Suspension Coils:
#### Overall T-Test Results
![T-Test on suspension coils](https://user-images.githubusercontent.com/86321353/136703435-ae9f94b6-b33b-429c-a5b6-96c7f311439d.jpg)<br>
We are unable to reject the null hypothesis that the true mean is equal to 1500 psi since the overall p value significance level is 0.06.<br>
#### Lot 1 T-Test Results
![Lot 1](https://user-images.githubusercontent.com/86321353/136703438-62b1d0c4-ea6b-4e9b-b6f8-724664034f58.jpg)<br>
P-Value for Lot 1 is 1 which is above our significance level of 0.05; which means that the PSI for Lot 1 are statistically different to the population mean.<br>
#### Lot 2 T-Test Results
![Lot 2](https://user-images.githubusercontent.com/86321353/136703442-dec00171-aef5-42f7-b7c1-550bcd37b0a5.jpg)<br>
P-Value for Lot 2 is 0.06 which is above our significance level of 0.05; which means that the PSI for Lot 2 are statistically different to the population mean.<br>
#### Lot 3 T-Test Results
![Lot 3](https://user-images.githubusercontent.com/86321353/136703455-794e81a1-b836-420e-8ebe-c507134eb8cb.jpg)<br>
The evidence shows that lot 1 and lot 2 statistically very similar to both p values. However, lot 3 is statistically similar to the population mean.<br>
## Study Design: MechaCar vs Competition
### Statistical study on MechaCar emissions vs Competition:
* What metric or metrics are you going to test?<br>
  The metrics I think would be beneficial to test would be "Vehicle emissions" since more people are conscious about our environment.<br>
* What is the null hypothesis or alternative hypothesis?<br>
  The null hypothesis will be that the MechaCar produces equal or more emissions that the competition.<br>
  The alternate hypothesis will be that MechaCar produces less emission that the competition.<br>
*	What statistical test would you use to test the hypothesis? And why?<br>
  To show overall comparisons between MechaCar and all competitors, we can run the ANOVA method.<br>
  To show direct comparisons between MechaCar and a particular competitor, we can tun the T-Test.<br>
* What data is needed to run the statistical test?<br>
  We might be able to obtain data from smog centers across the state to obtain emissions from all MechaCar's competition.<br>
