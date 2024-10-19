![alt text](slide1.jpg)

Using EDA, KPI's, hypothesis testing & Tableau dashboard to understand A/B test result and assist data driven decision.

## Introduction
 Vanguard, the US-based investment management company, believed that a more intuitive and modern User Interface (UI), coupled with timely in-context prompts (cues, messages, hints, or instructions provided to users directly within the context of their current task or action), could make the online process smoother for clients. The critical question was: Would these changes encourage more clients to complete the process?

An A/B test was set into motion from 3/15/2017 to 6/20/2017 by the team.

Control Group: Clients interacted with Vanguard’s traditional online process.
Test Group: Clients experienced the new, spruced-up digital interface.

Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.

# Goal
-Whether the new design leads to a better user experience
-Whehter the new design leads to a higher process completion rate

## Data Overview
We have the following datasets:
- Client Profiles: Demographics like age, gender, and account details.
- Client Roster: List indicating which clients were the part of the experiment and whether they belonged to the test group or the control group.
- Client Activity: A detailed trace of client interactions online.


## Data Exploration and Cleaning 
To understand the nature and structure of datasets, initial exploration was done and data cleaning problems were fixed.

- Null values
- Duplicates
- Renaming variable
- Mapping gender & process step column
- Defining 2 dataframe on each group to conduct separate analysis


## KPI's
- Completion rate
- The average duration users spent on each step
- Error rate



## Hypothesis testing: Statically proved through analysis

COMPLETION RATE
H0: The completion rate is lower for the new interface. 
H1: The completion rate is higher for new interface.

P-value:  2.35e^-69 (We reject the null hypothesis.)

TIME SPENT ON EACH STEP
H0: Average time spent on the steps is longer on new interface.
H1: Average time spent on the steps is shorter on new interface.  

P-value: 2.72e^-12 (We reject the null hypothesis.)

### Presentation link: 
https://www.canva.com/design/DAGUBOwPBJs/SXmKE-NK7QlMyhI00E1LOQ/view?utm_content=DAGUBOwPBJs&utm_campaign=designshare&utm_medium=link&utm_source=editor
