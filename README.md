# School_District_Analysis
School District Research

## How We Got Here
### Examples of code and a new data set.
We refactored the original school testing data into a new data set where replaced the tests in question with Nan.
<img width="320" alt="refactor_code" src="https://user-images.githubusercontent.com/82114481/118425426-30cd2600-b697-11eb-958b-a911ee67fdd3.png">

We cleaned data to remove prefixes to names.
<img width="1165" alt="Cleaned Names" src="https://user-images.githubusercontent.com/82114481/118425368-0da27680-b697-11eb-89b1-622849aac3a8.png">

We created a new data set of the cleaned data.
<img width="1122" alt="Cleaned Summary" src="https://user-images.githubusercontent.com/82114481/118425706-b94bc680-b697-11eb-94f5-3a263c140826.png">

## Overview of the School District Analysis
### PyCity School Analysis
#### Purpose: Compare data from two sets to see if the removal of questionable results has any impact on test results and determine if we can correlation between any number of variables and success rates.
#### Results: 
- Once faked results were removed, Thomas High School saw the results plummet in math while stay the same in reading. Overall passing also dropped sharply from 91% to 65%
- When Thomas's results are excluded, it doesn't really effect the budget "overall passing" results when sorted by per student budget.
- The top 5 schools are all still charter schools while the lowest 5 school are all district schools and Thomas.
- Small and Medium sized schools have roughly similar results while larger schools lag behind.
- Charter schools still vastly outperform district schools even once we have cleaned and accounted for the discrepencies at Thomas High School.

## Summary
#### Observed Changes
Giving a NaN value to the illigitimate test scores at Thomas High School caused it's ranking overall to drop from near the top to down by the bottom. Removing this data did not really have any changes when accounting for per student budget as the poorest performing schools were already well funded. As a budget per student in the higher ratio, dropping to the bottom does not change this data. We still see charter schools dominating the top of performers list while district schools still are all district except for Thomas' inclusion. As a medium sized school, even when the inelligble results are removed and factored into the findings, larger schools are still the poorest performing. Excluding Thomas Highschool only significantly changes the data for Thomas. Most of the conclusions drawn from the data before it was cleaned can still be made post cleaning. 
