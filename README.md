# **SCHOOL DISTRICT ANALYSIS**

## **Overview of School District Analysis**

This module uses Jupyter Notebook to analyze PyCity school district data. It has been identified that academic dishonesty occured in one of the schools so the data needs to be altered  before. begining the anaylysis.
In this project, I am replacing Thomas High School’s ninth graders results with ‘not a number’(NaN) to exclude them from the anaylsis in order to uphold the testing intergrity of the state testing standards. After replace thoses grades, the analysis will further show how it affected the school district analysis.
 
## Results

- How is the district summary affected?
	- The dstrict summary average math score decreased from 79.0 to 78.9, passing math percent decreased from 75% to 74.8%, passing reading percent decreased from 86% to 85.7% and overall passing percent decreased from 65% to 64.9%.

![Previous District summary](/Resources/initial_district_summary.png)

![Updated District summary](/Resources/new_District_summary.png)

- How is the school summary affected?
	- Thomas High School Passing Reading percent decreased from 97.3% to 69.7%, overall passing percent decreased from 90.9% to 65%

![Thomas High school Summary](/Resources/initial_THS_Summary.png)

![Updated District Summary](/Resources/New_THS_Summary.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 

	- No other school’s performance was affected by replacing Thomas High School ninth graders scores.

- How does replacing the ninth-grade scores affect the following? 
	- Math and reading scores by grade remained the same for other grades and other schools. 
	- Scores by school spending: Scores by school spending stayed the same
![Scores by School Spending](/Resources/scores_by_school_spending.png)

	- Scores by school size stayed the same

![Scores by school size](/Resources/scores_by_school_size.png)
	- Scores by school type stayed the same

![Scores by school type](/Resources/scores_by_school_type.png)

## Summary
Replacing Thomas High school ninth graders grade had little(insignificant) effect on PyCity school district analysis for math and English but had no effect on other schools in the district. Since NaN’s are not counted during the analysis, it will be less likely to affect the district analysis.


