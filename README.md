Task 1) 

Read in the DentalClaims.csv file into R. Name the resulting dataframe, Dental.
Remove the ID column. Convert the columns (Tier, Procedure, Occupation, and Claim) into
factor columns, not integer. Convert the Gender column from a categorical to a mapping where
M = 1 and F = 2. Convert Provider so that N=0, A=1, B=2, C=3, D=4. Create a subset dataset of
your cleaned up Dental dataset where Claim == 1 and name it DentalClaims.

Task 2) 
Create your best Simple Linear Regression model using the DentalClaims dataset where
the response (dependent) variable is Paid. Be sure to split your dataset for training and testing
(using a seed of 123).

Task 3) 
Create your best Multiple Linear Regression model using the DentalClaims dataset
where the response (dependent) variable is Paid.

Task 4) 
Use your best continuous regression model to make a prediction of a Paid claim amount
with the following characteristics:

• Tier = 1

• Gender = M

• Age = 35

• Procedure = 4

• Occupation = 1

• Provider = 3

Task 5) 
Create a logistic regression model using the original DentalClaims.csv file. The
response variable is Claim. The independent variables are Tier, Gender, Age, and Occupation.
Use a seed of 123 to split your data into a training set and a testing set. Produce a Confusion
Matrix to evaluate your model. 
