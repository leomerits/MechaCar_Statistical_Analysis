# MechaCar_Statistical_Analysis
# Overview of Project
In this project, we are helping Jeremy in his new role to accomplish a special project required of him from the upper management. We were able to help Jeremyand his data analytics team achieve the following;
- Perform multiple linear regresion analysis to to identify which variables in the dataset that predicts the MPG of MechaCar prototypes.
- Collect summary statistics on the PSI of the suspension coils from the manufacturing lots.
- Run t=test to determone if the manufacturing lots are statistically different from the mean population.
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

# Deliverable 1:
## Linear Regression to Predict MP
For this deliverable, MechaCar_mpg.csv file was imported and read, RScript was written for a linear regression model to be performed on all six variables, RScript was written to create the statistical summary of the linear regression model with the independent p-values as shoen below, and from the analysis, we found out that;
- Linear model has r-squared value of 0.7149 which implies athat approximately 71% of all MPG predictions will be effectively determined by the model.
- That the length and ground clearance of a vehicle are statistically likely provide non-random amounts of variance to a model meaning that lenght and clearance of a vehicle might have significant impact on MPG on the MechaCar prototype whereas the wight, spoiler angle and AWD do have p-values that indicate a random amount of variance with the dataset.
- Also the p-value of 5.35e-11 of this model is smaller than the significant level of 0.05% meaning that is ok to reject our null hypothesis.

![image](https://user-images.githubusercontent.com/34757498/148311859-9deca978-9853-4ca4-93f7-f5f9d96647d4.png)

![image](https://user-images.githubusercontent.com/34757498/148311947-965bf8d0-9ff4-47c7-9997-8390b6543b84.png)

![image](https://user-images.githubusercontent.com/34757498/148312050-7eeec867-deb9-4cd6-852d-8752c8bfe894.png)

# Deliverable 2:
## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/34757498/148337010-8c503483-8530-49b2-a913-3a14c42ba944.png)

And the Total Summary:
![image](https://user-images.githubusercontent.com/34757498/148337142-9741e70a-44b0-43f8-8231-0b115451e8e7.png)

# Deliverable 3:
## T-Tests on Suspension Coils
We write RScripts for t-test that compares all manufacturing lots, as well as individual lots against:
- Mean PSI
- Median PSI
- Variance PSI
- SD PSI
All Lots:
![image](https://user-images.githubusercontent.com/34757498/148337829-506de61f-1868-4874-af9c-a60e8961349f.png)

Lot1:
![image](https://user-images.githubusercontent.com/34757498/148337998-5444bcae-8245-4a14-a60b-0fc3cac3b532.png)

Lot2:
![image](https://user-images.githubusercontent.com/34757498/148338087-44c3f69b-d77b-4ef4-85ff-5721958f7c27.png)

Lot3:
![image](https://user-images.githubusercontent.com/34757498/148338209-2500f33f-1624-4c94-b615-21a7df247899.png)

# Deliverable 4:
## Study Design: MechaCar vs Competition
We were able to usecollected information on MechaCar and its comparable models regarding
- The competitors's comparable models.
- Which vehicles to be competing with head to head.
- Which vehicles will be in the study.
- What factors are considered relevant?

The metrics in this considerations includes:
1. Safety features
2. Current selling price.
3. Engine type.
4. Packages
5. Resale value
6. Maintenance cost
7. MPG.
As we can see from the analysis, using multiple linear regression to determine which factor has the highest correlation or predictability helps in getting a clearer idear for a better decision.
