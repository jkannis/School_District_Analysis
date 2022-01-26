# School District Analysis

## Overview
The purpose of this project is to provide insights about school performance trends and patterns.
### Criteria and Outcomes
This analysis is based on type of school, school spending, and test results for grades nine through twelve. The data was adjusted after the discovery of grade tampering on the 9th grade standardized tests at Thomas High School. All of the scores for this group were removed from the calculations for this analysis. The results of this analysis will showcase trends in school performance to help with decision-making regarding budgets and school priorities.

## Analysis Results
- Overall removing the 9th grade test scores from Thomas High School did not have a large impact on the analysis results.
    - The District Summary results after removing the test scores in question showed an overall passing percentage of 64.9%, as opposed to 65.2% before the adjustment.
### District Summary Results
![District Summary Before Adjustment](https://github.com/jkannis/School_District_Analysis/blob/main/Resources/District_Summary_Before.png)
![District Summary After Adjustment](https://github.com/jkannis/School_District_Analysis/blob/main/Resources/District_Summary_After.png)
    - The School Summary results only changed by .1% for Thomas High School after adjustments.
### School Summary Results
![School Summary Before Adjustment](https://github.com/jkannis/School_District_Analysis/blob/main/Resources/School_Summary_Before.png)
![School Summary After Adjustment](https://github.com/jkannis/School_District_Analysis/blob/main/Resources/School_Summary_After.png)
    - Removing the 9th grade test scores from Thomas High School did not affect the school ranking order.
    - The only difference on the math and reading scores by grade results was the 'nan' for Thomas High School 9th grade results, which was caused by our removing those results.
    - The Scores by School Spending, Scores by School Size, and Scores by School Type were unchanged after removing the 9th grade results for Thomas High School.

## Summary
Running an analysis on incomplete data is not ideal, but running an analysis on inaccurate data is worse. Therefore, removing the 9th grade test scores that had been tampered with was necessary to provide the most accurate analysis possible for the client. While replacing those test scores with nulls did not have a large impact on Thomas High School's placement in the school rankings, there were some results that were affected by the changes.
    1. The percent passing math at Thomas High School dropped .1%
    2. The percent passing reading at Thomas High School dropped .3%
    3. The combined percent passing math for all schools dropped .2% 
    4. The combined percent passing reading for all schools dropped .1%