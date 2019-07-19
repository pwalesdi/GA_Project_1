# Analysis of aggregate SAT & ACT Data from 2017 & 2018

Problem Statement:

Determine what relationships exist between SAT Scores, ACT Scores, SAT Participation Rates and ACT Participation rates. Understanding these relationships will help us to comprehend the US testing landscape better and to make recommendations about how to change or improve it from a business perspective and perhaps from an ethical perspective. 

Executive Summary
Contents:
2017 Data Import & Cleaning
2018 Data Import and Cleaning
Exploratory Data Analysis
Data Visualization
Descriptive and Inferential Statistics
Outside Research
Conclusions and Recommendations


Data Dictionary

| Statistic | Summary Stats | Distribution | Notes |
| --- | --- | --- | --- |
| 2017 ACT Participation | Mean = 65.25, s = 32.14| This data does not appear to be normally distributed | ACT Participation is being dramatically effected by states that are requiring the test |
| 2018 ACT Participation | Mean = 61.69, s = 34.03| This data does not appear to be normally distributed | ACT Participation is being dramatically effected by states that are requiring the test |
| 2017 ACT Composite Score | Mean = 21.52, s = 2.02| This data does not appear to be normally distributed | Among states that require participation in the ACT the data seem to approximate the normal distribution |
| 2018 ACT Composite Score | Mean = 21.50, s = 2.12| This data does not appear to be normally distributed | Among states that require participation in the ACT the data seem to approximate the normal distribution |
| 2017 SAT Participation | Mean = 39.80, s = 35.27| This data does not appear to be normally distributed | The data are heavily influenced by state requirements with very few states requiring the test and very few test takers in states that require the ACT |
| 2018 SAT Participation | Mean = 46.60, s = 38.01| This data does not appear to be normally distributed | The data are heavily influenced by state requirements with very few states requiring the test and very few test takers in states that require the ACT |
| 2017 SAT Composite Score | Mean = 1126.10, s = 92.50| This data does not appear to be normally distributed | The distribution is being heavily influenced by the states that have very low participation rates. These states are skewing the data to have higher outputs in states with a smaller participation |
| 2018 SAT Composite Score | Mean = 1124.67, s = 93.86| This data does not appear to be normally distributed | The distribution is being heavily influenced by the states that have very low participation rates. These states are skewing the data to have higher outputs in states with a smaller participation |
| 2017 SAT Math Score | Mean = 556.8, s = 47.18| This data does not appear to be normally distributed | This math data is also being affected by huge differences in the participation rate |
| 2017 SAT Evidence Based Reading and Writing Score | Mean = 569.1, s = 45.67| This data does not appear to be normally distributed | This EBRW data is also being affected by huge differences in the participation rate |
| 2017 ACT Math | Mean = 21.18, s = 1.98 | This data does not appear to be normally distributed | This is also being affected by huge differences in the participation rate | 
| 2017 ACT Science | Mean = 21.45, s = 1.73 | This data does not appear to be normally distributed | This is also being affected by huge differences in the participation rate | 
| 2017 ACT English | Mean = 20.93, s = 2.35 | This data does not appear to be normally distributed | This is also being affected by huge differences in the participation rate |
| 2017 ACT English | Mean = 22.01, s = 2.06 | This data does not appear to be normally distributed | This is also being affected by huge differences in the participation rate | 

Other thoughts and idea to follow up on:
It would be great to run a regression analyzing the relationships between participation
levels and scores. This could help us conclude which states are underperforming/over-performing relative to their participation rates.

It would also be interesting to get other data from prior years to compare and do a more robust analysis.

Data Sets:
2018 ACT Data: https://github.com/pwalesdi/GA_Project_1/blob/master/data/ACT_2018.csv
2018 SAT Data: https://github.com/pwalesdi/GA_Project_1/blob/master/data/SAT_2018.csv
2017 ACT Data: https://github.com/pwalesdi/GA_Project_1/blob/master/data/act_2017.csv
2017 SAT Data: https://github.com/pwalesdi/GA_Project_1/blob/master/data/sat_2017.csv
Final Data Frame: https://github.com/pwalesdi/GA_Project_1/blob/master/data/final.csv

Other Resources: 
https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html

https://www.chalkbeat.org/posts/co/2015/12/23/goodbye-act-hello-sat-a-significant-change-for-colorado-high-schoolers/