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

 * After removing the THS 9th grade results, averages in our DataFrame were skewed lower, as less scores were divided by the same base student body.  We then replaced the corresponding values in our DataFrame with the recalculated values for THS.
  ![ReplaceScores](https://user-images.githubusercontent.com/88443672/133145630-8fac08ee-b090-437b-b9dc-a2017ad4164b.png)
 
## Results: 
 
  - How is the district summary affected?
    After removing the THS 9th grade results
      * The average math score was reduced from 79% to 78.9%
      * The average reading scoare remained the same
      * The % passing math was reduced from 75% tyo 74.8%
      * The % passing reading was reduced from 86% to 85.7%
      * The % passing both math and reading was reduced from 65% to 64.9%
     
    ### BEFORE
    ![dis_sum_b](https://user-images.githubusercontent.com/88443672/133142896-c99d1144-19f7-4b0a-9bfa-0e95efe5e790.png)
    ### AFTER
    ![dis_sum_a](https://user-images.githubusercontent.com/88443672/133142917-d99820f6-f363-4076-b71f-b7a3706e7560.png)

  - How is the school summary affected?
    The affects of removing the 9th grades scores from Thomas High School only impact Thomas High School in the overall school summary. 
    
    ### BEFORE
    ![school_sum_b](https://user-images.githubusercontent.com/88443672/133146246-e5d023ae-7728-4ea4-becd-57e8f6b707bc.png)
    ### AFTER
    ![school_sum_a](https://user-images.githubusercontent.com/88443672/133146304-d718d841-a813-4bf3-a17a-c4aed9f21922.png)

  - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    Removing the 9th grade scores from THS had little impact on their overall averages.
      - The average math score remained the same (83.4%)
      - The average reading score improved by 0.1% (83.9%)
      - The % of students passing math declined by 0.1% (93.2%)
      - The % of students passing reading declined by 0.3% (97%)
      - The % of students passing both math and reading declined by 0.3% (90.6%)
    
  - How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade - There is no impact to grades, other than THS 9th grade being "NaN"
    ![bygradeM](https://user-images.githubusercontent.com/88443672/133147618-1047ca5e-bbe3-495d-886b-f3a36030ddf1.png)
    ![bygradeR](https://user-images.githubusercontent.com/88443672/133147648-72a979ed-a389-4c88-b24c-fd26116005bd.png)

    * Scores by school spending
    * Scores by school size
    * Scores by school type
    
## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.





