Problem Statement: We are trying to Predict the price of Health Insurace that a person need to pay to an insurance company.

Solution: TO solve the business problem we will be using machine learning models to predict the price of the Health Insurance.
Since this a regression problem here we are given Xi's and Yi so we need to predict the out put which is Yi So you will be knowing that Regression is defined as Yi=Xi for any R^d or R real value.

Data Set: Our data set contains of following columns
          1. Age
          2.Sex
          3.BMI
          4. Number of children
          5. Smoker
          6. Region
          7. Charges (output)
Data Pre-processing steps:1. we need to find any missing values or null values is present in our data.
                          2. We need to find any outliers is there in our data.
Feature Engineering: Since we all know that in order to apply Machine Learning we should convert all categorical variable to numerical format.
So here we have converted few categorical variables to numberical format.

Then after feature Engineering and data cleaining process we are proceeding with building Machine Learning Models.

Machine Learning: We have applied below models to our train data set
                  1. Linear Regression
                  2. SVM (Support Vector Machine)
                  3. RandomForest
                  4. GradientBoosting
Conclusion: Random Forest is predicting more closely to actual value than other models so we will be using Random Forest to Predict the price of Health Insurace.


          
