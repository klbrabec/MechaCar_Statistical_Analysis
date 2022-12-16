# MechaCar_Statistical_Analysis

## Overview 

## Linear Regression to Predict MPG 

### Results
(INCLUDE IMAGE OF RESULTS HERE lmimage)

### Questions 
#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
R calculated that the variables that provide a non-random amount of variance to the MPG values are ground_clearance (5.21e-08)  and vehicle_length (2.60e-12). Both have been assigned a significance code of 0.  

#### Is the slope of the linear model considered to be zero?  Why or why not? 
Due to the disparate types of data that are being compared in this model, it is not possible to determine if the slope is zero.   However, reviewing the individual data elements (Length, weight, clearance, AWD and spoiler angle) should be able to identify the slope for that particular model. 

#### Does this linear model predict mpg of MechaCar prototypes effectively?  Why or why not?
This model would allow us to predict the mpg of future MechaCar prototypes.  This assumption can be made because the R-squared value is .7149 and Adjusted R-squared value is .6825.  These values indicate that 71.49% of values will fit within the linear regression models (68.25% of adjusted values).  

## Summary Statistics on Suspsension Coils 

### Results 
#### Total Summary 
(INCLUDE IMGE OF RESULTS HERE - TOTAL SUMMARY)

#### Lot Summary
(INCLUDE IMAGE OF RESULTS HERE - LOT SUMMARY)


### Questions 
#### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

When looked at as a group - all manufacturing locations meet the design specifications for the pounds per square inch of the suspension coils.  However, when looked at individually, lot three misses the requirements, delivering 1496.14 as the mean pounds per square inch.  Further analysis should be done to determine why this is occurring. 

## T-Tests on Suspension Coils 
### Results 
#### All Lots 
INCLUDE IMAGE OF ALL 3 Lots here
#### Lot One 
INCLUDE IMAGE OF LOT 1 
#### Lot Two 
INCLUDE IMAGE OF LOT 2 
#### Lot Three
INCLUDE IMAGE OF LOT 3 

### Summary 
As discussed in the summary statistics for the suspension coils, only lot 3 was out of compliance with the design specifications for the number of pounds per square inch for the coils.  The mean of the PSI values is 1496.14.

## Study Design - MechaCar vs Competition 
In addition to the analysis above, additional studies can be done to determine the competitive stance of MechaCar's products.  One study should be the post purchase or maintenance cost for the car.  This study should cover the overall cost of maintaining a MechaCar for the five years after purchase.   
### Hypothesis
The hypothesis of the study would be that owning a MechaCar would cost less for the first five years than owning any of the other car brands in the study.    The null hypothesis for this study would be that there is no relation between a brand of car owned and the cost of ownership for the first five years.  
### Selection of Testing Models 
Using a multiple linear regression model and related summary statistics, analyze if there is a relationship between the brand of car and the cost of ownership for five years.
### Data used for study 
There are multiple factors used to determine total cost of ownership, maintenance costs (gas types, oil changes, tires, taxes and fees) and insurance costs (various coverage models) are most likely to be used along with miles per gallon as part of the selection process.  