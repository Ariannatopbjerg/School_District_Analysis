# School_District_Analysis
### Programming software used: Anaconda, Jupyter Notebook; Language: Python

## Purpose of Analysis
This analysis will assist a school board and super intendant of a school district in making decisions in regarding the school budgets and priorities. The school district data will be analyzed for insights about school performance trends and patterns for all standardize test taking. The insights will be used to inform discussions and strategic decisions at the school and district level. Unfortunately, the school board had found out that their data file shows evidence of academic dishonesty; specifically, math and reading scores for one of Thomas High School's grades. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. The data will be altered so that the dishonest scores will be removed from that data and the analysis with proceed. 
## Analysis Results
Having the data altered by removing the dishonest test scores for the analysis, there was some differences among the before and after district summary and school summary. 

### District Summary Changes
**District summary with total test scores**
![](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/images/districtsum_old.PNG)
**District summary without dishonest test scores**
![](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/images/districtsum_new.PNG)
#### Summary conclusion:
By removing the dishonest scores, there is no real significant change to the original district summary. There is a slight reduction to the percentages of passing scores - 0.5 to 1% difference, but again, it is not a drastic change.
### School Summary Changes
The only thing that changed with the school summary dataframe was that now, Thomas High School in the second best school in relation to performance scores. Rather than before the taking out of the ninth graders' scores, the school was third from the bottom.
### Thomas High School Performance Change
Thomas high School did have a drastic change in their testing performance in relation to the rest of the schools in the district. Before the scores were removed from the summary, the passing percentages were among the 60s percentile. Once the scores were removed from the dataset, the percentages jumped up to be in the 90s percentile. 

**Links to summary dataframe and Thomas High School data can be found here:** [Updated School Summary](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/images/school_summary_new.PNG) & [School Summary](https://github.com/Ariannatopbjerg/School_District_Analysis/blob/main/images/school_summary_old.PNG)

### Rest of data results
The rest of the analysis stayed the same after taking out the ninth grade test scores.
#### Summary conclusion:
The removal of the dishonest scores had improved the schools performance imensley. 
## Analysis Summary 
