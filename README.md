# MechaCar_Statistical_Analysis
## Linear Regression to predict MPG
<img width="1432" alt="MechaCarChallenge_Deliverable1" src="https://user-images.githubusercontent.com/82982480/128568934-ff96dccf-7a1d-40c6-b8de-839b76aaa77f.png">

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The following variables based upon their Pr(>|t|) score are unlikely to provide a non-random variance: the Intercept, Vehicle Length and Ground Clearance. With the Intercept having a high level of statistical significance, it means there are other variables and factors that contribute to the variation in mpg.

### Is the slope of the linear model considered to be zero? Why or why not?
The Slope is not considered to be zero. If there is no significant linear relationship, each dependent value would be determined by random chance and error. As seen in the question above and the data, there is a sigificant linear relationship, therefore our slop is not considered zero.

### Does this linear model predict mpg of MechaCar prototypes e ffectively? Why or why not?
The R-Squared value of 0.7149 indicates that it is an effective model to predict mpg, although it may be guilty of overfitting given the lack of significant variables (only vehicle length and ground clearance)

## Summary Statistics on Suspension Coil
<img width="1436" alt="MechaCarChallenge_Deliverable2" src="https://user-images.githubusercontent.com/82982480/128568966-58673bed-ea22-4797-bf8e-eb03d521099b.png">
In total the variance of the suspension coils meets the design specifications as seen in the Total Summary data. 
However, in the Lot Summary data we see that both Lots 1 and 2 have very low variance, while within the design specifications, but Lot 3, with a variance of over 220 falls why outside the requirement.

## T-Tests on Suspension Coils
<img width="1426" alt="MechaCarChallenge_Deliverable3_1" src="https://user-images.githubusercontent.com/82982480/128568994-416bede9-6a46-4093-8388-fe97da5b01ef.png">
Overall our Suspension Coil T-test is statistically signicant and we would not reject the null hypothesis.
Within each lot, the p-value is less than 0.05, and we would reject our Null Hypothesis.
<img width="1427" alt="MechaCarChallenge_Deliverable3_2" src="https://user-images.githubusercontent.com/82982480/128569009-c61ae4b6-42bd-4d2a-960e-caf95ad6e289.png">

## Study Design: Mechacar vs. Competition
How does the MechaCars perform vs. the competion on: City/Hwy MPG; horsepower and safety; all versus price? We want to determine whether the MechaCar performs better on these metrics vs. the cost of the car, vs. its competition.
Metrics that will be measured are: Price, MPG-City, MPG-huighway and Horsepower.
Null hypothesis: There is no significant difference between the competition and the MechaCar.
Alternative Hypothesis: there is a significant differecne between the competition and the MechaCar.
I will need the following metrics for each competitor and the MechaCar: Price, HorsePower, MPG-City, MPG-Highway. I will run the following tests:
Chi Square Test - deterimine frequency between groups.
Two Sample T-Tests - Is there a difference between the sample groups?
Anova sample for the two groups.


