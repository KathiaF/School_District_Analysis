# School_District_Analysis
# Project Overview
The purpose of this analysis is to help Maria analyze data on student funding and students standardized test scores in order to present it to the school board. After sending the results of the first analysis (Module 4), the school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Maria has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and write up a report to describe how these changes affected the overall analysis.

# Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.9.0, Anaconda Navigator 2.1.1, Jupyter Notebook 6.4.6


# Results
- How is the district summary affected?
  - Module 4: School District Summary
    
    <img src="/Resources/m4_img1.png" width="50%" height="50%">
    
  - Challenge 4: School District Summary
  
    <img src="/Resources/c4_img1.png" width="50%" height="50%">
  
  - After replacing the 9th graders' scores with NaN the average math score and the overall passing percent dropped 0.1, the percentage passing math dropped 0.2 and the percentage passing reading dropped 0.3.

- How is the school summary affected?
 - Module 4: School Summary
 
    <img src="/Resources/m4_img2.png" width="50%" height="50%">
    
 - Challenge 4: School Summary
    
    <img src="/Resources/c4_img2.png" width="50%" height="50%">
 
 - It can be seen that after replacing the 9th graders' scores with NaN, there were significant differences in the results, and it is observed that the percentage passing math dropped from 93.27% to 64.91%, the percentage passing reading dropped from 97.31% to 69.66% and the overall passing dropped from 90.95% to 65.08%


## Metrics
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  - Module 4: Top Five Performing Schools
  - Thomas High School (THS) was among the top 5 schools based on performance of all grades.
  <img src="/Resources/m4_img3.png" width="50%" height="50%">
  
  - Challenge 4: Top Five Performing Schools
  - In the previous point (School Summary), it was noted that by removing excess 9th graders and continuing to count 9th graders in the student count, THS reduced the overall passing rate from 90.95% to 65.08%. However, when the student count was adjusted to exclude 9th graders THS was still among the top 5 performing schools.
  <img src="/Resources/c4_img3.png" width="50%" height="50%">

  - Module 4: Bottom Five Performing Schools
  <img src="/Resources/m4_img4.png" width="50%" height="50%">
  
  - Challenge 4: Bottom Five Performing Schools
  <img src="/Resources/c4_img4.png" width="50%" height="50%">

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - As seen in the figures below, only the math and reading scores for 9th graders in THS were replaced with NaN. 
    - Module 4: Average Math Scores by Grade & School
    <img src="/Resources/m4_img5.png" width="25%" height="25%">
    
    - Challenge 4: Average Math Scores by Grade & School
    <img src="/Resources/c4_img5.png" width="25%" height="25%">
    
    - Module 4: Average Reading Scores by Grade & School
    <img src="/Resources/m4_img6.png" width="25%" height="25%">
    
    - Challenge 4: Average Reading Scores by Grade & School
    <img src="/Resources/c4_img6.png" width="25%" height="25%">

- Scores by school spending
  - Module 4: School Spending Summary
  <img src="/Resources/m4_img7.png" width="50%" height="50%">
  
  - Challenge 4: School Spending Summary
  <img src="/Resources/c4_img7.png" width="50%" height="50%">

  - THS is in the $630-$644 range spending bin, it can be seen that removing 9th graders from the analysis is not significant and is not even visible when scores are formatted to the nearest tenths.
  
- Scores by school size
  - Module 4: School Size Summary
  <img src="/Resources/m4_img8.png" width="50%" height="50%">
  
  - Challenge 4: School Size Summary
  <img src="/Resources/c4_img8ok.png" width="50%" height="50%">
  
  - THS is medium sized school. it can be seen that removing 9th graders from the analysis become insignificant and is not even visible when scores are formatted to the nearest integer.

- Scores by school type
  - Module 4: School Type Summary
  <img src="/Resources/m4_img9.png" width="50%" height="50%">
  
  - Challenge 4: School Type Summary
  <img src="/Resources/c4_img9.png" width="50%" height="50%">
  
  - THS is a Charter school. it can be seen that removing 9th graders from the analysis become insignificant and is not even visible when scores are formatted to the nearest integer.

# Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. The overall passing at THS dropped from 90.95% to 65.08%
2. Thomas High School lost its ranking as a top five school within this District...
3. ... but after removing 9th grade scores and the student count from the calculation, Thomas High School is still in the top five performing school.
5. The results in scores by school spending, school size and school type do not change significantly when the scores of the 9th graders of the THS are removed and are insignificant due to rounding.
