# Kickstarting with Excel

## Overview of Project

### Purpose
Louise’s play was very close to reaching its goal in a short amount of time, so the purpose of this analysis is to find the relation between launch dates and funding goals of various Kickstarter. To accomplish this, I will make two graphs that show different types of data to get a better picture. One graph will show the outcomes based on the launch date. The other graph will show were the outcomes based on the goals. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To have a proper analysis of the outcomes based on launch date I used the pivot table along with a line chart. The data that will be used will be taken from the outcomes, years, category, and launch date columns.  Some of the columns use data that are changed due to formulas. For example, the year's column uses the Year formula to grab information from the launch date columns.  The pivot table can be filtered by category and years. The category filter focuses on theaters only with successes as the start. I then make a line chart, so that I can visualize the numbers. 

![Theater Outcomes vs Launch](https://github.com/Robeliom15/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)
### Analysis of Outcomes Based on Goals
For the analysis of the outcomes based on goals, I needed to use two formulas to get the data I needed. To get the data for the number failed, canceled, and successful based on the goal and outcome I used the Countifs formula. Once I get that data, I added all the rows then divided them to get a percentage of the outcomes and goals. Once I get all my data, I then make a line chart so I can visualize the data. 

![Outcome VS Goals](https://github.com/Robeliom15/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)
### Challenges and Difficulties Encountered
Setting up the data for the charts was difficult for the most part, but I did have one major problem. When making the pivot table/chart for the theater outcomes by launch date I found that the data in the pivot table and line chart did not look right. Looking over the original data in the Kickstarter sheet I could not find any errors in the data I had. To fix it I had to use the month formula to get the data from the date-created conversion and convert them to the month. I found when I made the pivot table and line chart with this data the problem was fixed. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The difference between outcomes of the theater type Kickstarter is vastly different from each other. When looking at the successful Kickstarter you see a gradual rise in the amount toward the spring. Additionally, the successes peak in May and start to decline. The failed Kickstarter has a much steadier line and only peaks during May and two other months with similar numbers. There are much fewer canceled Kickstarter, and peaks in January. Other than the peak the amount of canceled Kickstarter stays consistent throughout the year. 
- What can you conclude about the Outcomes based on Goals?

The first thing I noticed was that the canceled plays were at zero, so I did not have to focus on it at all. The second thing I noticed was that the number failed and number successful mirror each other on the line chart. The line chart also shows that the cheaper the goal is the more likely it will be successful. 
- What are some limitations of this dataset?

For some of the line chart, we used I don’t think we had enough data to get a better idea of the bigger picture. For example, the outcomes based on the goals pivot table have been sorted by their goal. I don’t think we had enough of the higher-end kick-starters to truly understand the difference. One other difference I how the data was obtained. 
- What are some other possible tables and/or graphs that we could create?

A box plot would be a good addition since we can spot potential outliers in the data. Additionally, we would have some additional data that can give us a better understanding overall.
