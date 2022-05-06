# Introductory Research for Grant Funding: Analysis of SAT/ACT Scores, Participation Rates, and Mental Health

### Emily Gama - Data Scientist for Safe Education Non-Profit


### Problem Statement and Background: 
Thank you for being here today. My name is Emily Gama. I work for a non-profit called Safe Education. We focus on ensuring high school students in the United States enjoy accessible, safe, and fulfilling education that gives them the foundation to feel successful in whatever life path they choose. We believe that education is extremely important for young people, but also understand that college may not be for everyone. The expectation of attending college and No Child Left Behind policies have ensured that standardized 'college-readiness' tests like the SAT and ACT are very popular and often required to graduate high school. Twenty-six states in the US still require students to take one test or the other in order to graduate (<a href="https://prepmaven.com/blog/test-prep/states-require-sat-act/" target="_blank">Source</a>).

We are here today because I would like us to apply for grant funding to deepen our research on this. This project will look at participation rates and score averages for the SAT and ACT from 2017 and 2019 to explore the relationship between these two aspects. After I analyzed outside research and the initial data, I found that these graduation requirements may be hurting student performance. And, students on average perform better when there is no requirement in place. Those that do not want to take the exams do not have to. Because we don't have enough data yet to delve into this topic further, I am hoping to show you today that this is an important topic to study. I hope that we can pursue this grant funding as our next organization-wide project. 

Explicitly: The problem I approached in my project is that standardized testing has been shown to be ineffective and cause increased academic stress. While 76% of colleges are now making the SAT and ACT optional, in 26 states, they are still required to graduate meaning the pressure is still on. I will examine the trends in SAT and ACT scores and participation rates from 2017 to 2019, including outside research on mental health in high school, in hopes to make recommendations on what our next grant application will entail.


### Description of Data

The three datasets included in this project are the ACT and SAT scores by state. These datasets also include the participation rates for each test. This data comes from the ACT and SAT National Reports each year.
2017 ACT Scores by State (<a href="https://www.act.org/content/act/en/research/pdfs/act-national-profile-report-2017.html" target="_blank">Source</a>)
2018 ACT Scores by State (<a href="https://www.act.org/content/dam/act/unsecured/documents/cccr2018/National-CCCR-2018.pdf" target="_blank">Source</a>)
2019 ACT Scores by State (<a href="https://www.act.org/content/dam/act/unsecured/documents/National-CCCR-2019.pdf" target="_blank">Source</a>)
2017 SAT Scores by State (<a href="https://reports.collegeboard.org/pdf/2017-total-group-sat-suite-assessments-annual-report.pdf" target="_blank">Source</a>)
2018 SAT Scores by State (<a href="https://reports.collegeboard.org/pdf/2018-total-group-sat-suite-assessments-annual-report.pdf" target="_blank">Source</a>)
2019 SAT Scores by State (<a href="https://reports.collegeboard.org/pdf/2019-total-group-sat-suite-assessments-annual-report.pdf" target="_blank">Source</a>)

These datasets were cleaned and merged into the following final datasets you'll see referenced in the project: 

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|*object*|all datasets|The state name in alphabetical order|
|act_participation_2017|*float*|act_2017clean, act_merged| The participation rate by state of graduating high school students who took the ACT during the 2016/2017 year (in decimal form, ex: .40 means 40%)|
|act_composite_2017|*float*|act_2017clean, act_merged| The composite score (average of the four subjects) for the graduating high school students who took the test during the 2016/2017 year|
|act_participation_2018|*float*|act_2018clean, act_merged| The participation rate by state of graduating high school students who took the ACT during the 2017/2018 year (in decimal form, ex: .40 means 40%)|
|act_composite_2018|*float*|act_2018clean, act_merged| The composite score (average of the four subjects) for the graduating high school students who took the test during the 2017/2018 year|
|act_participation_2019|*float*|act_2019clean, act_merged| The participation rate by state of graduating high school students who took the ACT during the 2018/2019 year (in decimal form, ex: .40 means 40%)|
|act_composite_2019|*float*|act_2019clean, act_merged| The composite score (average of the four subjects) for the graduating high school students who took the test during the 2018/2019 year|
|sat_participation_2017|*float*|sat_2017clean, sat_merged| The participation rate by state of graduating high school students who took the SAT during the 2016/2017 year (in decimal form, ex: .40 means 40%)|
|sat_total_2017|*integer*|sat_2017clean, sat_merged| The total score (sum of the two subjects) for the graduating high school students who took the test during the 2016/2017 year|
|sat_participation_2018|*float*|sat_2018clean, sat_merged| The participation rate by state of graduating high school students who took the SAT during the 2017/2018 year (in decimal form, ex: .40 means 40%)|
|sat_total_2018|*integer*|sat_2018clean, sat_merged| The total score (sum of the two subjects) for the graduating high school students who took the test during the 2017/2018 year|
|sat_participation_2019|*float*|sat_2019clean, sat_merged| The participation rate by state of graduating high school students who took the SAT during the 2018/2019 year (in decimal form, ex: .40 means 40%)|
|sat_total_2019|*integer*|sat_2019clean, sat_merged| The total score (sum of the two subjects) for the graduating high school students who took the test during the 2018/2019 year|

### Strategy and Analysis

I specifically wanted to look at the relationship between participation rates and test scores. I created several visualizations to explore this. This relationship showed a negative correlation between scores and participation rates. To explain more clearly, when participation rates are low, the scores are higher; and, when participation rates are high, the scores are lower. One state where this is shown very clearly is Colorado. In my project, I explore a brief case study of the state and the background that could explain the inverted relationship.

### Conclusion and Recommendations

Initially, I sought out to explore the relationship between standardized testing participation rates and their scores. I had already addressed the background of the tests, understanding that test anxiety and mental health alone can have an impact on performance. What I found in the data is that when there is a requirement or a push for 100% participation, student performance suffers. Colorado's findings show us that when the pressure is off, students may actually do better. 

My conclusion from the data I analyzed is that there is some relationship between lower participation rates and higher scores, showing potential that the lack of requirement helps students who want to take the tests to feel more comfrotable on exam day. My recommendation is that we apply for grant funding to research the intersection of these two issues: required standardized testing and mental health of young people. A recent, robust study for this potential relationship does not yet exist in the US, and I hope today's presentation gives you the foundation to see why it would be important for us to accomplish. 

### Next steps

If I were to do this project again, I would give myself more time and breadth to dig deeper, explore more meaningful relationships, and focus more heavily on the impact of standardized testing as a whole. I am proud of the work I've done, and look forward to continuing to grow in my skills.

