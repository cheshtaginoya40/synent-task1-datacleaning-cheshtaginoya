# Synent Data Science Internship – Task 1

## Project Title
Data Cleaning & Preprocessing of Titanic Dataset

Cheshta Ginoya

## Problem Statement
The goal of this project is to clean and preprocess the Titanic dataset.

## Dataset
Titanic Dataset (kaggle)

The dataset contains passenger details such as:
- PassengerId
- Pclass
- Name
- Age
- Sex
- Fare
- Cabin
- Embarked
- Survival status

## Tools & Technologies Used
- Python
- Pandas
- Jupyter Notebook

## Steps Performed

1. Data Loading  
   - Loaded the dataset using Pandas.

2. Data Inspection  
   - Checked dataset structure using `info()` and `head()`.

3. Handling Missing Values  
   - Filled missing values in Age using mean.
   - Filled missing values in Fare using median.
   - Dropped Cabin column due to many missing values.

4. Removing Duplicates  
   - Checked and removed duplicate records.

5. Data Type Conversion  
   - Converted categorical columns such as Survived, Pclass, Sex, and Embarked.

6. Renaming Columns  
   - Renamed columns for better readability.

## Output
The final cleaned dataset is saved as:

clean_titanic_dataset.csv

This dataset is now ready for further analysis and visualization.

## Key Learning
- Data preprocessing techniques
- Handling missing values
- Working with Pandas DataFrames
- Preparing datasets for analysis
