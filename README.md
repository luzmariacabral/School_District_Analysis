# School_District_Analysis

## Overview
Maria has asked for out assistance in the analysis of testing in a school district using Anaconda systems. The district is composed of 15 high schools both charter and public. Data was given to us in csv form to clean up and make it presentable for Maria to be able to present to stakeholders. To begin with Maria is looking for these deliverables:

- Top 5 performing schools
- Bottom 5 performing schools
- Average math score received by student in each grade level, per school
- Average reading score received by student in easg grade level, per school
- School Performance based on budget
- School Performance based on school size
- School Performance based on school type

All this information can be found in the PyCitySchools.ipynb file. Once we were finished with our report it was discovered the the 9th grade class at Thomas High School (THS) had cheated and all their scores were diqualified. We had to re-evaluate all our findings and reports to adjust for this change. Initially removing all the math and reading scores from the data for the 9th grade class in THS, replacing those with NaN. Then re-calculating the rest of the school's totals and percentages and pluging this information in the completed report. This analysis will review our actions with the report and the difference removing the Thomas High School 9th grade class made.

## Results
After cleaning up the raw data it was determined that there were 39,170 student in the 15 high schools in the region. The selection of schools looks pretty even in type, school size, and funding per student. Students that went to Charter schools received higher scores that students in public schools. Smaller class sizes or schools with less students also had the best outcomes in the testing. 

#### Results of District v. Charter
![image](Resources/districtvcharter_original.png)
