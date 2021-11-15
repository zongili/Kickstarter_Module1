# Kickstarting with Excel
### Folder: HuliaCarletonUModule1
## Overview of Project
###This project allows you to test your Excel skills that is covered in Module 1. You will use your database and complement it with pivot tables and graphs to create visualizations. Visualizations will allow you to understand your data clearly and uncover trends. 


## Purpose
###The purpose of this project is to visualize how different campaigns fared in relation to their launch dates and funding goals. 

## Analysis and Challenges
###Analysed campaign outcomes based on their launch dates using pivot tables and charts.First created the goal column for the launch dates worksheet. Used countifs built in function for each row of the goal column with different goal ranges. I calculated it for for 3 different outcomes.This was a bit of work as seen in the picture. 

![This is my image](resources/Theater_Outcomes_vs_Launch_Calculations.png)
According to the analysis outcomes were most successful in May as seen in the chart below.
![This is my image](resources/Theater_Outcomes_vs_Launch.png)

Analysed campaign outcomes based on their their funding goals using pivot tables and charts.Pivot table uses auto sorting. I needed to keep the text in the same order as it was in Goal column. Because the text was consisting of digits and letters the sorting messed up my table, less then 1000 being the last in the column as opposed to being the first. I got rid off the auto sorting option and moved cells around as seen in the picture.
![This is my image](resources/Outcomes_BasedOnGoals_Sorting.png)

According to the analysis success and failureare mirrored, an interesting result as seen in the chart below. With increased goal the success rate goes down from 80% to 20% at the goal level 30000. With increased goal the failure rate goes up from 24 to 80% at goal level 30000. 
![This is my image](resources/Outcomes_vs_Goals.png)

## 3. Results

###-  What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Outcomes were most successfull in May, exceding 100%. Summer months give the most successful results in May - August 71-111%. Success rate declines from September to Dec and Jan to April.February also shows a 71% success spike in winter.

2. General failure rate is around 50% in the summer with the exception 50% failure in October. Other months around from Jan-April 31%-40% and Sept, Nov-Dec failure is 31-35% 

-  What can you conclude about the Outcomes based on Goals?
They are mirrored, success and failure. With increased goal the success rate goes down from 80% to 20% at the goal level 30000. From goal level 35000 to 45000 the success rate goes up to 70%. After from 45000+ goal level success rate ranges between to 0-18%

With increased goal the failure rate goes up from 24 to 80% at goal level 30000. From goal level 30000 to 45000 the failure rate goes down to 33%. From goal level 45000 to 5000 the failure rate reaches to 100%. After from goal level 50000+ failure rate ranges between to 83-100%. 

If we want to be failure level to be between 20-40% the goal should not be more than 10000 or to take the chance for the 33% failure rate and set a goal for 40-45 thousand.

Adding pictures or links to readme.md was another challenge for this project. I used [How to Put Images in Readme files for GitHub Repos](https://www.youtube.com/watch?v=EOKOFHtXz4g/) to learn it.

-  What are some limitations of this dataset? 
it limists it to goal only. We need to take into consideration the launch time and pledged amounth as well to get a better picture of success/failure rate.

-  What are some other possible tables and/or graphs that we could create?
We could use categories and subcategories in order to focus our analysis on an area (theater/film/plays etc.) and its goal and pledges. We could also draw chart/table based on goal for different counties.

