# School_District_Analysis
## Project Overview
The purpose of this project is helping Maria to do the analysis of the school district. However, due to the academic dishonesty, we need to replace reading and math grades for Thomas High School ninth graders with Nan first.

Then, we need do following analysis:
*A high-level snapshot of the district's key metrics, presented in a table format
*An overview of the key metrics for each school, presented in a table format
*Tables presenting each of the following metrics:
*Top 5 and bottom 5 performing schools, based on the overall passing rate
*The average math score received by students in each grade level at each school
*The average reading score received by students in each grade level at each school
*School performance based on the budget per student
*School performance based on the school size 
*School performance based on the type of school

## Resources
Data Resource: schools_complete.csv and students_complete.csv
Software: PythonData environment in Jupyter Notebook

## Results
*How is the district summary affected?
% Passing Math decreased from 75% to 74.8%
% Passing Reading decreased from 85.8% to 85.7%
% Overall Passing decreased from 65.17% to 64.9%

*How is the school summary affected?
The original summary are  93.272171% passing math,	97.308869% passing reading and	90.948012% overall passing.
1) Only change 9th grade to Nan, the school summary of Thomas became to 66.911315% passing in math,	69.663609% passing in reading, and 65.076453% in overall.
2) Replace the number of Thomas by the percentage of 10th-12th grade students, then the passing percentage will back to 93.185690% ,	97.018739% , and	90.630324%.


*How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
There is no affect Thomas High School's performance relative to the other schools.


*How does replacing the ninth-grade scores affect the following:

**Math and reading scores by grade

Thomas's Math and reading scores became to Nan.

**Scores by school spending

The scores by school spending between $630 and $644 has changed. They became to 78.502002, 81.636261, 73.462589, 84.319261	and 62.778233.

**Scores by school size

No changes

**Scores by school type

No changes

## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs: 
  
1. Thomas's school data 
2. The school summary (percentage of passing in math, reading and overall)
3. The scores by school spending
4. The math and reading scores by grade
