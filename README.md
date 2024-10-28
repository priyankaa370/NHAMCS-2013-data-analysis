# NHAMCS-2013-data-analysis
This project aims to explore and analyze real-world medical care data in order to discover and
understand the factors that impact the duration of wait time patients experience in order to see a
healthcare provider in the emergency room. 

## Understanding the need:
According to the source, the average wait time in an emergency room to see a doctor is over 2 hours, while for a primary care doctor, it is approximately 18 minutes. To reduce these wait times and provide care faster, it is essential first to understand the underlying causes. The objective of this project is to determine whether factors such as the holiday season and racial demographics influence wait times and to identify the elements that most significantly impact these wait times.


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
