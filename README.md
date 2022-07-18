# School_District_Analysis
## Overview

Purpose of the analysis is to present reading and math scores across the district by school, grade level, school type (District or Charter), school population size. The main focus of the analysis was to determine if the data provided by Thomas High School 9th grade class was cheating on the exams. The school board asked for the the data from Thomas High Schools 9th grade be stricken from the analyis. 461 9th graders at Thomas High School were turned to NaN's. 

## Procedure 
Open Jupyter Notebook files from local directories using a development environment.<br />
Read an external CSV file into a DataFrame.<br />
Format a DataFrame column.<br />
Determine data types of row values in a DataFrame.<br />
Retrieve data from specific columns of a DataFrame.<br />
Merge, filter, slice, and sort a DataFrame.<br />
Apply the groupby() function to a DataFrame.<br />
Use multiple methods to perform a function on a DataFrame.<br />
Perform mathematical calculations on columns of a DataFrame or Series.<br />

## Results: 
### How is the district summary affected?

**Original Analysis:**<br />
Passing Math 74.9%<br />
Passing Reading 85.8%<br />
Overall Passing 65.2%<br />

![District_preedit](https://user-images.githubusercontent.com/107026442/179453781-8ed1f1ee-1885-465e-a192-e1c832a4a866.png)

**Adjusted Analysis without Thomas High School 9th Graders:**<br />
Passing Reading 73.9%<br />
Passing Math 84.7%<br />
Overall Passing 64.1%<br />

![district_postedit](https://user-images.githubusercontent.com/107026442/179453812-5f67f818-adec-438b-ba5c-35e165a15e40.png)

There was less than 1% difference between original and adjusted analysis.

### How is the school summary affected?

**Original Analysis:**<br />
Passing Reading 93.2%<br />
Passing Math 97.3%<br />
Overall Passing 90.9%<br />

![scores_with_9thgrade](https://user-images.githubusercontent.com/107026442/179454273-aecf0fd8-9b7d-4be4-89aa-46258932fcf9.png)

**Adjusted Analysis without Thomas High School 9th Graders:**<br />
Passing Reading 93.1%<br />
Passing Math 97.0% <br />
Overall Passing 90.6%<br />

<img width="811" alt="Screen Shot 2022-07-17 at 11 12 14 PM" src="https://user-images.githubusercontent.com/107026442/179454160-19b63f0a-5c12-4596-972c-204d41c20290.png">

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High Schools 9th grade math and reading scores make no realative difference to other schools in the district. 

### How does replacing the ninth-grade scores affect the following:<br />
Replacing ninth grade scores did not substantially affect-
 - the math and reading scores by grade<br />
 - school spending<br />
 -  school size<br />
 -  school type<br />

## Summary

1. The overall passing rate for Thomas High School changed dramatically from 90.94% to 90.63%.

2. Thomas High School's ranking dropped from 2nd to 3rd in the district of 15 campuses.

3. Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School.

4. At the district level, the percentage passing is 1% less. 

