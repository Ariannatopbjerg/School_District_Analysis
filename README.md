# School_District_Analysis
**Programming software used: Anaconda, Jupyter Notebook; Language: Python**

**Code for analysis: [PyCitySchools](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)**

## Purpose of Analysis
This analysis will assist a school board and super intendant with their school district data, in making decisions in regarding the school budgets and priorities. The school district data will be analyzed for insights about school performance trends and patterns for all standardize test taking. The insights will be used to inform discussions and strategic decisions at the school and district level. Unfortunately, the school board had found out that their data file shows evidence of academic dishonesty; specifically, math and reading scores for the Thomas High School ninth grade. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. The data will be altered so that the dishonest scores will be removed from that data and the analysis with proceed. 

## Analysis Results
Having the data altered by removing the dishonest test scores for the analysis, there was differences among the before and after district summary, school summary, and Thomas High School passing scores. 

### District Summary Changes
**District summary with total test scores**:

![](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/images/district_sum_old.PNG)

**District summary without dishonest test scores**:

![](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/images/district_sum_new.PNG)

***Conclusion:***
By removing the dishonest scores, there is a slight reduction to the percentages of passing scores - 0.5% to 1% difference; which is not a huge significance. 

### School Summary Changes
The only thing that changed with the school summary dataframe was that now, Thomas High School, is the second best school in relation to performance scores. Rather than before the taking out of the ninth graders' scores, the school was third from the bottom.

### Thomas High School Performance Change
Thomas high School did have a drastic change in their testing performance in relation to the rest of the schools in the district. Before the scores were removed from the summary, the passing percentages were in the 60s. Once the scores were removed from the dataset, the percentages jumped up to be in the 90s. 

**Links to summary dataframe and Thomas High School data can be found here:** [Updated School Summary](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/images/school_summary_new.PNG) & [School Summary](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/images/school_summary_old.PNG)

***Conclusion:***
The removal of the dishonest scores improved Thomas high School's performance immensely.

### Analysis data that stayed the same:
- Math and reading scores by grade
- Scores by school spending
- Scores by school size
- Scores by school type

***Conclusion:***
Since the math and reading scores of the ninth graders at Thomas High School were replaced with Nan in the dataset, the rest of the scores by grade had no effect. The other three analyses had any drastic changes to them.
