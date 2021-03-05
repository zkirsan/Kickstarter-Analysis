# Kickstarting with Excel
 
An Analysis of Kickstarter Campaigns

## Overview of Project

The goal of the project is to support Louise, who wants to start a crowdfunding business to help fund her play, Fever.
She expects a target of over $10,000 and is reasonably cautious about launching into her fundraising event. 

### Purpose

The purpose of this project is to use Excel to organise, filter and evaluate data on crowdfunding to decide 
if there are unique variables that make the project's campaign a success. As if to use these insights to help 
Louise navigate her own way and set her up for future success. Utilizing excel to evaluate existing site data to 
help it achieve a deeper view of campaigns from beginning to end. In other words, its goal can be set by its initiative 
to mimic other popular ones in the same classification.

## Analysis and Challenges

Performing analysis on Kickstarter data aims to uncover any hidden trends. These analyses are;

 1. the Theater Outcomes by Launch Date
 2. the Outcomes Based on Goals
 3. Edinburg Research

First, the Theater Outcomes by Launch Date comprises the pivot table, which is including the count of outcomes per month, 
and the number of successful, cancelled, and failed. 


Second, the Outcomes Based on Goals consists of a dollar-amount range, the number of successful, failed and cancelled, 
the sum of total projects, and finally, their percentages.
Using the function of COUNTIFS() populated the number of successful, failed and cancelled. Then, with the SUM() function 
got the number of total projects. 

### Analysis of Outcomes Based on Launch Date

The pivot table, which is the line graph of Theater Outcomes Based on Launch Date shows that the month that launched the most successful Kickstarter campaign 
was May in the category of theatre. However, May, June, July, and October all had roughly the same number of failed campaigns launched. Further, there were not be any
cancelled projects between September and November. 

### Analysis of Outcomes Based on Goals

The line graph shows that the percentage of the outcomes based on goals. For example, in case of the Theater filtered,there was a decrease in the percentage of successful projects 
between less than $1000 and $29999 by around 55%. However, it was increasing suddenly after the amount of $25000 to $29999 up to the range of $35000 to $39999 then it reached by 0% abruptly at the point of $45000 to $49999. 
<p align="center"><img src="https://github.com/zkirsan/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png"></img></p>
In opposite to that, the percentage of failed reached 100%. It is clear that there was an asymmetrical relationship between the successful and failed numbers. 
Finally, there were not any outcomes for the percentage of cancelled projects. 
<p align="center"><img src="https://github.com/zkirsan/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true"></img></p>


### Challenges and Difficulties Encountered

I think the biggest challenge is all the analyses made from the given data set, however, it did not consist of any information 
about the consumers or attendees. Making some predictions for fundraising needs more data about the consumers or attendees to predict more clearly to 
uncover any hidden trends. 


## Results

To sum up, according to the Theater Outcomes Based on Launch Date, the percentage of successful projects has seasonal changes in a year. That's why to investigate better the project
that needs more data about the attendees. Also, there was a steady percentage for cancelled projects. 
According to the Outcomes based on Goals, It is obvious that there has been an asymmetrical interaction between successful and failed figures.
In terms of more descriptive analysis that the dataset needs more specific information about the participants. For example, we do not have any information about people 
who were interested in the fundraising and their profiles. 
Finally, according to given data, it could have seen some other possible tables and/or graphs, which are the Parent Category Outcomes, the Subcategory Outcomes, the Outcomes based on Lauch Date, and a specific country research. 


