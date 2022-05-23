# School_District_Analysis
## Overview
The chief data scientist of a local, large school district has asked us to complete a complete and total analysis of their schools. The purpose is to analyze standardized math and reading test scores from each student and how it will correlate to the allocation of the school budget. 

Upon receiving the data for the analysis, it was brought to our attention that there is a high probability of fraud at Thomas High School. The school district would like our help in determining if this is true.

### Resources
Data Sources:     clean_students_complete.csv     missing_grade.csv     schools_complete.csv     students_complete.csv

Software:     Python 3.9     Jupyter Notebooks 6.1.4     Anaconda 3.8.5

Code Techniques Utilized: Pandas Numpy

## Results
### Original data received from school district
The original set of data shows that the Thomas High School overall passing grade is 65%.
<img width="999" alt="Screen Shot 2022-05-22 at 9 33 12 PM" src="https://user-images.githubusercontent.com/103767830/169733006-2fdedcd4-312b-4665-961a-1748f010ac91.png">

### Altered DataFrame 
We removed 461 students from the Thomas High School list. This brought THS from an overall passing grade of 65% to 90%.
<img width="999" alt="Screen Shot 2022-05-22 at 9 47 01 PM" src="https://user-images.githubusercontent.com/103767830/169734089-0973dd99-0264-4e6a-811f-1a6e0d4d2688.png">

### Top ranking school
After correcting the data, Thomas High School is now a top performing school in the district.
<img width="993" alt="Screen Shot 2022-05-22 at 9 51 48 PM" src="https://user-images.githubusercontent.com/103767830/169734830-155fc495-fa14-4c66-b6b6-4212692c0ea7.png">

### Spending ranges per student
Along with fixing the Thomas High School issue, we were tasked with analyzing the amount of money spent per student and if there were any correlations to their test scores.
<img width="823" alt="Screen Shot 2022-05-22 at 9 59 19 PM" src="https://user-images.githubusercontent.com/103767830/169735236-0680803f-0eeb-43e9-bf27-b53aaa6db3a7.png">
According to our analysis, the less money schools spent per student, the higher the test scores were.

### School performance by size
We also analyzed how large a school was and if it had any effect on student's test scores.
<img width="762" alt="Screen Shot 2022-05-22 at 10 07 26 PM" src="https://user-images.githubusercontent.com/103767830/169735785-5ef83437-86ed-43ab-a3d8-b99d60fa389b.png">
 Our analysis shows that smaller schools (small and medium sized) performed better than the large school category.

### School performance by type
Our final conclusion was based off whether district schools or charter schools performed better.

