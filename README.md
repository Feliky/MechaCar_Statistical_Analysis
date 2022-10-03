# MechaCar Statistical_Analysis

The MechaCar production is in troubles with its production. AWD and MPG were given to perform data analysis to help the manufacturing team understand why the delay in production. 

# Results

# Deliverable #1 - Linear Regression to Predict MPG

## Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The p value in column "Pr" helps determine the relationships observed in the sample also exist in the larger population. It  test the null hypothesis that the variable (vechicle length, vehicle weight, spoiler angle, ground clearance and AWD) has no correlation with dependent varialble (MPG).

In summary the calculated linear regression model shows that the vehicle length, ground clearance and the Intercept have a  smaller value than 0.05 which would indicate that the null hypothesis for those variable can be rejected. These variables are probably not random.

![multiple_linear](https://user-images.githubusercontent.com/84817579/193487013-727ca2f8-ed78-458c-819a-e1395e69ea26.png)
![multiple_linear_summary](https://user-images.githubusercontent.com/84817579/193487017-05c95cc4-f9c4-4245-a1a9-edfec6f738de.png)

* Is the slope of the linear model considered to be zero? Why or why not?

No is not considered to be zero. The slope of the linear P-value for the intercept is smaller than the stated significance level of 0.05. Meaning the intercept is not zero and is significantly impactful in regards to the MPG.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not? 

Linear Models that have an R-Squarded value of 0.70 or more are considered effective models. The R-Squarded value, highlighed in yellow, is 0.071.

![R-Squared](https://user-images.githubusercontent.com/84817579/193487141-265e6a7d-eab2-4811-9038-a454ea43f586.png)

# Deliverable #2 - Summary Statistics on Suspension Coils

## Total Summary

![total_summary](https://user-images.githubusercontent.com/84817579/193488580-1902df3e-c6e6-4a43-8780-b5e4f6f2d3bc.png)

## Lot Summary

![lot_summary](https://user-images.githubusercontent.com/84817579/193488627-ad611eda-537a-4289-a335-127d551f7e8a.png)

The design specifications for the MechaCar suspension coils must not exceed 100 pounds per square inch. 

Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 1 and 2 both meet the specification of 1500, but Lot 3 is does not.

# Deliverable #3 - T-Tests on Suspension Coils

Our null hypothesis = Mean is 1500 and our alternative hypothesis = Mean is not 1500.

The level significance is 0.05. Lot 1 and Lot 2 have a p-value of 0.06028 and 1, respecitively. We cannot reject the null hypothesis. Lot 3, with a p-value of 0.04168 less than 0.05, can be rejected the null hyothesis for Lot 3.

## T-Tests Across All Manufacturing Lots

![t_test_All](https://user-images.githubusercontent.com/84817579/193488824-46caabe1-098f-420a-aa6b-89d03ad4cc6b.png)

## T-Tests Across Manufacturing Lot 1 Only

![t_test_Lot1](https://user-images.githubusercontent.com/84817579/193488920-26eec911-c6ef-414a-a1a4-067914e18337.png)

## T-Tests Across Manufacturing Lot 2 Only

![t_test_Lot2](https://user-images.githubusercontent.com/84817579/193489014-7aedaadf-71eb-45be-b3c9-5b7ea3f4d316.png)

## T-Tests Across Manufacturing Lot 3 Only

![t_test_Lot3](https://user-images.githubusercontent.com/84817579/193489053-7ae5281f-d50f-48fd-ae7f-bb2670d4f83d.png)

# Deliverable #4 - Study Design: MechaCar vs Competition

We would need data for the past years to analyze whether trend for particular car types changes over the years. 

Finally, to compare the MechaCar with other competitors, the metrics of interests to consumers would be mileage, safety ratings, highway MPG, price, citg MPG,  price and number of passengers by car model and year. Data should be aggregated in a way that makes the comparison the same. Null and alternative hypothesis vehicle size has no significant effect on car price
.
