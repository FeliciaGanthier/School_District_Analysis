# School_District_Analysis

##**Overview of Project**

Maria, chief data scientist for a school district, is responsible for analyzing data from a variety of sources and in a variety of formats. She prepares the standardized test data for analysis, reporting and presentation to provide insights about performance trends and patterns. These insights inform discussions and strategic decisions at the school and district level. 

Using Jupyter Notebook and the Pandas Library, I am reading raw data from CSV files, inspecting and cleaning data, merging datasets, performing mathematical calculations and visualizing the data to tell a story.

*Purpose of Analysis*

I am helping Maria analyze data on student funding and student’s standardized test scores. To complete this project, I have access to every student’s math and reading test scores as well as information about the schools they attend. My task is to aggregate the data and showcase trends in school performance. The analysis will help the school board and superintendent in the making decisions regarding school budgets and priorities.  In compliance of the Family Education Rights and Privacy Act (FERPA), the data must be treated with the utmost confidentiality to protect the students being reported on. 

A Git Hub repository was created for the school analysis so Maria and the team can review the most recent work. 

###**Results**

After my initial report, Maria asked for a deeper analysis using each school’s metadata to get the average math and reading scores for each grade. To help the school board make decisions about the budget for the upcoming school year, Maria asked me to organize the data in spending ranges for the schools to show how school spending per student affects the average scores and passing percentage. 

*Items to Consider*

•	For schools in the district, 70 is the passing score for the math and reading tests. 

•	Highest performing schools based on the overall percentage of passing students will help the district determine how much money should be allocated to and spent on each school 

•	Lowest performing schools based on the overall percentage of students who passed will help the district determine if more money needs to be allocated to these schools or if other solutions are needed, based on what the data shows. 

!Overall Summary Original Photo(https://github.com/FeliciaGanthier/School_District_Analysis/blob/master/Resources/Overall_Summary_Original.png)

The school board is concerned about academic dishonesty at Thomas High School and to uphold state-testing standards, I replaced the math and reading scores for Thomas High School nineth graders (the grade in question)with NaNs while keeping the rest of the data intact. Then I updated the district summary with the adjusted data to recalculate the passing math and reading percentages and overall passing percentage with the recalculated student count.

!NaN Scores photo(https://github.com/FeliciaGanthier/School_District_Analysis/blob/master/Resources/NaN%20Scores.png)

!Delieverable 1 photo(https://github.com/FeliciaGanthier/School_District_Analysis/blob/master/Resources/Deliverable%201.png)

Unfortunately, due to an error in either the Challenge Starter Set and/or Challenge Instructions, there was no change in the summaries and the affect on the Thomas High School’s performance relative to the other schools, scores by school spending, scores by school size and scores by school size cannot be determined. There would be an impact on the math and reading scores by grade because the Thomas High School student count was reduced by 461 students. 

It is possible to perform the analysis in Excel with the CSV files but Pandas is one of the most widely preferred tools for data analysis and carries tremendous power in handling large data sets, which can slow down Excel. 

####**Summary**

Given the challenges outlined in the Results section, the following can be inferred:

Since the nineth graders are still part of the overall Thomas High School population

•	School Types and Spending Based on School Type can remain unchanged

•	School Size and Spending Based on School Size can remain unchanged

However, these items would be impacted:

•	Budget Allocation based on math and reading scores

•	Budget Allocation based on overall passing percentage

The school board may decide to increase funding to provide Thomas High School with more resources not as a reward for academic dishonesty but in recognition of need since the act could be interpreted as a “cry for help”.  The data cannot account for motivation so the school board would need to have conversations with Thomas High School leaders to determine the best course of action. 
