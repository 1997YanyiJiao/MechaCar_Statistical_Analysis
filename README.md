# Module 15

## Linear Regression to Predict MPG

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance and vehicle_length.

* Is the slope of the linear model considered to be zero? Why or why not?

Our slope is not zero just be looking at the p-value, which is less than 0.05.

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

R-squared value is .7149 which is a strong correlation for the dataset.OR 71% of variance between atual and predicted values can be explained by our model.So effectively,yes.

![1](https://user-images.githubusercontent.com/100504550/180364630-5faf3097-f934-44d1-b40f-1b2f9cd6c168.png)


## Summary Statistics on Suspension Coils


The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.
The design specs are respected for all manufacturing lots in total with a global variance of 62.3 psi.
On the lot level, Lot 1 and Lot 2 are into specs with respectively variances of 0.98 and 7.5 psi. The Lot 3 is out of specs with a variance of 170.3 psi.


![Screenshot (270)](https://user-images.githubusercontent.com/100504550/180365357-ea9aff83-9a93-4ba0-bfd9-fbda83e58907.png)

## T-Tests on Suspension Coils
![Screenshot (272)](https://user-images.githubusercontent.com/100504550/180365937-81824caa-d9e4-4b3a-8150-ae72010766b1.png)
* A review of the results of the T-test for the suspension coils across all manufacturing lots shows that they are not statistically different from the population mean, and the p-value is not low enough (0.0603) for us to reject the null hypothesis.
### Lot 1 T-Test
![Lot 1 ](https://user-images.githubusercontent.com/100504550/180366851-06a265aa-36b4-41e2-b94c-4d06c14ee9f0.png)
### Lot 2 T-Test
![Lot 2](https://user-images.githubusercontent.com/100504550/180366888-79b168bb-7e03-4b48-a994-632cc9d5611f.png)
### Lot 3 T-Test
![Lot 3](https://user-images.githubusercontent.com/100504550/180366910-4077e17a-f5cb-4463-8bc0-821289f314f4.png)

## Study Design: MechaCar vs Competition

Another statistical study could be conducted to quantify how the MechCar performs against the competition in fuel efficiency. A one-way ANOVA test can be used to test the fuel efficiency of different cars based on vehicle class. The null hypothesis is that the means of all groups are equal. The data needed to run the ANOVA includes MPG, vehicle class, manufacturer, and model.
