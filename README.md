# MechaCar_Statistical_Analysis   

## Overview   
This analysis is to review data on the MechaCar's performance data.   

### Objectives   
* Find which variables closely predicts the MPG for vehicle prototypes.   
* Present summary statistics of the suspension coils' PSI.   
* Test if manufacturing lots have a statistically significant difference from the population's mean.      
* Propose a new study to compare the MechaCar's performance against other vehicles in the market.   

## Results   
### Linear Regression to Predict MPG   
![Pic](https://github.com/ajsadowy/MechCar_Statistical_Analysis/blob/main/images/Deliverable1.png)
With the data presented we can see the vehicle length and ground clearance are statistically significant and provides little variation to the model. Weight, spoiler angle, and AWD have high p-values that suggest that these resultes could be random variances.   
   
With the r-square value at 0.68 we can assume that the mpg can be roughly (68% of the time) predicted.   
### Summary Statistics on Suspension Coils   
![Pic](https://github.com/ajsadowy/MechCar_Statistical_Analysis/blob/main/images/Total_Suspension_Coil.png)   
![Pic](https://github.com/ajsadowy/MechCar_Statistical_Analysis/blob/main/images/Suspension_Coils_by_Lots.png)  
The overall variance shown for the Total Summary data is under the 100 psi specifications, the variance for Lot3 (170) shows a potential outlier for the data.

### T-Tests on Suspension Coils   
![Pic](https://github.com/ajsadowy/MechCar_Statistical_Analysis/blob/main/images/Deliverable3.png)
The t-test shows for Lots 1 and 2 that the p-value is not low enough to reject a null hypothesis while Lot 3 could be argued that for the data collected a p-value of 0.04 could be enough to reject the null hypothesis.
### Study Design: MechaCar vs Market Competition   
The next study should be conducted to see the reliablility of the vehicles.   
New hypothesis: The maintenance cost of the MechaCar is a factor to its overall price.
#### New Metric Test   
The maintenance cost of ownership for the vehicle.     
#### Null Hypothesis   
If the maintenance cost is not a factor, then the overall price will not be affected.
#### Statistical Test to Use  
We can begin with linear regression to determine if the maintenance cost is a factor based on its correlations with the listing selling price.
#### Data That Needs Collecting   
Cost of each repair bill or maintenance (ie tire rotation, fluid changes, etc).
