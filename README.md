TITANIC TASK 1 - DATA PREPROCESSING

This repository contains my internship submission for Task 1, which involved cleaning and preprocessing the Titanic dataset.

ABOUT THE TASK

The goal of this task was to:
- Load the Titanic dataset
- Identify and handle missing values
- Encode categorical columns like 'Sex' and 'Embarked'
- Normalize numerical features like 'Age' and 'Fare'

 WHAT I DID

- Filled missing values in 'Age' with median
- Filled missing 'Embarked' values with mode
- Dropped the 'Cabin' column due to too many missing values
- Converted 'Sex' into numerical format using map
- Applied one-hot encoding to 'Embarked'
- Scaled 'Age' and 'Fare' using StandardScaler

 FILES INCLUDED

- task1-data-preprocessing.ipynb: Jupyter Notebook containing the full code for the preprocessing steps

 TECHNOLOGIES USED

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

 AUTHOR
-Divyadharshini
-
