# MechaCar_Statistical_Analysis

## Overview 

## Linear Regression to Predict MPG 

### Results
![Linear Regression Results](https://github.com/klbrabec/MechaCar_Statistical_Analysis/blob/main/lmimage.JPG)

### Questions 
#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
R calculated that the variables that provide a non-random amount of variance to the MPG values are ground_clearance (5.21e-08)  and vehicle_length (2.60e-12). Both have been assigned a significance code of 0.  

#### Is the slope of the linear model considered to be zero?  Why or why not? 
All individual dimensions within this linear model are non zero slopes (with the exception of the Intercept which is not a slope at all) 

#### Does this linear model predict mpg of MechaCar prototypes effectively?  Why or why not?
This model would allow us to predict the mpg of future MechaCar prototypes.  This assumption can be made because the R-squared value is .7149 and Adjusted R-squared value is .6825.  These values indicate that 71.49% of values will fit within the linear regression models (68.25% of adjusted values).  However, the model would be more effective if the R values were higher (.9000 or higher would be optimal) 

## Summary Statistics on Suspension Coils 

### Results 
#### Total Summary 
![Total Summary](https://github.com/klbrabec/MechaCar_Statistical_Analysis/blob/main/totalsummary.JPG) 

#### Lot Summary
![Lot Summary](https://github.com/klbrabec/MechaCar_Statistical_Analysis/blob/main/lotsummary.JPG)


### Questions 
#### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

When looked at as a group - all manufacturing locations meet the design specifications for the pounds per square inch of the suspension coils.  However, when looked at individually, lot three misses the requirements, delivering 1496.14 as the mean pounds per square inch.  Further analysis should be done to determine why this is occurring. 

## T-Tests on Suspension Coils 
### Results 
#### All Lots 
![ALL Lots TTest](https://github.com/klbrabec/MechaCar_Statistical_Analysis/blob/main/T-test_all.JPG)
#### Lot One 
![Lot 1 TTest](https://github.com/klbrabec/MechaCar_Statistical_Analysis/blob/main/t-test_lot1.JPG))
#### Lot Two 
![Lot 2 TTest](https://github.com/klbrabec/MechaCar_Statistical_Analysis/blob/main/T-test_lot2.JPG)
#### Lot Three
![Lot 3TTest](https://github.com/klbrabec/MechaCar_Statistical_Analysis/blob/main/T-test_lot3.JPG)

### Summary 
As discussed in the summary statistics for the suspension coils, only lot 3 was out of compliance with the design specifications for the number of pounds per square inch for the coils.  The mean of the PSI values is 1496.14.

## Study Design - MechaCar vs Competition 
In addition to the analysis above, additional studies can be done to determine the competitive stance of MechaCar's products.  One study should be the post purchase or maintenance cost for the car.  This study should cover the overall cost of maintaining a MechaCar for the five years after purchase.   
### Hypothesis
The hypothesis of the study would be that owning a MechaCar would cost less for the first five years than owning any of the other car brands in the study.    The null hypothesis for this study would be that there is no relation between a brand of car owned and the cost of ownership for the first five years.  
### Selection of Testing Models 
Using a multiple linear regression model and related summary statistics, analyze if there is a relationship between the brand of car and the cost of ownership for five years.
### Data used for study 
There are multiple factors used to determine total cost of ownership, maintenance costs (horsepower, gas types, oil changes, tires, taxes and fees) and insurance costs (various coverage models) are most likely to be used along with miles per gallon as part of the selection process.







##### Rubric Review 
###### Linear Regression to Predict MPG (30 points)
-- The MechaCar_mpg.csv file is imported and read into a dataframe (5 pt) (done)
-- An RScript is written for a linear regression model to be performed on all six variables (10 pt) (done)
-- An RScript is written to create the statistical summary of the linear regression model with the intended p-values (10 pt) (done)
-- There is a summary that addresses all three questions (5 pt) (done)

###### Create Visualizations for the Trip Analysis (30 points)
-- The csv file is imported and read into a dataframe (5 pt) (done)
-- The total summary dataframe has the mean, median, variance, and standard deviation for all manufacturing lots (10 pt) (done)
-- The lot summary dataframe has the mean, median, variance, and standard deviation for each manufacturing lot individually (10 pt) (done)
--There is a summary that addresses the design specification requirement for all the manufacturing lots and each lot individually (5 pt) (done)

####### T-Tests on Suspension Coils (20 points)
-- An RScript is written for t-test that compares all manufacturing lots against mean PSI of the population (5 pt) (done)
-- An RScript is written for three t-tests that compare each manufacturing lot against mean PSI of the population (10 pt) (done)
-- There is a summary of the t-test results across all manufacturing lots and for each lot (5 pt) (done)

####### Design a Study Comparing the MechaCar to the Competition (20 points)
-- A metric to be tested is mentioned (5 pt) (done)
-- A null hypothesis or an alternative hypothesis is described (5 pt) (done)
-- A statistical test is described to test the hypothesis (5 pt) (done)
-- The data for the statistical test is described (5 pt)
