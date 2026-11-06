# Task 1: Data Collection and Cleaning

Internship task for Rhombix Technologies (Data Analysis).

## Dataset
Titanic dataset from Kaggle (train.csv): 891 rows, 12 columns.

## What I did
- Checked for duplicate rows (none found)
- Filled 177 missing Age values with the median
- Filled 2 missing Embarked values with the mode
- Dropped the Cabin column (77% missing)
- Fixed formatting: lowercase column names, trimmed text, age as integer

## Result
Cleaned dataset with 891 rows, 11 columns and 0 missing values.

## Files
- `task1_datacleaning.ipynb`: Python notebook with code
- `titanic_cleaned.csv`: cleaned dataset

## Tools
Python, Pandas, Google Colab
