       
Overview

This project analyzes the performance metrics of schools within a school district to understand the overall educational outcomes and draw comparisons between different types of schools. The analysis utilizes data from two main datasets: one containing school information and another containing student performance details. The key metrics analyzed include budget, student count, average test scores, and pass rates for math and reading.

Data Sources

schools_complete.csv - Contains information about each school, including school name, type, size, and budget.
students_complete.csv - Contains information about each student, including student name, gender, grade, school name, reading score, and math score.
Analysis Goals
Calculate district-wide metrics such as total number of schools, total students, total budget, average math score, average reading score, and passing rates for math, reading, and overall.
Generate a summary for each school with detailed metrics.
Identify the highest and lowest-performing schools based on overall passing rates.
Examine the impact of spending per student on academic performance.
Analyze the effect of school size on academic outcomes.
Compare the performance between charter schools and district schools.
Draw conclusions and identify observable trends from the data.


Key Metrics

District Summary
Total Schools
Total Students
Total Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
% Overall Passing
School Summary
For each school:

School Name

School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
% Overall Passing
Additional Analyses

Top Performing Schools:

List of the top 5 schools by overall passing percentage.
Bottom Performing Schools: List of the bottom 5 schools by overall passing percentage.
Math Scores by Grade: Average math scores for each grade level (9th, 10th, 11th, 12th) at each school.
Reading Scores by Grade: Average reading scores for each grade level (9th, 10th, 11th, 12th) at each school.
Scores by School Spending: Breakdown of school performance based on average spending ranges per student.
Scores by School Size: Breakdown of school performance based on school size (small, medium, large).
Scores by School Type: Comparison of performance between charter schools and district schools.
Usage
Data Loading and Merging:

Load the datasets using pandas.
Merge the datasets on the school name to create a comprehensive dataset.
District Metrics Calculation:

Calculate the total number of unique schools and students.
Sum the total budget.
Calculate the average math and reading scores.
Calculate the percentage of students passing math, reading, and overall.
School Summary Calculation:

Group the merged dataset by school and type.
Calculate the total students, total budget, per student budget, average scores, and passing percentages for each school.
Performance Analysis:

Identify the top and bottom-performing schools.
Calculate average scores by grade for each school.
Analyze scores based on spending ranges, school size, and school type.
Observations and Trends:

Draw conclusions and identify trends based on the analysis results.
Running the Analysis
To run the analysis, execute the provided Jupyter Notebook or Python script. The script will print out the calculated metrics and summaries, and provide insights into the performance of schools within the district.

Observable Trends
Charter Schools Outperform District Schools:

Charter schools generally have higher average math and reading scores and higher overall passing rates compared to district schools.
Spending and Performance:

Higher spending per student does not necessarily result in better academic performance. Effective resource allocation and other qualitative factors play a significant role in student success.
