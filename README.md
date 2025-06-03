# HR Employee Performance Tracker (Interactive Dashboard using Power Bi)
Description: This project involves analyzing employee attendance patterns from April to June using a real-world HR dataset. It focuses on understanding work preferences (Work from Home vs. Office), reasons behind these preferences, sick leave patterns and frequency, and overall attendance trends over time.  The implementation included extensive data cleaning and transformation using Power Query Editor, DAX calculations for various metrics, and data visualization in Power BI. 

## Objective:

To analyze employee attendance patterns from April to June using a real-world HR dataset. 
To understand work preferences (Work from Home vs. Office) and the reasons behind those preferences. 
To analyze sick leave patterns and their frequency. 
To identify trends in employee attendance over time. 

## Dataset 
- <a href="https://github.com/deshpandeshefali/Data-Analysis-Dashboard/blob/main/Attendance%20Sheet%202022-2023_Masked.xlsx">Dataset</a>

## Questions Answered (Implicitly, through analysis and insights):

1. What is the percentage of employee presence (including WFH and Half-WFH)? 
2. What is the percentage of sick leave taken by employees? 
3. What is the percentage of Work from Home instances? 
4. How do these percentages (presence, sick leave, WFH) trend over time (daily and monthly)? 
5. Are there specific periods with higher sick leave or WFH percentages? 
6. How do work preferences compare between Work from Home and office setups? 

## Dashboard
- <a href="https://github.com/deshpandeshefali/Data-Analysis-Dashboard/blob/main/final.png">View Dashboard</a>

## Process 

Data Cleaning and Transformation: Imported, filtered, cleaned, and unpivoted attendance data for April, May, and June.
Query Optimization & Reusability: Created a parameterized Power Query function (GetData) to automate imports and handled errors.
Data Modeling: Created a Measure Table and calculated Total Working Days, Presence Days (including WFH/Half-WFH), Presence %, and Sick Leave % using DAX.
Visualizations: Built card visuals (Presence %, Sick Leave %, WFH %), detailed attendance tables, line charts for trends (Presence, WFH, Sick Leave % by Date), and daily tables.

## Insights 

• Employees showed a strong preference for Work from Home over traditional office 
setups.
• A noticeable percentage of employees took sick leaves, especially during specific 
periods—highlighting potential wellness or seasonal trends.
• Presence rates improved towards the end of the quarter, possibly due to company 
policies or better health awareness.
• Trends helped in identifying low-engagement days and potential scheduling 
inefficiencies.

## Conclusion

This Power BI project provided clear insights into employee attendance patterns and work preferences from April to June. It revealed a strong inclination towards remote work, highlighted trends in sick leaves, and showed improved presence rates over time. The project showcased end-to-end BI skills—data cleaning, modeling, DAX, and interactive dashboards—offering a strong foundation for future HR analytics and automation.


