# Tina's Project - ACT/SAT Scores Pattern and Insights Analysis

## Problem Statement

**Tips for Increasing SAT Participation Rate in States:**
* Who leads the trend now? SAT or ACT?
* Which states are our target?
* How to increase our market share on standardized tests?

---
## Background

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for each test):
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry. Lately, more and more schools are opting to drop the SAT/ACT requirement for their Fall 2021 applications ([*read more about this here*](https://www.cnn.com/2020/04/14/us/coronavirus-colleges-sat-act-test-trnd/index.html)).

---
## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|**ACT/SAT**|50 states in the U.S.| 
|participation_17_act|float|**ACT**|2017 state ACT participation rate| 
|score_17_act|float|**ACT**|2017 state mean ACT total score| 
|participation_18_act|float|**ACT**|2018 state ACT participation rate| 
|score_18_act|float|**ACT**|2018 state mean ACT total score| 
|participation_19_act|float|**ACT**|2019 state ACT participation rate| 
|score_19_act|float|**ACT**|2019 state mean ACT total score|
|participation_17_sat|float|**SAT**|2017 state SAT participation rate|
|ebrw_17|int|**SAT**|2017 state mean SAT Reading and Writing score|
|math_17|int|**SAT**|2017 state mean SAT Math score|
|score_17_sat|int|**SAT**|2017 state mean SAT total score|
|participation_18_sat|float|**SAT**|2018 state SAT participation rate|
|ebrw_18|int|**SAT**|2018 state mean SAT Reading and Writing score|
|math_18|int|**SAT**|2018 state mean SAT Math score|
|score_18_sat|int|**SAT**|2018 state mean SAT total score|
|participation_19_sat|float|**SAT**|2019 state SAT participation rate|
|ebrw_19|int|**SAT**|2019 state mean SAT Reading and Writing score|
|math_19|int|**SAT**|2019 state mean SAT Math score|
|score_19_sat|int|**SAT**|2019 state mean SAT total score|
|rank_happy|int|**rank_happiest_states_2019**|2019 the rank of the happiest states in the U.S. (source: [These Are 2019's Happiest States In America](https://www.iheart.com/content/2019-09-10-these-are-2019s-happiest-states-in-america/))|
|rank_rich|int|**rank_richest_2019**|2019 the rank of the richest states in the U.S. according to their median household income in 2018 (source: [Ranked: These Are The Richest States In The U.S. 2019](https://ceoworld.biz/2019/10/07/ranked-these-are-the-richest-states-in-the-u-s-2019/))|
|governor|object|**political_map_2020**|The governor party of each states in the U.S. (source: [Political party strength in U.S. states](https://en.wikipedia.org/wiki/Political_party_strength_in_U.S._states))|

---
## Conclusions and Recommendations

1. SAT and ACT are substitute products and they share the same market.
2. According to our study, the growth of one test's participation rate will inversely affect the other test.
3. The best way to grow the SAT participation rate is to make the SAT test mandatory.
4. Try to target blue states to increase the market share.
