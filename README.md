# Titanic Dataset Analysis

## Overview

This project explores the Titanic dataset, focusing on data cleaning, missing data handling, and data visualization. The dataset contains information about passengers on the Titanic, including their demographics, ticket class, and survival status.

## Dataset

- Dataset: [titanic_train.csv]("https://github.com/ashaneo/Handling-Missing-Elements-in-a-DataSet-with-Mean/blob/main/titanic_train.csv")
- Columns: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

## Data Cleaning and Missing Data Handling

- Checked for missing data using a heatmap.
- Approximately 20% of age data is missing.
- Many data points are missing in the Cabin column.
- Created a function to impute missing ages based on passenger class:
  - If passenger class is 1, age is set to 37.
  - If passenger class is 2, age is set to 29.
  - If passenger class is 3, age is set to 24.
- Updated the Age column with imputed values.

## Data Visualization

- Visualized the survival count using a countplot.
- Explored survival counts based on gender using a countplot.
- Examined survival counts based on passenger class.
- Plotted a histogram of passenger ages.
- Created a boxplot to compare passenger age distributions among different classes.

## Conclusion

- Most passengers who did not survive were males.
- Passengers in class 3 had the highest casualty rate.
- The imputed age values helped in filling missing age data.
