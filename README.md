# Kickstarting with Excel

## Overview of Project
The challenge assignment for module 1 focused on building skills related to managing and analyzing data sets using pivot tables, charts, 
and graphical representations. There are two specific analysis to be created from the available data for theatrical activities;
one based on the funds raised goal; one based on launch date. 


### Purpose
The purpose of the two analyses was to determine how different theatrical campaigns performed based on the funds raised and the launch dates. 
This report will detail the findings of each outcome, provide a graphical representation of each outcome, outline the difficulties experienced
(or difficulties one could experience), and the final conclusions based on the analyses.  



## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For this analysis, a pivot table was created filtering on the parent category "theater" and all years.  The columns consisted of the outcomes 
"successful", "failed", and canceled; "live" was excluded.  The row labels consisted of the months each theatrical activity was launch.  Once the 
pivot table was completed, a line chart was created in order to easily visualize the results of the analysis.   

Based on the chart below, May was the peak of successful theater launches during the twelve months with almost an appearance of a normal distribution.  
The failed launches were more consistent throughout the year, although a little higher in the summer months.  There were dips in May and September then a 
spike in October.  Canceled outcomes were the largest in January and then were primarily flat.  There were additional dips in July and October as well. 
![Theater_Outcomes_vs_Launch](https://github.com/dandschevy/Kickstarter_analysis_module1/blob/main/resources/Theater_Outcomes_vs_Launch..png?raw=true)


### Analysis of Outcomes Based on Goals
For this analysis, a chart was created based on the goal amount and then calculating a percentage based on the number of successes, failures and cancelations for just the subcategory of plays.  As indicated in the chart below, percent of failures was great in the $25,000 to $29,999 range and greatest in the $45,000 to $49,999 range.  the lowest percentage of failures occurred at the $0 to $1,000 range and $35,000 to $45,000 range.  Conversely, the percent of successful outcomes was highest in the $0 to $1,000 range, dipping in the $25,000 to $29,000 range, rising in the $35,000 to $45,000 range, and falling in the $45,000 to $49,000 range.  

![Outcomes_vs_Goals](https://github.com/dandschevy/Kickstarter_analysis_module1/blob/main/resources/Outcomes_vs_Goals.png?raw=true)


### Challenges and Difficulties Encountered
While there were no challenges faced during the analysis, there could have been a challenge in being able to list the data by month for the Outcomes Based on Launch Date pivot table and graph in it was not remembered how to filter to get this data.  Additionally, if one was not reading the instructions carefully for the Outcomes Based on Goals challenge, additional subcategories could have been mistakenly included instead of filtering by plays.

## Results

### Outcomes Based on Launch Date
Two conclusions can be drawn based on the analysis. The first conclusion is that launch date does have an impact on the number of successful campaigns.  May and June theatrical releases have a higher number of successes as compared to other months.  The second conclusion is that cancellations are not necessarily dependent on the month, with the exception of January.  


### Outcomes Based on Goals
For this analysis, the conclusion that can be drawn is that plays with high goals, $45,000 to $49,999, have a greater chance at failing than those with smaller goals.


### Additional Analyis or Data Points
One addional data point that could have been included in the Outcomes Based on Launch Date is the percent of successes, failures, and cancelations to the total each month.  This could have provided a better representation of the data due to removing the fact that there were more theatrical activities in May and June (using ratios rather than pure numbers).  


