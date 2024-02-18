# City_School_District_Analysis

Analyzing the district wide standardized test results data for each student by aggregate it to showcase obvious trends in school performance, which will help make strategic decisions regarding future school budgets and priorities.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#Prerequisites)
- [Coding Instruction](#Coding-Instruction)
- [Report](#Report)
- [References](#references)
  
## Getting Started

Using Pandas and Jupyter Notebook, create a report that includes a written description of at least two observable trends based on the data.


## Prerequisites

Requirements for the software and other tools to build, test and push 

- [Pandas](https://pypi.org/project/pandas/)
- [Jupyter Notebook](https://jupyter.org/)

## Coding Instruction

#### District Summary
- Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:

  1.Total number of unique schools
      
  2.Total students
      
  3.Total budget
      
  4.Average math score
      
  5.Average reading score
      
  6.% passing math (the percentage of students who passed math)
      
  7.% passing reading (the percentage of students who passed reading)
      
  8.% overall passing (the percentage of students who passed math AND reading)

#### School Summary
- Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
Include the following:
  
  1.School name
    
  2.School type
    
  3.Total students
    
  4.Total school budget
    
  5.Per student budget
    
  6.Average math score
    
  7.Average reading score
    
  8.% passing math (the percentage of students who passed math)
    
  9.% passing reading (the percentage of students who passed reading)
    
  10.% overall passing (the percentage of students who passed math AND reading)

#### Highest-Performing Schools (by % Overall Passing)
- Sort the schools by % Overall Passing in descending order and display the top 5 rows.
- Save the results in a DataFrame called "top_schools".
#### Lowest-Performing Schools (by % Overall Passing)
- Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
- Save the results in a DataFrame called "bottom_schools".
#### Math Scores by Grade
- Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
#### Reading Scores by Grade
- Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

#### Scores by School Spending
- Create a table that breaks down school performance based on average spending ranges (per student).
- Include the following metrics in the table:
  
  1.Average math score
  
  2.Average reading score
  
  3.% passing math (the percentage of students who passed math)
  
  4.% passing reading (the percentage of students who passed reading)
  
  5.% overall passing (the percentage of students who passed math AND reading)

#### Scores by School Size
- Use the following code to bin the per_school_summary.
  - size_bins = [0, 1000, 2000, 5000] labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]
- Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
- Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).
  
#### Scores by School Type
- Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
- This new DataFrame should show school performance based on the "School Type".


## Report

1.	The data we have included:
  -	A total number of (15) schools with (7 District and 8 Charter Types). 
  
  -	A total budget for all schools is ($24,649,428):
  
      -	The school with the highest budget is (Bailey High School) with a budget of ($3,124,928).
      -	The school with the lowest budget is (Holden High School) with a budget of ($248,087).
      
      -	The school with the highest budget per student is (Huang High School) with a budget of ($655).
      -	The school with the lowest budget per student is (Wilson High School) with a budget of ($578).
    
  -	A total number of (39,170) students all together:
      -	The school with the highest number of students is (Bailey High School) with (4976) students which falls under the district type.
      -	The school with the lowest number of students is (Holden High School) with (427) students which falls under the charter type.

2.	Using the data given from the math and reading scores we were able to come up with a math average and reading average for all the students together:
 
  -	The math average is (78.9) with (74.9%) students passing math all together.
  -	The reading average is (81.8) with (85.8%) students passing reading all together.
  -	 Only (65.1%) pass reading and math. 

3.	The data included, and during our analysis we were able to conclude the following:
  -	The highest performing schools (the top 5) with highest precent of students who passed math and reading came from the same type which is (Charter). 
  -	The lowest performing schools (the lowest 5) with lowest  precent of students who passed math and reading came from the same type which is (District).  
  -	To analyze the above results, we looked at the total number of students that falls under each school type, this showed that there were more students in District schools than Charter schools, and this could have led to less attention paid to students who needed extra help and less one on one time for students who are struggling.  
  -	Students on average did better in reading than in math and that goes for all students from any school, this means that all students struggled with math more than reading but what made a difference in their marks is how much extra help they could ask for and that is based on how big the classroom is.

## References
Data generated by- [Mockaroo, LLC.](https://mockaroo.com/)(2022). Realistic Data Generator. Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

