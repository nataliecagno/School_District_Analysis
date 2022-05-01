# School_District_Analysis

## Project Overview
Analysis focused on performance of math and reading schools of school district in preparation of board meeting. Overall percentages were analyzed across school name, school types, school sizes and average budget spending per student. Upon further investigation the board noted that the results for Thomas High School's 9th grade class have been fabricated. As a result, we adjusted analysis to remove those students’ scores and analyzed the data again. Key results are below.
## Resources
### Software
Python 3.7, Anaconda, Jupyter Notebook

## Results
### How is the District Summary affected?
Our original analysis included all students from our data file. Due to potential fraudulent scores of the ninth graders of Thomas High School, we omitted their results and reran our analysis. The data frame below is a summary of the district before and after replacing the students’ scores with NaN.
Original Analysis: (picture)
Adjusted Analysis: (picture
The average scores of math and reading dropped by .06% and .02% respectively which caused the overall passing percentages of math and reading by .22% for math and .15% for reading. Therefore, we can see the passing percentage dropped from to 65.17% to 64.86% overall for the district.
While the changes are miniscule, it is important to note that the 9th graders of Thomas High School only make up about 1.2% of the overall district data, so removing their data overall does not cause too much disruption to our analysis.

### How is the School Summary affected?
Original Analysis:
Adjusted Analysis:

### Score replacement effects
#### Thomas High School Performance
The top 5 schools with the highest overall passing percentage are all Charter schools, whereas all the bottom 5 performing schools are District schools. Adjusting our analysis did not affect Thomas High Schools ranking at #2.
Top school original pic
Top school new pic
The bottom 5 rankings were not affected as Thomas High School was ranked #2 in both analyses.
Bottom 5 pic
Bottom 5 new pic

#### Math and reading score by Grade
Original math score pic
Updated math score pic
Original reading score pic
Updated reading score pic
The only change we can see in these data frames is the data from the 9th grade class at Thomas High School. Their scores have been replaced by NaN in the beginning of our analysis.

#### Scores by School Spending
One key result I noticed was that the average scores and passing percentages do not increase as the spending per student increases. There was a slight change in scores by spending groups in the $630-$644 range as this is the group Thomas High School falls in. However, the change is miniscule, where each metric was changed by less than .1 percentage.
Original spending pic
New spending pic

#### Scores by School Type
The Charter schools in this district generally performed better than the district schools in this analysis. Given that Thomas High School was a charter school, we only see a minimal effect in our data as the district school data was unaffected. 

Original school type pic
New school type pic

#### Scores by School Size
Original size pic
New size pic
Since Thomas High School has 1,635 students, the only slight change we saw was in the Medium sized range (1000-2000 students). Each metric changed by less than 1 percentage point.

## challenge summary
To conclude, after replacing the math and reading scores of 9th graders from Thomas High School with NaN, we saw significant changes to our district summary. Once we recalculated the scores of only the 10th-12th graders at THS, we realized our analysis was not as off as we originally feared.
•	Changes made to math and reading scores decreased the districts overall passing percentage by .31%.
•	The overall passing percentage of the spending range $630-$644 decreased by .01%
•	Although the overall passing percentage for Thomas High School was affected, the school rankings remain unchanged.
•	Changes to charter school type for all scores by a fraction of a percentage point did not affect the overall performance of Charter schools vs District Schools.

