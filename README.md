### MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG
The ground clearance & vehicle length coefficients provided a non-random amount of variance to the mpg values in the dataset.
The slope of the linear model would be considered non-zero based on the p-value.
This linear model predicts mpg of MechaCar protypes effectively based off the r-squared value.

![MPG_Linear_Regression](https://github.com/abeituni/MechaCar_Statistical_Analysis/blob/main/LinearRegressionMPG.png?raw=true)


## Summary Statistics on Suspension Coils
The variance does not exceed 100lbs per square inch in Lot 1 & 2. However, Lot 3 has a variance whcih exceeds that requirement.

![Total_Summary](https://github.com/abeituni/MechaCar_Statistical_Analysis/blob/main/Total_Summary.png?raw=true)

![Lot_Summary](https://github.com/abeituni/MechaCar_Statistical_Analysis/blob/main/Lot_Summary.png?raw=true)


## T-Tests on Suspension Coils
Based off the T-Tests we performed, Lot 1 & 2's p-value makes it not low enough to reject the null hypothesis. However, Lot 3's p-value allows us to reject the null hypothesis.


![TTest](https://github.com/abeituni/MechaCar_Statistical_Analysis/blob/main/TTest.png?raw=true)

![LotTTests](https://github.com/abeituni/MechaCar_Statistical_Analysis/blob/main/Lot123TTest.png?raw=true)

## Study Design: MechaCar vs Competition
Fuel Efficiency is a very important factor when purchasing a vehicle. The null hypothesis would be to make sure there is little to no signifcance in fuel efficency. The alternative hypothesis would be that there is a significant differnce in fuel efficiency. A statistical test we could use to test the hypothesis would be a z-score. We'll need data from other car manufactureres as well when testing out our hypothesis.