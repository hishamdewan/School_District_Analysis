# Overview of the school district analysis

The purpose of this analysis is to assist the school board to determine whether there is evidence of academic dishonesty in the students_complete.csv file. Specifically, the task is to determine whether reading and math grades for ninth graders at Thomas High School have been altered. 

I analyze the students_complete.csv data to look for evidence of academic dishonesty. We test this by replacing math and reading scores of ninth graders at Thomas High School with "NaNs" while keeping the rest of the data intact. After this replacement, we have to determine how key metrics snapshot of the district changed and draw conclusion on whether academic dishonesty took place with ninth graders at Thomas High School. 

# Results

The following section looks at the impact of removing math and reading scores for ninth graders at Thomas High School. 

## How is the district summary affected?

The district summary changed only marginally after removing math and reading scores of ninth graders at Thomas High School as can bee seen in the following two charts. Noteworthy changes are:

- Average math score dropped from 79.0 to 78.9 after the removal.
- Passing rate for math dropped from 75% to 74.8%.
- Passing rate for reading dropped from 85.8% to 85.7%.
- Overall passing rate for reading and math combined dropped from 65.2% to 64.9%.

![District summary after removal](/Resources/District_summary.png) 

District summary before removing math and reading scores of ninth graders at Thomas High School:

![District summary original](/Resources/District_summary_old.png) 

## How is the school summary affected?

The school summary did not change in a statistically significant manner after removing math and reading scores of ninth graders at Thomas High School as can bee seen in the following two charts. Math and reading scores changed for Thomas High School only as the new table looks at 10th to 12th grade students and excludes 9th grade. 

![School summary after removal](/Resources/school_summary.png) 


School summary before removing math and reading scores of ninth graders at Thomas High School:

![School summary old](/Resources/school_summary_old.png) 

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Removing math and reading scores of ninth graders at Thomas High School did not significantly alter Thomas High School's performance relative to other schools. Both before and after the removal of 9th grader scores, Thomas High School would have been ranked #2 in terms of overall passing rate. Top school ranking after removal: 

![Top Schools after removal](/Resources/Top_schools.png)

Top schools original list:
![Top Schools](/Resources/Top_schools_old.png)

## How does replacing the ninth-grade scores affect the following?

Replacing the ninth-grade scores did not alter scores for 10th to 12th graders Thomas High School. Ninth grader scores were replaced by "nan". The following tables show math and reading scores by grade for each school:

Table of math scores by grade after removing ninth-grade scores:

![math by grade](/Resources/math_by_grade.png) ![reading by grade](/Resources/reading_by_grade.png)

Original table of math scores by grade: 

![math by grade](/Resources/math_scores_by_grade_old.png) ![reading by grade](/Resources/reading_scores_by_grade_old.png)

The average scores by school spending were not impacted by removing math and reading scores of ninth graders at Thomas High School. 

![scores by spend](/Resources/scores_by_spend.png)

The average scores by school size were not impacted by removing math and reading scores of ninth graders at Thomas High School.

![scores by size](/Resources/scores_by_size.png)

The average scores by school type were not impacted by removing math and reading scores of ninth graders at Thomas High School.

![scores by type](/Resources/scores_by_type.png)


# Summary School District Analysis and Conclusion

The following are the four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaN:

- Average math score dropped from 79.0 to 78.9 after the removal.
- Passing rate for math dropped from 75% to 74.8%.
- Passing rate for reading dropped from 85.8% to 85.7%.
- Overall passing rate for reading and math combined dropped from 65.2% to 64.9%.

In addition, there is insufficient evidence to support in the  students_complete.csv file to show evidence of academic dishonesty with ninth grade students at Thomas High School. 