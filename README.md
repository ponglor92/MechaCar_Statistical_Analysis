# MechaCar_Statistical_Analysis

## Linear Regression To Predict MPG

![output from linear regression](https://user-images.githubusercontent.com/101531875/183807873-a724e00f-9348-402f-be4d-80344da4c905.png)

- The variables that provided non- random amount of variance to mpg were vehicle length and ground clearance. Both of their p- values are extremely small meaning that they had high level of significance.
- No, it is not to be considered zero, because the linear regression shows how some independent variables are affceted by the dependent variables. 
- Because we are going by the R-dquared value, the percentage is 71% because according to the output from the linear regression, the r-squared value is 0.7149, meaning the effectiveness is 71% out of 100%. Therefore, the model would be considered effective.

## Summary Statistics on Suspension Coils

Below are the two dataframes: "total summary and lot summary" I createdm for suspension coil PSI's.The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data does meet this design specification for all manufacturing lots in total. However, individually, only lots 1 and 2 meet the specification. Both lot 1 and 2 had a variance of 0.97 and 7.46, but lot 2 has a variance of 170.28, exceeding the 100 pound per square inch specification. 

![total summary](https://user-images.githubusercontent.com/101531875/183811059-a3daaf5f-3c9e-495c-907f-7933d6abf071.png)
![lot summary](https://user-images.githubusercontent.com/101531875/183813060-c251d9ac-7319-490f-b2d6-6cc7594fa0b2.png)

## T-Tests on Suspension Coils
Below are T-test for each manufacturing lot, and they all differ from each other. The p- values are all close in range but not exactly the same, however that is not enough statistical evidence to say all manufaturing lots are differnt from each other. Also, the mean for each of the individual lots are very close to the population mean of 1,500 PSI.
T-test for all manufacturing lots
![ttest for all lots](https://user-images.githubusercontent.com/101531875/183815475-372d2e1e-f965-4655-b300-19399354c885.png)

T-test for manufacturing lot 1:
![ttest lot 1](https://user-images.githubusercontent.com/101531875/183815533-3f2d4e57-5c8d-4570-a40d-ae4b24e82bdf.png)

T-test for manufacturing lot 2:
![ttest lot 2](https://user-images.githubusercontent.com/101531875/183815614-0b26d04d-3318-4cc0-b483-c00b7259d091.png)

T-test for manufacturing lot 3:
![ttest lot 3](https://user-images.githubusercontent.com/101531875/183815675-6e64382d-8af0-41ad-ba5e-6590eeafda2d.png)

## Study Design: MechaCar vs Competition
When buying a car, consumers are looking at many factors such as gas, model, safety, the year of the car, etc. Now in days, to maintain a car is expensive because everything is going up. Therefore, the consumers will be looking to buy a car that helps them economically to transport themselves on a regular daily basis with no problem (for the most part).

-Metric to test: because the consumer wants a car that can help them economically, we should measure MechaCars carrying capacity in cubic inches. This is to measure how big the car is.
- Null and Alternate Hypothesis: The null hypothesis would be that, all vehicles of the same class has the same carrying capacity. The Alternate hypothesis would be, MechaCar's carrying capacity is above of the competitots vehicle.
- Statistical test used: Two- sample t-tests
- Data needed: for the data, we would be the measurements of the cubic space from the car such as the compartments, seats, etc. 
