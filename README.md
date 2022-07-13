# PyCity School Analysis
## July 13, 2022

#### **Overview**
The purpose of this project was to analyze a school district's state tesing scores. A comprehensive analysis was done that showed the average of each schools performance, which was further broken down by school size, school budget, and school type. A school was proven to have conducted academic dishonesty, which caused a re-evaluation of all analysis without Thomas High School's ninth grade scores. The two analysis were then compared with each other. The python pandas package was used for this project using jupyter as the text editor. 
#### **Results**
##### 1. How is the district summary affected?
The district summary reported looks to show the same values,when rerunning the analysis for all of the testing scores. This could be indicative that Thomas High School worked to fudge their ninth grade scores so that they would stay at the same performance of their tenth, eleventh, and twelth grade students.
District Summary with dishonest ninth grader performance numbers[^1]
District Summary excluding all Thomas high schools ninth grade[^2]
##### 2. How is the school summary affected?
The school summary analysis with all the ninth grade students scores put in as zeroes, significantly drops Thomas High School performance in 60-70 percent range across both reading and math tests.[^3] When this was corrected for, by reconducting the analysis for only tenth, eleventh, and twelfth grade students of Thomas High School. The performance went up to around the same percentages as the summary with the dishonest ninth grade scores.
School Summary with dishonest ninth grader performance numbers[^4]
School Summary excluding all Thomas high schools ninth grade[^5]
##### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
When replacing the ninth grade scores for Thomas High School with NaN. This caused the school's performace to significantly drop relative to other schoools. This put the school in the middle of all district school in terms of overall passing percentage. 
##### 4. How does replacing the ninth-grade scores affect the following:
######   * Math and reading scores by grade
Thomas High School ninth graders went from an average math score of 83.6, which was consistent with other Thomas High School grades performance, to a score of NaN. ![6](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_FudgedNinthGrade_MathScores.png) ![7](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_NaNNinthGrade_MathScores.png) Thomas High school ninth graders went from an average reading score of 83.7, which was consistent with other Thomas High School grades performance, to a score of NaN. ![8](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_FudgedNinthGrade_ReadingScores.png) ![9](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_NaNNinthGrade_ReadingScores.png) The ninth graders previous scores seems to be a score that would have made sure the mean of the school would stay consistent the mean of only the tenth, eleventh, and twelfth graders. This further provides some evidence that they tried to replicate the same performance, and why the district and school summary performace when only showing performace for tenth, eleveth, and twelth graders is the same as summaries with the fudged ninth grade numbers.
######   * Scores by school spending
Scores by school spending stayed the same. 
######   * Scores by school size
Scores by school size stayed the same
######   * Scores by school type
Scores by school type stayed the same. 
#### **Summary**
Overall, the changes in the performance when the ninthe graders were excluded fromt he analysis stayed relatively the same. This is evident as the district schools summary overall passing percentage stays the same, the scores by school spending stays the same, the scores by school size stays the same, and the scores by school type stays the same. Th only slight difference is in the school summary report. However, the scores are only off by a hundreth or tenth of a point. This slight difference explains why the overall scores for all the other analysis stayed the same. 


[^1]![1](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_FudgedNinthGrade_DistrictSummary.png)
[^2]![2](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_NoNinthGrade_DistrictSummary.png)
[^3]![3](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_NaNNinthGrade_SchoolSummary.png)
[^4]![4](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_FudgedNinthGrade_SchoolSummary.png)
[^5]![5](https://github.com/encollin94/Python-Pandas-Project/blob/main/PyCity_Schools_NoNinthGrade_SchoolSummary.png)
