# NHAMCS-2013-data-analysis
This project aims to explore and analyze real-world medical care data in order to discover and
understand the factors that impact the duration of wait time patients experience in order to see a
healthcare provider in the emergency room. Specifically, this study aims to discover if the wait
time increases during the holiday periods or based the racial group of the patient, and to understand
five of the most important numeric and categorical variables in the data that have the best ability
to predict how long a patient will have to wait to see a healthcare provider in the emergency room.
This report describes the statistical analysis performed for the objectives of this study and
summarizes the conclusion met based on them.

## T-test overview: 
The t-test is a statistical method used to compare the means of two groups and
determine if there is a significant difference between them. The t-test produces a t-statistic and a
p-value, which help assess the strength of evidence against the null hypothesis.

## Summary/Results:
From the National Hospital Ambulatory Medical Care Survey (NHAMCS) data, we performed t-
test analysis to analyze the relationship between the wait times based on Races and wait times
based on the holidays or non-holiday periods. We found that there is a significant difference
between racial minority and majority groups. We concluded that the racial majority groups have
to wait for less time than the minority groups. Moreover, we found out that the wait times do not
vary depending on whether it is a holiday or not a holiday.
Lastly, to predict the top 5 factors which affect the wait time of the patients, we used Random
Forest Regressor. This gives 19.2% accuracy on the test set.
And top 5 features can be tabulated as -

![image](https://github.com/priyankaa370/NHAMCS-2013-data-analysis/assets/81320366/45ed67a7-9d43-4564-afa2-92acfc170679)
