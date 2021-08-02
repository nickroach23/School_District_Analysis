# School_District_Analysis
### Project Overview

With thorough research for analyzing the school districts research for the overall grades for reading and math. There was an unfortunate academic dishonesty that was reported by  Thomas High School. The ninth grade scores were tampered with. Which leads us to do another analysis that must adjust the ninth grades reading and math scores by replacing them with a "NaN" which means "Not a Number". The meaning of this analysis is to re-analyze and gather the data for the entire School District. 
### Resources
Data Source : schools_complete.csv , students_complete.csv
Tools : Python 3.7.6, Pandas, Jupyter Notebook

### Analysis Results
### District Summary
![Screenshot (15)](https://user-images.githubusercontent.com/64110317/127796375-e37474ae-5f41-49e5-b4ec-2fe42ba5f6b1.png)

### School Summary 
### Top 5
![Screenshot (18)](https://user-images.githubusercontent.com/64110317/127797973-9e07ae1c-5ddf-47af-9c8a-f852171de139.png)

### Bottom 5 

![Screenshot (21)](https://user-images.githubusercontent.com/64110317/127798122-c02e11d7-c1ec-4044-bfe4-da81ff5632ed.png)

1. After creating the district summary and the school summary the images shows the following:
  * The top 5 performing schools in the district were all "Charter" whereas the bottom performing schools were "District". One reason for this is because the lower body size Charter schools have compared to the District schools.
  * The performance shows that the Charter type schools overall have a higher passing percentage than the district schools.
  * The data shows the the smaller and medium size schools have a larger passing percentage than larger size schools.
  * The performance shows based on spending per student that the overall passing percentage is highest for the schools having spending per student < $584. The schools whose spending per student is $645-675 have the lowest overall percentage
  * ![Screenshot (25)](https://user-images.githubusercontent.com/64110317/127799693-64104bd5-9ef4-4fa6-a170-44293f9bde99.png)
  
  * ## Average Math and Reading Scores
    By effectively removing the ninth grader's score, it should be noted that the average math exam score for the district dropped ny one-tenth of a percentage point. The average score of reading wasn't altered.
  
  * ## Percentage of students passing according to math scores
    Following with the data adjustment, it can be noted that the percentage of students passing the math exam was lowered by two-tenths of a percentage point following the new adjustment.
  * ## Percentage of students passing according to reading scores.
    Following with the data adjustment, it can be noted that the percentage of students in the district who passed the reading exam was dropped ny three-tenths of a percentage point.
   * ## Overall percentage of students who both passed math and reading.
    With the data adjustment of replacing the ninth graders from Thomas High School with "NaN" the overall percentage of the students who passed of the courses in the district had dropped by one-tenth of a percentage.

### Summary
After reviewing the analysis of the school district and replacing Thomas High School ninth graders scores with a "NaN" for both math and reading had four notable changes in the district data:
1. The average math exam scores for the district had dropped one-tenth of a percentage
2. The percentage of students that did pass the math exam was decreased by a two-tents percentage
3. The percentage of students that did pass the reading exam was decreased by three-tenths percentage
4. For the students who passed both math and reading their percentage was decreased by one-tenths percentage.

