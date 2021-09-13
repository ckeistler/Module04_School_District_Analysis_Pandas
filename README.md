# School_District_Analysis

## Overview of the school district analysis: 
Module 4 provided 2 csv files, one with student data, and another with school system data. We then were tasked with merging the data sets and performing analysis on test results, school budget, school spending per student, type of school, school size, etc.  The challenge portion of the module tasked us with setting a small portion of the dataset with a "NaN" value due to suspicion of academic dishonesty.  After removing the Thomas High School 9th grade test results, we then recalculated and replaced values within the DataFrame, before recalculating and sorting the views by size, type, spending, etc.  


## Process
 * Set THS 9th Grade Math and Reading Scores to "NaN"
  ![THS_NANM](https://user-images.githubusercontent.com/88443672/133144349-9b471718-708d-4cb7-b6d5-d8ce2cd0e833.png)
  ![THS_NANR](https://user-images.githubusercontent.com/88443672/133144364-ab3032f1-ca04-43ed-aaa0-ce8461672138.png)
  ![THS_NANtable](https://user-images.githubusercontent.com/88443672/133144434-04f60177-58d8-4435-89b7-1159b4244150.png)
 * Calculate THS Student Population for 10-12th Grades
  ![THS10_12](https://user-images.githubusercontent.com/88443672/133144668-9f92d7b9-b55a-41cb-bcc4-39f2705c171c.png)
 * Sum of 10-12 Graders w/ Passing Math Score
  ![THS_PM](https://user-images.githubusercontent.com/88443672/133144895-51c530b9-87ab-40c0-9f7a-515beb203e83.png)
 * Sum of 10-12 Graders w/ Passing Reading Score
  ![THS_PR](https://user-images.githubusercontent.com/88443672/133144911-27b9017e-6d3f-4bd2-9f2c-57286c6d390d.png)
 * Sum of 10-12 Graders w/ Passing Math & Reading Score
  ![THS_PMR](https://user-images.githubusercontent.com/88443672/133144934-4334e188-0fc2-4e5c-a020-09194808c67a.png)
 * Calculate % Passing for THS 10-12 Graders
  ![THS_PCT_Calcs](https://user-images.githubusercontent.com/88443672/133145029-c0ba6afd-b32b-4a17-a60f-40e67769a868.png)

## Results: 
 
  - How is the district summary affected?
    ![dis_sum_b](https://user-images.githubusercontent.com/88443672/133142896-c99d1144-19f7-4b0a-9bfa-0e95efe5e790.png)
    ![dis_sum_a](https://user-images.githubusercontent.com/88443672/133142917-d99820f6-f363-4076-b71f-b7a3706e7560.png)

  - How is the school summary affected?
    The affects of removing the 9th grades scores from Thomas High School only impact Thomas High School in the overall school summary. 

  - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
    * Scores by school spending
    * Scores by school size
    * Scores by school type
    
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


## A high-level snapshot of the district's key metrics, presented in a table format

## An overview of the key metrics for each school, presented in a table format

## Tables presenting each of the following metrics:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - The average math score received by students in each grade level at each school
  - The average reading score received by students in each grade level at each school
  - School performance based on the budget per student
  - School performance based on the school size 
  - School performance based on the type of school

  - Total number of students
  - Total number of schools
  - Total budget
  - Average math score
  - Average reading score
  - Percentage of students who passed math
  - Percentage of students who passed reading
  - Overall passing percentage
