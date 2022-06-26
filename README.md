# Rafajos_excel
# kickstarter-analysis
challenge week one
---
*module 1*
---

**1.	Overview of Project: Explain the purpose of this analysis.**

The purpose of this analysis is to determine which projects are most feasible and what is the right time to start them based on the evaluation of percentage of successful and failed campaigns in relation to goals in a prescribed amount of time

**2.Analysis and Challenges:**

Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.

Delivery 1:

The first step was to classify the “Outcomes” column with different colors based on the campaign status, and then split or delimited the category and subcategory in two columns one for “Parents Category” and the another for “Subcategory” using the “text to columns”.
The second step used the information from the column “Launched_at” to extract the launch date and subsequently I  used the function YEAR() to obtain the year for each campaign and created a new column just for the year.
Next, creation of the pivot table required using all the data, filtered by “Parent Category” and “Years”.  The rows in the pivot table take the date converted from the “Launched_at” and columns use “Outcomes”, for the values is defined for count of outcomes.
I grouped the date by months to reflect them in the rows and filtered the columns labels to show only successful, failed, and canceled campaigns.
The final step filtered the parent category column by “Theater” to obtain the final data in order to create the chart graph.  Subsequently I created the “Theater Outcomes Based on Launch Date” graph chart to visualize the results and saved it in a resources folder like Theater_Outcomes_vs_Launch.png.

####Delivery 2:####
---
First, I created a new work sheet, with eight columns (goal, number successful, number failed, number canceled, total project, percentage successful, percentage failed, percentage canceled.) The goals are defined between “less 1000” to “50000 or more”.
Next, to extract the information for fill the columns “Number Successful”, “Number Failed” and “Number Canceled” I used the function COUNTIFS to defined  all conditions,
To “Total Projects” I used the function SUM() and for the percent I divided the number successful, failed and canceled with the total projects and multiply by 100 and added the function ROUND() to show only 2 digits.  
Using the final table to create the chart line “Outcomes Based on Goals” to show the results goals vs percentages, then saved it as “Outcomes_vs_Goals” in the recurses folder.
The biggest challenge for me was to write the analysis use the GitHub. 

###3.Results:###
---
Answer the following questions in complete and coherent sentences.

####o	What are two conclusions you can draw about the Theater Outcomes by Launch Date?####
---
The first conclusion reveals the most important months to launch campaigns, specifically May being the month with the highest number of campaigns, as well as successful campaigns and failed campaigns, followed in second place by June.  These two months are the best option if the company decides to launch campaigns. 
The second conclusion reveals that December as the worst month to launch campaigns.  In December 36 successful campaigns and 35 failed campaigns make this month the worst option for launching campaigns.

####o	What can you conclude about the Outcomes based on Goals?####
---
The projects with a goal up to 9999 are most successful and register the highest number of projects, and the projects with a goal between 25000 to 34999 are more likely to fail. Projects with a goal of 45000 to 49999 have the highest percentile to fail because in the last years the company didn’t register information about them or don’t start projects with this goal. 

####o	What are some limitations of this dataset?####
---
The possible limitations are about the dataset is it needs to be converted and delimited or split into columns if you want to analyze this information, which may cause errors and miss portions of data. 

####o	What are some other possible tables and/or graphs that we could create?####
---
We can create graphs about the different parent category and subcategory, in relation to the date, filter in a determine lapse of time or group it by months. Other options could sort by a country or specific year to show the result and select a specific kind of money denomination would be another option to create a graph. Also the data could be graphed separately for successful, failed or canceled campaigns. 


