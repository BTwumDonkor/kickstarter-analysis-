# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this progect was to explore how different campaings, "for which this project focused on plays campaign", performed with respect to their launch dates and their funding goals using the Kickstarter dataset.This was achieved by developing charts which better paints the picture of plays campaing outcome with respect their launch dates and their funding goals.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
:Inserts screenshot of Theatre Outcomes based on Launch Date
A pivot tabel was created from the Kickstater dataset where Years and Parent Category were placed at Filters, outcomes at Legend(Columns) and Values and Date Created Conversion at Axis (Rows). Theater was the filter for Parent Category and the Column Labels filtered out live columnn.

### Analysis of Outcomes Based on Goals
:Inserts screenshot of Theatre Outcomes based on Launch Date
A table was created which sort to count the number and percentage of outcomes ( successful, failed and canceled) for the different ranges of goals proposed within the plays. The COUNTIFS formula was applied to populate the outcomeds given the goal ranges for the play campaign.

### Challenges and Difficulties Encountered
The were no challenges encountered however, a possible challenge could be the conversion of the date from the unix format to actual dates format and the correct application of the COUNTIFS formula to attain the desired results.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. More successful play campaigns for the months from April, peaked in May and begins to drop in numbers from there till the end of the year.
2. Very few canceled play campaigns accros the year with none canceled for the month of October

- What can you conclude about the Outcomes based on Goals?
1. Zero canceled plays based on goal outcomes for the entire plays campaign.

- What are some limitations of this dataset?
1. Launch dates and Deadlines are presented in unix code format and outliers exist with the goal column.

- What are some other possible tables and/or graphs that we could create?
1. We could create a bar chart to present the analysis results as well.
