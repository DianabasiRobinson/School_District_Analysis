# SCHOOL DISTRICT ANALYSIS

## PROJECT OVERVIEW
This project involves a standardized test data for the analysis of the student's tests scores, student's funding, school types and the school sizes to provides insights to the school board on strategic decisions regarding the school budgets and priorities. 
key THS - thomas high school
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.


## RESULTS
###  How is the district summary affected?
The initial district summary is shown below;
![before thomas](https://user-images.githubusercontent.com/109990578/188480215-aaf29d72-648b-4247-bed3-b6c276d1ee44.png)

The district summary after Cleanup is shown below;
![after thomas](https://user-images.githubusercontent.com/109990578/188480453-132b8281-83ad-43f6-a9f2-80d1aa6d987d.png)

Considering the images above, we can see that;
  - The average Math Score decreased by 0.1%
  - The average Reading Score remained constant
  - The percentage Passing Math decreased by 0.2%
  - The percentage Passing Reading decreased by 0.3%
  - The percentage Overall Passing decreased by 0.1%

###  How is the school summary affected?
The school summary for Thomas High School used to have following numbers:
![perfomance summary before](https://user-images.githubusercontent.com/109990578/188516895-16519daa-6f86-42ca-980f-3acfd28d004b.png)
![performance summary after](https://user-images.githubusercontent.com/109990578/188516898-3b1b021e-bfcc-43b9-8a3e-9ad93e0b445e.png)
We can deduct that;
  - The average Math score decreased by 0.06712 grade
  - The average Reading score increased by 0.047152 grade
  - percent of students who passed math reduced by 0.086481%
  - percent of students who passed reading reduced by 0.29013%
  - percent of students who passed both math and reading reduced by 0.317688%


###  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The following images shows that THS performance remained unchange in the list of the Top Performing Schools (before and after replacing the 9th graders for Math and Reading score) whereas, other schools performances was changed.

![thomas school top before replacing](https://user-images.githubusercontent.com/109990578/188517388-b347653b-e6f1-4c6b-9464-02c82c824494.png)

![thomas school top after replacing 9th](https://user-images.githubusercontent.com/109990578/188517400-8d5c3ea7-2ada-45fd-9740-fdf97aea0e65.png)

###  How does replacing the ninth-grade scores affect the following
Replacig the 9th grade scores of THS only affects THS 9th grade cells with **nan** values.
- Math and reading scores by grade
  
 The Initial Math scores by grade;

![old math score by grade](https://user-images.githubusercontent.com/109990578/188517720-0e4df0ff-5086-4bc1-8d12-bd6fa90d2f27.png)

New Math score after replacing the 9th grader;
    
![new math score after replacing 9th](https://user-images.githubusercontent.com/109990578/188517789-ea1e75de-1e0e-45ec-a3fa-778ae13ec8a2.png)

- The initial reading scores by grade;
  
![old reading score by grade](https://user-images.githubusercontent.com/109990578/188517890-7e729f5f-09fb-4b9b-bcf4-fac4e17be123.png)

- New Reading score after replacing the 9th grader;

![new reading score after replacing 9th](https://user-images.githubusercontent.com/109990578/188517920-00a4b1e9-492d-4899-89e0-9a51ef6f4cf0.png)

### Scores by school Spending
The following shows the score by school spending before and after THS 9th graders grades was remove(d); 
It can be seen that there was no significant effect on the school spending before and after replacing the 9th grade THS scores.


BEFORE

![spending summary before non format](https://user-images.githubusercontent.com/109990578/188518617-8e39afe1-6b15-42c0-9185-dc4844a5d90b.png)

![spending summary before formatted](https://user-images.githubusercontent.com/109990578/188518633-613a5e89-f6cc-4d07-8585-38dc0fa8477a.png)

AFTER

![spending summary after non format](https://user-images.githubusercontent.com/109990578/188518646-5778d752-9ad6-4fb7-a12d-2208e42dce4a.png)

![spending summary after formatted](https://user-images.githubusercontent.com/109990578/188518649-61aba864-0207-4371-828b-8e8ca3ab58b7.png)

### Scores by school size
The table below shows the school performances based on the school size

Initial table

![perfomance based on school size  before](https://user-images.githubusercontent.com/109990578/188531587-a6730116-232c-42a7-a16f-4a4411cb65a6.png)

After 9th grader was replaced for Math and reading;

![perfomance based on school size after](https://user-images.githubusercontent.com/109990578/188531610-ba6c93f7-40a4-479a-b4dc-648e15cca229.png)

Thomas High School is a medium sized school and it can be conclude that replacing the ninth-grade Thomas High School scores did not significantly affect scores by school size. 

### Scores by school type
 The initial performance of the schools based on type is shown below;
 
  ![type summary before](https://user-images.githubusercontent.com/109990578/188533317-0708dd58-112c-4d96-8e24-e5e9ca7f95f5.png)

After replacing 9th grade THS scores

![type summary after](https://user-images.githubusercontent.com/109990578/188533358-672573f8-a656-4ba6-b234-0408de5d596d.png)

 There are insignificant changes in charter schools' performance. In general, replacing the ninth-grade Thomas High School scores did not significantly affect scores by school type.
  
## SUMMARY
