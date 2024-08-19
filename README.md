Case study: How does a bike-share navigate speedy success?

Introduction

Hi, this is a case study from google course in Data Analytics Professional Certificate. However, this case study will be focus on the year 2020.
The purpose of this case study is to understand how casual riders and annual members use Cyclistic bikes differently, in order to design a new marketing strategy
to convert casual riders into annual members.

Data

The data I used is Cyclistic’s historical trip data, specifically the year 2020 to analyze and identify trends. (https://divvy-tripdata.s3.amazonaws.com/index.html)
The data has been made available by Motivate International Inc. under this license (https://divvybikes.com/data-license-agreement).
The raw data has been cleaned and the cleaning process include deleting a row with a few missing values. After cleaning, a thorough analysis has been done to understand
and identify the overall data. The formula used to calculate the length of each ride by subtracting the column started_at from the column ended_at, and format as time.
The column day_of_week is created by calculating the day of the week that each ride started using the WEEKDAY command and format as General or as a number with no decimals,
noting that 1 = Sunday and 7 = Saturday. Then proceed to create a pivot table to quickly calculate and visualize the data.

Dashboard and Conclusion

Visualization chart, graph and heatmap of the data is done on Tableau and combine in one dashboard to tell the story from the analyzed data.
The result that I conclude from the dashboard is that Tuesday, Wednesday, and Thursday have the highest number of bike trips (highlighting the annual members), peaking
mid-week. While, Saturday and Sunday are in lower usage for annual members, but higher for casual riders which suggests that weekdays are more popular for bike sharing,
possibly due to work commutes. Whilst, the weekends are popular for casual riders, possibly due to the general public using bike-sharing on their day off. Other than that,
most bike trips are short, with the majority lasting between 1 to 10 minutes. There’s a rapid decline in the number of rides as duration increases, indicating that bikes
are primarily used for short-distance travel. The heatmaps also indicate a high concentration of rides in specific urban areas, particularly around central locations.
This suggests that these areas are key hubs for bike-sharing.

Data-Driven Decisions

Increase Bike Availability during mid-week, especially in high-demand areas. Given the short ride durations, ensuring that bikes are well-distributed in central,
high-traffic areas can optimize usage. Expand Bike Stations in the hotspots identified by the heatmaps to better serve high-demand areas and reduce bike shortages during
peak times. Offering special membership discounts or trial periods on weekends when casual riders are most active and emphasizing the savings they would get by becoming
members, especially for regular weekend riders. Use data from ride patterns to create targeted marketing campaigns that focus on casual users who frequently ride on
weekends, encouraging them to convert to membership.

