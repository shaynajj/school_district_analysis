# PyCitySchools with Pandas

## Overview of Project

### Purpose
To analyze High School students' standardized reading and math scores and to use the information to determine the high school budget for the county as well as see what factors influence higher testing scores.
Further analysis was required after cheating was discovered amongst 9th graders at Thomas High School. So the same analysis was repeated after removing their scores.
     
     

## Results
Note: all images are displayed with the initial results first, followed by the results after Thomas High School 9th graders were removed.
- How is the district summary affected?
--The district average math score and overall passing percentage decreased slightly.
(./Resources/District_Summary_1.png)
(./Resources/District_Summary_2.png)
- How is the school summary affected?
--The passing math, reading, and overall percentages for Thomas High School students decreased significantly: from 93.3%, 97.3%, 90.9% to 66.9%, 69.7, 65.1% respectively.
(./Resources/School_Summary_1.png)
(./Resources/School_Summary_1.png)
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
--Initially, Thomas High School was ranked #2 out of the 15 schools in Overall Passing Percentage. After the results were revised due to the 9th grade scores being tainted, Thomas High School was no longer in the top 5.
(./Resources/Top_5_1.png)
(./Resources/Top_5_2.png)
- How does replacing the ninth-grade scores affect the following:
a) Math and reading scores by grade
---There is no affect by grade because all math and reading scores for Thomas High School 9th graders are replaced with "nan"
(./Resources/Average_Math_1.png)
(./Resources/Average_Math_2.png)
b) Scores by school spending
---The math, reading, and overall passing percentages decreased for the Spending Range $630-644: from 73%, 84%, and 63% to 67%, 77%, and 56% respectively.
(./Resources/Scores_By_Spending_1.png)
(./Resources/Scores_By_Spending_2.png)
c) Scores by school size
---The math, reading, and overall passing percentages decreased for Medium sized schools: from 94%, 97%, and 91% to 88%, 91%, and 85% respectively.
(./Resources/Scores_By_Size_1.png)
(./Resources/Scores_By_Size_2.png)
d) Scores by school type 
---The math, reading, and overall passing percentages decreased for Charter schools: from 94%, 97%, and 90% to 90%, 93%, and 87% respectively.
(./Resources/Scores_By_Type_1.png)
(./Resources/Scores_By_Type_2.png)
## Summary
The 4 major changes in the updated school district analysis was the decrease in passing percentages by spending, size, and type
