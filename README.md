# School_District_Analysis

## Overview of the school district analysis:  
In this project we are analyzing data on student funding and students' standardized test scores. Our task is to aggregate the data and showcase trends in school performance.This analysis assists the school board and superintendent in making decisions regarding the school budgets and priorities.
The school board has notified us that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. So we need to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Then we have to make comparison to see how these changes affected the overall analysis.

## Results:  
* At the pictures below we can see that eliminating of the math and reading scores for Thomas High School didn't effect much on the district summary.  
Before eliminating scores  
![pic](https://github.com/ElenaMasarsky/School_District_Analysis/blob/main/Resources/district_summary.png)  
After eliminating scores  
![pic](https://github.com/ElenaMasarsky/School_District_Analysis/blob/main/Resources/district_summary_without_THS_9th_scores.png)  

* School summary wasn't affected but Thomas High School metadata. As we can see at pictures attached, average math and reading scores were not changed much for Thomas High School, but percentages have changed a lot.  
Before eliminating scores  
![pic](https://github.com/ElenaMasarsky/School_District_Analysis/blob/main/Resources/per_school_summary.png)  
After eliminating scores  
![pic](https://github.com/ElenaMasarsky/School_District_Analysis/blob/main/Resources/per_school_summary_without_THS_9th_scores.png)  


* As we can see in math and reading scores data frames only indicators for Thomas High School 9th classes changed for NAN. Everything else remained unchanged.  
Before eliminating scores  
![pic](https://github.com/ElenaMasarsky/School_District_Analysis/blob/main/Resources/math_scores_by_grade.png)  
After eliminating scores  
![pic](https://github.com/ElenaMasarsky/School_District_Analysis/blob/main/Resources/math_scores_by_grade_without_THS_9th_scores.png)  
Before eliminating scores  
![pic](https://github.com/ElenaMasarsky/School_District_Analysis/blob/main/Resources/reading_scores_by_grade.png)  
After eliminating scores  
![pic](https://github.com/ElenaMasarsky/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_without_THS_9th_scores.png)  

* Scores by school spending were affected only to a hundredth of a percent. So we couldn't see any changes at formated spending_summary_df. 

* Scores by school size were affected only to a hundredth of a percent. And we couldn't see any changes at formated size_summary_df.

* Scores by school type were affected only to a hundredth of a percent. We could not see any changes at formated type_summary_df. 

## Summary:  
After all considered above we can assume that the most affected by eliminating of the math and reading scores for ninth grade at Thomas High School were Passing Math Percentage, Passing Reading Percentage, and Overal Passing Percentage at per school summary. Final results of scores by school spending, school size, and school type remained the same.