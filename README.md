# Kickstarter Analysis - Berkeley DA
Yae Jin Park
Module 1: Kickstarting with Excel

## Project Overview
### Purpose
As becoming familiar with Excel is the first step to become a successful data analyst, this project's purpose is exactly that - do an analysis on a given set of kickstarter projects data with what I was taught over the past week. I was provided with a set of data regarding the status of multiple kickstarter projects in a varying categories of entertainment and my goal is to target and extract certain parts of the data to analyze with tools in Excel (mainly the pivot chart, line graphs and basic statistics functions in Excel).

The first analysis was done on 'theater' category of the kickstarter projects using the pivot chart and a line graph.
During this analysis, I demonstrated how I can utilize the rows, columns, values, and filters on a pivot chart in order to produce a more human-friendly analysis chart to deduce a conclusion for theater kickstarter projects based on their launch dates.

The second analysis was done on the outcomes of the 'play' category of the kickstarter projects by using the COUNTIF() function in Excel and a line graph.
For this demonstration, I counted projects that were successful, have failed, or have been cancelled with the mentioned function and compared their percentages and displayed them on a line chart.

## Analysis and Challenges
### Analysis and Challenges on Outcomes Based on Launch Date
With the pivot table, I rearranged the data to show the success/fail/cancel rates for each month of all years in the dataset. Looking at the 'Grand Total' column on the far right, which counts all projects regardless of their status in the same month for all years, I was able to check that all months had no alarming outliers (e.g. there was no month that had 5000 theater projects when other months had somewhere around 70-160). However, with just numerical values, it was difficult to visualize what exactly is going on and so a line graph was produced based on the statuses of the projects for each month of all years.

![Theater_Outcomes_vs_Launch](./resources/Theater_Outcomes_vs_Launch.png)