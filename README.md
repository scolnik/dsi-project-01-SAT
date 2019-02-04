
# Project 1: SAT & ACT Analysis

## Problem Statement

Analyze trends in SAT & ACT data from 2017 - 2018 and make recommendations to increase SAT participation and scores.

## Executive Summary

### Contents:
- 2017 Data Import & Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|name of state| 
|act_2017_participation|float|ACT 2017|percent participation in decimal| 
|act_2017_english|float|ACT 2017|average ACT English test score| 
|act_2017_math|float|ACT 2017|average ACT Math test score| 
|act_2017_reading|float|ACT 2017|average ACT Reading test score| 
|act_2017_science|float|ACT 2017|average ACT Science test score| 
|act_2017_composite|float|ACT 2017|average ACT composite score| 
|sat_2017_participation|float|SAT 2017|percent participation in decimal| 
|sat_2017_reading_and_writing|int|SAT 2017|average SAT Reading and Writing test score|
|sat_2017_math|int|SAT 2017|average SAT Math test score|
|sat_2017_total|int|SAT 2017|average SAT total score|
|act_2018_participation|float|ACT 2018|percent participation in decimal| 
|act_2018_composite|float|ACT 2018|average ACT composite score| 
|sat_2018_participation|float|SAT 2018|percent participation in decimal| 
|sat_2018_reading_and_writing|int|SAT 2018|average SAT Reading and Writing test score| 
|sat_2018_math|int|SAT 2018|average SAT Math test score| 
|sat_2018_total|int|SAT 2018|average SAT total score|


### Sources:
SAT data: https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/
ACT data: https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows
SAT School Day program: https://blog.prepscholar.com/which-states-require-the-sat

## Conclusions and Recommendations

### Conclusions:  

#### SAT School Day
The SAT School Day program seems to be having a positive effect on participation. States participating in SAT School Day had an average SAT participation rate of approx. 72.9% vs 34.8% in other states in 2018. However, higher participation rates also correlate with lower average scores. SAT School Day schools had average score of 1032.4 vs 1161.6 in other states in 2018.

### Recommendations:  

#### Targets for Improvement
These states are targets for improvement. I recommend additional investment in the SAT School Day program for the states in the program that have the lowest SAT participation rate, and DC which saw the largest decrease from 2017 to 2018. I also recommend targeting the states with the lowest SAT participation rates to join SAT School Day, as they have the biggest potential for impact on participation. They don't already require the ACT, so they may also be more open to increasing SAT participation than the ACT-mandatory states.
- District of Columbia (largest decrease in SAT participation from 2017 to 2018, from 100% to 92%)
- states already in SAT School Day with lowest 2018 participation rates: Tennessee, Oklahoma; and lowest 2018 scores: DC (977 total), Delaware (997 total)
- states w/lowest 2018 SAT participation rates (not already requiring ACT): Oklahoma (8%), Ohio (18%) 

#### Top Performers
These states are success stories for SAT. Perhaps with additional data on the strategies these states used for participation and scores, we could develop additional recommendations.

- Illinois (largest increase in SAT participation, from 9% to 99%)

- Michigan, Connecticut and Delaware were the only states with 100% SAT participation in both 2017 and 2018

- top 2018 SAT scores: 
Minnesota: 1298
Wisconsin: 1294
North Dakota: 1283

