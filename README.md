# Data Analysis and Visualization 
## Dataset Introduction

- The datasets consist of several medical predictor (independent) variables and one target (dependent) variable -Outcome.
- Independent variables include the number of pregnancies the patient has had, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age.

## Objective
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. 
In particular, all patients here are females at least 21 years old (minimum age in the dataset).

## Methods
The dataset have nine columns(variables/attributes) in which there are eight independent variables (Pregnancies,Glucose,Blood Pressure,SkinThickness,Insulin,BMI,DiabetesPedigreeFunction,Age) and one dependent variable (Outcome).

- In the Dataset the data is unbalanced. The number of non-diabetic (outcome = 0) is 500 the number of diabetic (outcome = 1) is 268. Some the oversampling techniques like SMOTE (Synthetic Minority Over-sampling Technique) can be used for further analysis.
- Some of the variables do not contain any null values (missing values). However, this can not be true. The variables Insulin,SkinThickness,BloodPressure,BMI,Glucose have zero values.
- The missing values '0' is replaced by the median of the variables for the analysis. As there are outliers in the data median is more robust than mean.
- Some variables like BloodPressure,SkinThickness,Insulin,BMI have outliers, hence there are not many datapoints in the dataset (not being a large dataset), the data is not removed from these. However for Pregnancies there are outliers below 1% only those rows are removed from the dataset.

## Analysis
- In the analysis part, Some of the variables like Glucose,BMI,Age can see little correlation with the outcome. And also Pregnancies and age, BMI and Skinthickness also show some correlation by looking at the heat map.
- After plotting on the charts, there is no convincing relationship can be seen between Pregnancies and Age, BMI and skinthickness. However if it is a large dataset then can determine the relationship between these variables.
- Pregnant women more prone to get the Diabetes. Some studies shows some pregnant women will get diabetes but will go after their pregnancy. As the Diabetes during Pregnancy may not last long but there are chances of getting back when they become old.
- From the plots, can determine women having high Glucose levels and BMI levels tend to have Diabetes.
