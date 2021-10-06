# School District Analysis
Analyzing School Data with Python

## Resources
- Python 3.8.5
- Jupyter Notebook 6.3.0
- Data Sources: students_complete.csv, schools_complete.csv (found in Resources folder)

## Summary
The purpose of this analysis is to assist a school board with the evaluation of data that was received from the school's in it'S district. The board believes that the ninth grade reading and math grades in Thomas High School have been altered. The school board wants to maintain the integrity of their testing scores over their district, and would like the altered scores to be removed from the total; as to not skew the overall data. This analysis will demonstrate how the removed scores from Thomas High School affect the overall data. 

## Analysis
These are the district's Numbers before any adjustments:
![](../main/Resources/District_Summary_Unadjusted.png)

These are the District's numbers after the adjusments:
![](../main/Resources/District_Summary_Adjusted.PNG)

During the analysis, it was confirmed that there was a small decline in Overall Passing Percentage from **65.2** to **64.9**
- The Schools total students (39,170) remained unchanged
- Also the Total Budget for the district also was unaffected by the adjsutment. The budget remained at $24,649,428.00

Below you will see the areas that were affected after adjustments were made.
- Average Math Score (Unadjusted):     **79.0** *in comparison to* 

  - Average Math Score (Adjusted): **78.9**
- Average Reading Score (Unadjusted):  **81.9** *in comparison to* 
 
  - Average Reading Score (Adjusted): **81.9**
- Passing Math Percentage (Unadjusted):             **75.0** *in comparison to* 
  - Passing Math Percentage (Adjusted): **74.8**
- Passing Reading Percentage (Unadjusted):         **85.8** *in comparison to* 
  - Passing Reading Percentage (Adjusted): **85.7**
- Overall Passing Percentage (Unadjusted):         **65.2** *in comparison to* 
  - Overall Passing Percentage (Adjusted): **64.9**

Top 5 Schools Unadjusted for Thomas High School

![](../main/Resources/Top5Schools_Unadjusted.png)

Top 5 Schools Adjusted for Thomas High School

![](../main/Resources/Top5Schools_Adjusted.png)

If you look carefully above at both charts you can see that Thomas High School's percentage does change in Both Math and Reading Scores, Both Passing Percentages and Overall percentage but it does not alter it's placement in the the top 5 schools. 


## Conclusion



