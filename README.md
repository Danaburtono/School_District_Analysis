# School_District_Analysis
## Overview of the school district analysis: Explain the purpose of this analysis.

Purpose of the analysis is to present reading and math scores across the district by school, grade level, school type (District or Charter), school population size. The main focus of the analysis was to determine if the data provided by Thomas High School 9th grade class was cheating on the exams. The school board asked for the the data from Thomas High Schools 9th grade be stricken from the analyis. 461 9th graders at Thomas High School were turned to NaN's. 

### Procedure 
Open Jupyter Notebook files from local directories using a development environment.
Read an external CSV file into a DataFrame.
Format a DataFrame column.
Determine data types of row values in a DataFrame.
Retrieve data from specific columns of a DataFrame.
Merge, filter, slice, and sort a DataFrame.
Apply the groupby() function to a DataFrame.
Use multiple methods to perform a function on a DataFrame.
Perform mathematical calculations on columns of a DataFrame or Series.

### Results: 
#### How is the district summary affected?

Original Analysis: 
% Passing Math 74.9%
% Passing Reading 85.8%
% Overall Passing 65.2%

![District_preedit](https://user-images.githubusercontent.com/107026442/179453781-8ed1f1ee-1885-465e-a192-e1c832a4a866.png)
sing 65.2%

Adjusted Analysis without Thomas High School 9th Graders: 
% Passing Reading 73.9%
% Passing Math 84.7%
% Overall Passing 64.1%

![district_postedit](https://user-images.githubusercontent.com/107026442/179453812-5f67f818-adec-438b-ba5c-35e165a15e40.png)

There was less than 1% difference between original and adjusted analysis.
### How is the school summary affected?

Original Analysis: 
% Passing Reading 93.2%
% Passing Math 97.3%
% Overall Passing 90.9%

Adjusted Analysis without Thomas High School 9th Graders: 
% Passing Reading 93.1%
% Passing Math 97.0%
% Overall Passing 90.6%



### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High Schools 9th grade math and reading scores are negigliable and make little difference relative to other schools in the district. 


### How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade

Original Math Scores by grade
9th Grade 
10th Grade
11th Grade 
12th Grade

### Original Reading Scores by grade
9th Grade 
10th Grade
11th Grade 
12th Grade

### Scores by school spending
no difference 

### Scores by school size
no difference 
Scores by school type
no difference

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
