# Kickstarter-Analysis
## Module 1 Challenge
### Overview of Project
###### Throughout the course of a year, Louise’s play "Fever", came close to it's fundraising goal. The purpose of this analysis was to see reults containing, outcomes based on launch date and the outcomes based on goals.
---
### Analysis and Challenges
#### Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/114371722/198755816-1bc4d225-4e13-4d1d-bcec-aaa91542a8f8.png)
###### For Outcomes Based on Launch Date, I added a "Years" and "Date Created Conversion" column to my Kick Starters Challenge sheet. From there I created a pivot table using "Parent Category" and "Years" in the filters, "outcomes" in the columns, "date created conversion" in the rows, and "outcomes" in the values, which became "count of outcomes". From the data in the pivot table, I was able to make a line chart to display the results. 
###### The only issues that were encountered in this deliverable, was making sure I used the categories in the correct areas on the pivot table, which took a couple tries.   
---
#### Outcomes Based on Goals 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/114371722/198755934-6c516762-b7ac-4da4-b2c7-b2a6ffe19c93.png)
###### For Outcomes Based on Goals, I added a new excel sheet and created a "goals" category, followed by rows starting at less than 1000, ending with no more than 50000, and 10 other ranges in between. From there, I added eight more categories which were number successful, number failed, number canceled, total projects, percentage successful, percentage failed, and percentage canceled. To find all the goal numbers, "=COUNTIF" was used for the outcomes, goals, and subcategory columns, and then I was able to add another criteria to get the different ranges. The =SUM formula was used for the "total projects" and also used to divide finding "percentage successful" and "percentage failed". "Percentage Cancelled" had zero results in the outcome.
###### The biggest struggle I had with this deliverable, was using the =COUNTIF function. I couldnt seem to find the right formula to make everything work and received alot of error pop ups. 
---
### Results
#### Outcomes Based on Launch Date
###### From January through December, there was a total of 1,369 plays and over 800 plays were successful. The total number plays that failed was slightly under 500. From September to November, there were no cancellations.
#### Outcomes Based on Goals
######

