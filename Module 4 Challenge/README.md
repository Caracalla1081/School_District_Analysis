# School District Analysis
## Overview of School District Analysis
The purpose of the anaylsis related to schools of this particular district are to assist in budgetary decisions related to schools in the district individual performances, as well as any trends or patterns related to these schools, and the district as a whole.

## Resources
- Data Source: new_full_student_data
- Software: Jupyter Notebook 6.4.12

## Key Analysis Findings:
- District School Budgets:
  - The average school budget across the district is $893,472.75
  - The minimum school budget in the district is $817,615
  - The maximum school budget in the district is $991,918
- District Scores:
  - Avg. reading score is 72
  - Avg. math score is 64
- Charter Avg. Math Scores by Grade:    
  - 9th: 70
  - 10th: 66
  - 11th: 68
  - 12th: 64
 - Public Avg. Math Scores by Grade:
  -  9th: 64
  -  10th: 64
  -  11th: 59
  -  12th: 64
 -  School Student Body Count:
  - Montgomery High School: 2038
  - Green High School: 1961
  - Dixon High School: 1583
  - Wagner High School: 1541
  - Silva High School: 1109
  - Woods High School: 1052
  - Sullivan High School: 971
  - Turner High School: 846
  - Bowers High School: 803
  - Fisher High School: 798
  - Richard High School: 551
  - Campos High School: 541
  - Odonnell High School: 459
  - Campbell High School: 407
  - Chang High School: 171  

## School District Analysis Summary
After performing the cleaning and analysis on the student data provided, it is my belief that much more parsing and drilling into the data needs to be performed to gather any valuable insights into factors that may contribute to test score performances between individual schools and Charter versus Public.

For instance, in comparing "school_type" by "math_score", we can see that charter schools saw a decline in performance from 9th grade to 12th grade by 10 points, whereas public schools did not see any meaningful change over the four years of high school, but it is not clear here why. Without a better breakdown of comparisons between school test score performances by "school_budget" and "student_count" by "school_name" or "school_type" it appears difficult to draw any solid conclusions on why the drop-off in performance in charter schools and stagnation in public schools.

Another datapoint that would prove useful would be to break out school budgets by grade, and group by school and/or type, with the "math_score" and "reading_score" means included. We could potentially then determine if schools are acknowledging or providing more resources based on grade level, and if so, ask why.

The analysis could even be done on "student_count" and "student_budget" by "school_name" and/or "school_type", giving us the ability to breakout avg. spending per student and also what are the schools that have an outsized budget based on their "student_count", and can resources be guided to other schools, primarily in-between public schools.

As it stands the main takeaways from the analysis above are:
- Reading scores in the district are neither being dragged down or lifted by any significant outliers.
- Math scores in the district are neither being dragged down or lifted by an significant outliers.
- Public schools have larger budgets than charter schools in the district, but the results related to math scores appear to be indistinguishable from each other.
- 9th grade performance appears to be dragging overall district performances down for reading scores, but not for math scores where they slightly over perform.
