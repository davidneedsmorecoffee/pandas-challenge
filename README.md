# Analysis of student testing results using Pandas

Pandas script was written to analyze two sample sets of data (schoos_complete.csv, students_complete.csv). The data set contains students math and reading scores, as well as various information on the schools they attend, e.g., school size, school budget, total number of students, etc.

Pandas was used to examine and aggregate the data. 
Different trends in school and student performance were identified as the result of this analysis. 

From the data, the following summaries were generated. See the `PyCitySchools_DL_clean.ipynb` file in the Code folder for complete output and interpretation.

### District Summary

* High level snapshot (in tablular form) of the district's key metrics, such as

  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### School Summary

* Overview table that summarized key metrics about each school, such as

  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Top and Bottom 5 Performing Schools (By Passing Rate)

* Identified the top 5 and bottom 5 performing schools based on Overall Passing Rate and created a summary based on

  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)


### Math Scores by Grade

* Created a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

* Created a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending, School Size, and School Type

* Created tables that breaks down school performances based on

  * average Spending Ranges (Per Student). 
  * school size (Small, Medium, Large)
  * school type (Charter vs. District)
  
* Summarized the results based on the following:

  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)
