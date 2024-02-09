# Data Analysis and Visualization 
## Dataset Introduction

- The datasets consist of several medical predictor (independent) variables and one target (dependent) variable -Outcome.
- Independent variables include the number of pregnancies the patient has had, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age.

## Objective
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. 
In particular, all patients here are females at least 21 years old (minimum age in the dataset).

## Methods
The dataset have nine columns(variables/attributes).

📌 Independent attributes are Pregnancies, Glucose, Blood Pressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age.

📌 Dependent variable is Outcome.

### Data unbalanced
📌 Oversampling techniques like SMOTE (Synthetic Minority Over-sampling Technique) can be used for further analysis.

### Handling missing/null values
📌 The missing values '0' is replaced by the median of the variables for the analysis. As there are outliers in the data median is more robust than mean.

📌 Outliers below 1% only those rows are removed from the dataset.

## Libraries used in this analysis
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- stats
  
📌 From the plots, can determine women having high Glucose levels and BMI levels tend to have Diabetes.
