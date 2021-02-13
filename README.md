# MechaCar Statistical Analysis


##  Deliverable 1 - Linear Regression to Predict MPG

### Summary

We were provided data a dataset that contained mpg test results for 50 prototype MechaCars.  The metrics in the dataset included vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance. 


### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle length and ground clearance provide a non-random amount of Variance to the mpg values in the dtataset and both have a high statistical significants.

### Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not considered to be 0 because the p-value is 5.35e-11 which is a lot less than 0.05


### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

This linear model predicts mpg of MechaCar prototypes effectilvely because the model has an r-squared value of 0.7149.  This means that 71% of the time the model would be effective.


## Deliverable 2 - Summary Statistics on Suspension Coils

### Summary

We were provided data a dataset that contained results from mulitple production lots. The datas set had weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots.

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

<b>Total Summary</b><br>
<img src="https://github.com/andralobo/Module15-Challenge/blob/main/Resources/total_summary.png?raw=true" width="auto" height="auto">

<b>Lot Summary</b><br>
<img src="https://github.com/andralobo/Module15-Challenge/blob/main/Resources/lot_summary.png?raw=true" width="auto" height="auto">


The Total Summary table shows 


## Deliverable 3 - T-Tests on Suspension Coils

### Summary

<b>Lot Summary</b><br>
<img src="https://github.com/andralobo/Module15-Challenge/blob/main/Resources/Suspension_lots.png?raw=true" width="auto" height="auto">


## Deliverable 4 - Study Design: MechaCar vs Competition

### Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.


### What metric or metrics are you going to test?

I would test Fuel economy based of vehicle type.


### What is the null hypothesis or alternative hypothesis?

The null hypothesis would state that these performance metrics are stistically similar between MechaCar's vehicles and vehicles from competitors.  

### What statistical test would you use to test the hypothesis? And why?

For this statistical test I would use a one-way ANOVA. This test allows us to see if there are any statically significant differeences between the means of the different vehicle types.  

### What data is needed to run the statistical test?

We would need Data from MechaCar and its competitors to complete this analysis.  We would need the vehicle type and fuel efficiency for both MechCar and its competitors.



