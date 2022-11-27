# School_District_Analysis

## Overview
### Purpose
The purpose for this analysis was to help Maria, the chief data scientist for a school district to analyze data on student funding and standarized test scores to prepare an analysis, reporting, and presentation to provide insights about performance trends and patters.

### Data

The given csv file([new_full_student_data.csv](https://github.com/ninicholasas/School_District_Analysis/blob/main/Resources/new_full_student_data.csv)) was consisted from 8 columns for student id, student name, grade, school name, reading score, math score, school type, and school budget with 14,831 rows. Some rows had null values and some were duplicate, so those rows were removed during the analysis

## Analysis
Here is the full analysis that I have done [Student_Data_Challenge](https://github.com/ninicholasas/School_District_Analysis/blob/main/Unsolved/Student_Data_Challenge_Starter_Code.ipynb)<br />
For this analysis I used Pandas and Jupyter Notebooks to clean and group the given csv file.

First, I removed the rows that had null values and removed the rows that was duplicated by using __.dropna()__ and __.drop_duplicates()__.
Next, I changed the data type for the grade by removing the "th" by using __.str.replace__ and changing the type to integer with __.astype()__.
Further on the analysis was done by getting the average budget for Charter and Public schools, the student count for each school and the average math score for the 9th to 12th grade for each Charter and Public schools.

## Result
As stated in the Jupyter Notebook, the result for this analysis was not enough to determine if the budget has any co-relation with sudents socres.
We sould need to compare the reading score as well as the math and also see on a micro level by analyzing the budget and the test scores for each schools.
