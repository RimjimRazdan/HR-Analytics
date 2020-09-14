# HR-Analytics

## Problem statement:

Our client is a large MNC and they have 9 broad verticals across the organisation. One of the problem our client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

They first identify a set of employees based on recommendations/ past performance selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical

At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion

For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 

They have provided multiple attributes around Employee's past and current performance along with demographics. Now, the task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

Website: https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1/

## Dataset Description

1. employee_id:	Unique ID for employee
2. department:	Department of employee
3. region:	Region of employment (unordered)
4. education:	Education Level
5. Gender:	Gender of Employee
6. recruitment_channel:	Channel of recruitment for employee
7. no_of_trainings:	no of other trainings completed in previous year on soft skills, technical skills etc.
8. age:	Age of Employee
9. previous_year_rating: Employee Rating for the previous year
10. length_of_service:	Length of service in years
11. KPIs_met: >80%	if Percent of KPIs(Key performance Indicators) >80% then 1 else 0
12. awards_won?: if awards won during previous year then 1 else 0
13. avg_training_score:	Average score in current training evaluations
14. is_promoted: (Target) Recommended for promotion

## Evaluation Metric

The evaluation metric for this competition was F1 Score.

### Best Score: 

XGBoostClassifier : 0.479793637145314
