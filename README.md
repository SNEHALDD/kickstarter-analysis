# Kickstarting with Excel

## Overview of Project

This dataset contains information about multiple fundraising campaigns.This project is to understand how different campaigns fared in relation to their launch dates and their funding goals

I need to work on two analysis - 1) Outcomes based on goals and 2)outcomes based on launch date. Also, create line chart of those. Then I am supposed to submit the written report.



### Purpose

The purpose of this project is how to analyze and sort data from larger dataset using excel. This also improves excel usage capabilities.



## Analysis and Challenges

Deliverable 1: Outcomes Based on Launch Date Chart
* Excel functions used - Unix date converter, Year(),Pivot tables, Pivot Charts
Deliverable 2: Outcomes Based on Goals Chart - 
* Excel functions used - Unix date converter, Countifs(),sum(), Percent format, Pivot tables, Pivot Charts



### Analysis of Outcomes Based on Launch Date

* In the Kickstarter_Challenge.xlsx workbook, created a new column labeled "Years."
* In the "Years" column, I used the YEAR() function to extract the year from the “Date Created Conversion” column.
* I created the pivot table considering Patent category and Years in filters. 
* Filtered the pivot table based on "Parent Category" and "Years."
* Placed the appropriate pivot table fields in the columns, rows, and values.
* Filtered the column labels to show only "successful," "failed," and "canceled."
* Filtered the "Parent Category" to show only the data for "theater."
* Created line chart to observe distribution of outcomes (successful, failed, canceled)over different months, saved in "resources" folder.



### Analysis of Outcomes Based on Goals

* In the KickStarter sheet, created a new sheet and labeled it "Outcomes Based on Goals."
* In the new sheet, created these columns to hold the data: Goal, Number Successful, Number Failed, Number Canceled, Total, Projects, Percentage Successful, Percentage Failed, Percentage Canceled.
* In the “Goal” column, created the dollar-amount ranges so projects can be grouped based on their goal amount.
* Used COUNTIFS() functions to populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column using the ranges created in Step 3, and on the "Subcategory" column using "plays" as the criteria.
* Used the SUM() function to populate the "Total Projects" column with the number of successful, failed, and canceled projects for each row.
* Calculated the percentage of successful, failed, and canceled projects for each row.
* Created a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.
*Saved the Line chart in "resources" folder



### Challenges and Difficulties Encountered

* Faced difficulties while working on "Analysis of Outcomes Based on Goals", since I was making some silly mistakes when selecting sheet and some typo
* difficulties during typing the correct formula 




## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

* The success rate is more in April, May and June timeframe. 
* The failure rate is more in October.



- What can you conclude about the Outcomes based on Goals?
* Percent successful tends to be more when the Goal is less than 1000 and between 35,000 to 40,000.
* Percentage failed is highest at 45,000 and more.



- What are some limitations of this dataset?
* Limited dataset to come up with any solid conclusion.



- What are some other possible tables and/or graphs that we could create?
* We can create individual graphs for each campaign to get more clarity about their success over the year.
