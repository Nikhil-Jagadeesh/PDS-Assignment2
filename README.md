**Used Cars Data Analysis**
This repository contains the code and analysis for the assignment on used cars data. The dataset includes various details and attributes associated with used cars, with the target variable being the price of the used cars measured in lakhs.

Tasks
a) Handling Missing Values
Identified and handled missing values in all columns.
For categorical columns, imputed missing values with the mode to preserve existing data.
For numerical columns, imputed missing values with the mean to maintain distribution and central tendency.
b) Removing Units
Removed units from certain attributes to keep only numerical values.
Example: Removed "kmpl" from "Mileage," "CC" from "Engine," "bhp" from "Power," and "lakh" from "New_price."
c) Categorical to Numerical Transformation
Transformed categorical variables ("Fuel_Type" and "Transmission") into numerical one-hot encoded values.
d) Additional Feature Creation
Calculated the current age of the car by subtracting the "Year" value from the current year.
Added the new feature to the dataset.
e) Data Manipulation Operations
Performed various data manipulation operations, including select, filter, rename, mutate, arrange, and summarize with group by operations.
