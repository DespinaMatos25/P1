# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SAT & ACT Analysis

### Table of Contents:

- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Data Dictionary](#Data-Dictionary)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [Sources](#Sources)

---
### Problem Statement

When a person becomes a high school junior in the United States, they will need to either take the Scholastic Aptitude Test or the American College Testing examination for the admission process to get into college. Yearly, the CollegeBoard and ACT organizations release it's data sets to the public. The SAT data set includes the averages of the participation rates, the averages of the evidence based reading and writing subtest, the averages of the math subtest, and the total averages of all subtests. The ACT data includes the averages of the participation rates, the averages of the english subtest, the averages of the reading subtest, the averages of the math subtest, the averages of the science subtest, and the total averages of all subtests. 

The SAT is scored out of a 1600 and the ACT is scored out of a 36. The SAT subtests have a minimum of 400 and a maximum of 800. The ACT subtests have an average out of 36. 

Given the SAT and ACT datasets from 2017 to 2018, my goal is to identify where the CollegeBoard resources should be implemented to have higher participation rates for its exams. I will need to seek trends in the data sets and analyize the outcomes. Lastly, I will need to combine my data with outside research to identify factors that are influencing the participation rates and scores in states across the country. 


---

### Executive Summary

My approach was first to import and clean the data sets. In cleaning my data I was looking for key factors. In this data set, is it complete? Does it have incorrect numbers in each row? Does the minimum and maximum numbers have identical numbers to the SATs and ACTs minimums and maximums? Are the data types in the correct format? Is there an extra row in the data set? And finally, is the coulumns in the data set named clearly? 

After cleaning the data sets, I was able to megre all data sets into one clear polised data set. I called this data set the final data set and it had the combined SAT 2017, SAT 2018, ACT 2017, and ACT 2018 datasets. 

Next, I went straight into modeling our data set. Visualizing our data was a *huge* help in finding trends. I created a heatmap, histograms, scatterplots, and boxplots. For the heatmap, I wanted to find the correlations between all numeric features. For the histograms, I compared distributions in my data set. For scatterplots, I wanted to see the correlations between different columns in my data set. For boxplots, I wanted to see if there was any outliers in my data set. 

Lastly, I was able to do outside research on three different states to see what interesting trends lead to their participation rates in the SATs and ACTs. I chose states from three different locations in the country to have a bigger popluation sample. I chose Lousiana(18), Colorado(5), and New Mexico(31). I found some intriguing discoveries. 

In my final step, I was able to draw conclusions and suggest recommendations to the CollegeBoard about where to aggregate the organizations resources to help better participation rates. 

---

### Data Dictionary 

Here is the SAT 2017 and ACT 2017 dictionary for the column names.

|Feature|Type|Dataset|Description|
|---|---|---|---|
|2017_sat_participation_rate|*float*|SAT|SAT participation rates tells us how many students participated in each state| 
|2017_sat_reading_and_writing_subtest|*integer*|SAT|SAT reading and writing subtest scores tells us the averages in each state| 
|2017_sat_math_subtest|*integer*|SAT|SAT math subtest scores tells us the averages in each state| 
|2017_sat_total_of_subtests|*integer*|SAT|SAT total of subtests tells us the averages of the subtests in each state| 
|2017_act_participation_rate|*float*|ACT|ACT participation rates tells us how many students participated in each state| 
|2017_act_english_subtest|*float*|ACT|ACT english subtest scores tells us the averages in each state| 
|2017_act_math_subtest|*float*|ACT|ACT math subtest scores tells us the averages in each state| 
|2017_act_reading_subtest|*float*|ACT|ACT reading subtest scores tells us the averages in each state|
|2017_act_science_subtest|*float*|ACT|ACT science subtest scores tells us the averages in each state|
|2017_act_total_of_subtests|*float*|ACT|ACT total of subtest tell us the averages of the subtests in each state|

Here is the SAT 2018 and ACT 2018 dictionary for the column names. 

|Feature|Type|Dataset|Description|
|---|---|---|---|
|2018_sat_participation_rate|*float*|SAT|SAT participation rates tells us how many students participated in each state| 
|2018_sat_reading_and_writing_subtest|*integer*|SAT|SAT reading and writing subtest scores tells us the averages in each state| 
|2018_sat_math_subtest|*integer*|SAT|SAT math subtest scores tells us the averages in each state| 
|2018_sat_total_of_subtests|*integer*|SAT|SAT total of subtests tells us the averages of the subtests in each state| 
|2018_act_participation_rate|*float*|ACT|ACT participation rates tells us how many students participated in each state| 
|2018_act_total_of_subtests|*float*|ACT|ACT total of subtest tell us the averages of the subtests in each state|


---

### Conclusions and Recommendations

#### Key Takeways: 

#### In general: 

- The SAT exam and the ACT exam has no correlation. One can not compare each examination to one another because they have different sections. Also there are different study methods for each examination.

- The total SAT scores from 2017 to 2018 have a positive correlation. The students who took the test in 2018 had higher scores than the students who took the exam in 2017.

- The total ACT scores from 2017 to 2018 have a negative correlation. The students who took the test in 2018 had lower scores than the students who took the exam in 2017.


- The participation rates for the SAT exams from 2017 to 2018 has a positive correlation. The states that took the SAT exam in 2017 continue to increase scores in 2018.

- The participation rates for the ACT examas from 2017 to 2018 also has a positive correlation. The states that took the ACT exam in 2017 continue to increase score in 2019.

- States with higher participation rates in either test almost always have much lower scores.  

- The highest total average score for the SAT 2017 and SAT 2018 was in Minnesota. 

- The lowest total average score for the SAT 2017 was D.C.

- The lowest total average score for the ACT 2017 was Maine.

- The highest total average score for the ACT 2018 was Connecticut.

- The lowest total average score for the SAT 2018 was D.C.

- The lowest total average score for the ACT was Nevada. 

#### In the *east coast*: 

- The SATs has a higher participation rate than the ACTs. 
- Even if the ACT is not widely taken, the ACT total average scores increased from 2017 to 2018. 
- The SATs total averages scores increased from 2017 to 2018.
- The ACTs scores are the highest compare to the rest of the country. 

#### In the *south*:

- Most of the states are not required to take the SATs, so most states have a higher participation rate in the ACTs.
- Most states actually take the ACTs instead of taking their state exams.
- Those who took the SATs do well on the exams from 2017 to 2018.
- Those who took the ACTs lower their total averages from 2017 to 2018.

#### In the *midwest*:
- The SATs scores are the highest compare to the rest of the country. 
- The ACTs average scores from 2017 to 2018 are about same as an average ACT taker.
- Some states have lower participation rates in the SATs than others in this region. 
- Some states have lower participation rates in the ACTs than others in this region.

#### In the *west coast/south west*: 
- The SATs has a higher participation rate than the ACTs.
- The average scores for the SATs datasets and ACTs datasets vary.
- Nevada and New Mexico are the outliers for both SATs and ACTs data sets.

### Recommendations


- There is missing data in the act 2018 dataset. The catergories that are missing are the subtests of the ACT 2018 exam. The CollegeBoard should provide the full data set for further analysis. 
- The CollegeBoard should not consider the participation rates as the only success, it should also consider how students prep for the exam as well as a success.
- The CollegeBoard needs improvements on their test prep. 
- The CollegeBoard needs to fix it's contracts with individual states so students in that state have a fair opportunity to take the exam.
- The CollegeBoard should pay for fees. 
- The CollegeBoard needs to look at what students prefer to take and why.

---

### Sources

“How to remove a value from a list in a Pandas dataframe?” Stackoverflow, https://stackoverflow.com/questions/45488968/how-to-remove-a-value-from-a-list-in-a-pandas-dataframe. Accessed 17 December 2019. 


“Dictionary comprehension to apply a function to DataFrame columns.” Stackoverflow, https://stackoverflow.com/questions/55048445/dictionary-comprehension-to-apply-a-function-to-dataframe-columns. Accessed 18 December 2019.


Contreras, Russell. “How proficient are New Mexico students in math and reading? State releases latest results.” Las Cruces Sun News, https://www.lcsun-news.com/story/news/education/2019/07/26/less-than-third-new-mexico-students-test-proficient/1844444001/. Accessed 18 December 2019.


Strauss, Valerie. “New Mexico’s new governor ending PARCC standardized testing to evaluate students, teachers.” The Washington Post, https://www.washingtonpost.com/education/2019/01/04/new-mexicos-new-governor-ending-parcc-standardized-testing-evaluate-students-teachers/. Accessed 18 December 2019.


Whaley, Monte. “Colorado juniors face new, revamped college exam in SAT after state dumps rival ACT.” The Denver Post, https://www.denverpost.com/2017/03/06/colorado-juniors-sat-college-exam/. Accessed 18 December 2019.


Gorski, Eric. “Goodbye ACT, hello SAT: a significant change for Colorado high schoolers.” Chalkbeat, https://www.chalkbeat.org/posts/co/2015/12/23/goodbye-act-hello-sat-a-significant-change-for-colorado-high-schoolers/. Accessed 18 December 2019. 


Simmons, Olivia. “The Condition of College & Career Readiness 2017 : Louisiana Key Findings.” ACT, https://www.act.org/content/dam/act/unsecured/documents/cccr2017/Louisiana-CCCR-2017-Final.pdf. Accessed 18 December 2019.


Anderson, Nick. “SAT usage declined in 29 states over seven years.” The Washington Post, https://www.washingtonpost.com/local/education/sat-usage-declined-in-29-states-over-7-years/2014/03/15/f4504cfc-a5ff-11e3-8466-d34c451760b9_story.html. Accessed 18 December 2019. 


Gewertz, Catherine. “Which States Require Students to Take the SAT or ACT?” Education Week, https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html. Accessed 18 December 2019. 
