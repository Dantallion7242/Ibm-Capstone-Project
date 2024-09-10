# Ibm-Capstone-Project
IBM Capstone Project: Google Looker Studio Dashboard
Project Overview
This capstone project involves creating an interactive dashboard using Google Looker Studio with data from two provided CSV files: m5_survey_data_demographics.csv and m5_survey_data_technologies_normalised.csv. The project aims to visualize current technology usage, future technology trends, and respondent demographics using various types of graphs and charts.

Files Required
m5_survey_data_demographics.csv – Contains demographic data about respondents.
m5_survey_data_technologies_normalised.csv – Contains data about technologies respondents have worked with or desire to work with in the future.
Steps to Upload CSV Files
Download both CSV files.
Upload these files as data assets to your Google Looker Studio account to create the visualizations.
Dashboard Structure
The dashboard consists of 3 pages with different visualization themes:

Current Technology Usage
Future Technology Trend
Demographics
Each page will contain 4 graphs, making use of different chart types and data filters.

Page 1: Current Technology Usage
Template: 2 x 2 Rectangle Areas (Tabbed)
Data Source: m5_survey_data_technologies_normalised.csv
Graphs:
Top 10 LanguageWorkedWith (Stacked Bar Chart):
Metrics: Top 10 programming languages.
Utilize Dimension, Breakdown Dimension, Metric, and Color fields.
Features: Show data labels, include proper chart title.
Top 10 DatabaseWorkedWith (Stacked Column Chart):
Metrics: Top 10 databases.
Utilize Dimension, Breakdown Dimension, Metric, and Color fields.
Features: Show data labels, include proper chart title.
PlatformWorkedWith (Word Cloud Chart):
Metrics: Platforms used.
Utilize Dimension and Metric fields.
Features: Include a proper chart title.
Top 10 WebFrameWorkedWith (Scatter Bubble Chart):
Metrics: Web frameworks.
Utilize Metric X, Metric Y, Bubbles Size, and Bubble Color fields.
Features: Include a proper chart title.
Page 2: Future Technology Trend
Template: 2 x 2 Rectangle Areas (Tabbed)
Data Source: m5_survey_data_technologies_normalised.csv
Graphs:
Top 10 LanguageDesireNextYear (Stacked Bar Chart):
Metrics: Top 10 programming languages respondents desire to work with next year.
Utilize Dimension, Breakdown Dimension, Metric, and Color fields.
Features: Show data labels, include proper chart title.
Top 10 DatabaseDesireNextYear (Stacked Column Chart):
Metrics: Top 10 databases respondents desire to work with next year.
Utilize Dimension, Breakdown Dimension, Metric, and Color fields.
Features: Show data labels, include proper chart title.
PlatformDesireNextYear (Tree Map Chart):
Metrics: Desired platforms next year.
Utilize Dimension and Metric fields.
Features: Include Show Scale feature, proper chart title.
Top 10 WebFrameDesireNextYear (Scatter Bubble Chart):
Metrics: Desired web frameworks next year.
Utilize Metric X, Metric Y, Bubbles Size, and Bubble Color fields.
Features: Include a proper chart title.
Page 3: Demographics
Template: 2 x 2 Rectangle Areas (Tabbed)
Data Source: m5_survey_data_demographics.csv
Graphs:
Respondent Classified by Gender (Pie Chart):
Metrics: Gender classification of respondents.
Utilize Dimension and Metric fields.
Features: Show Slice Label, include proper chart title.
Respondent Count for Countries (Filled Map Chart):
Metrics: Respondent count by country.
Utilize Location and Color metric fields.
Features: Include proper chart title.
Respondent Count by Age (Line Chart):
Metrics: Respondent age groups.
Utilize Dimension and Metric fields.
Features: Show data labels, include proper chart title.
Respondent Count by Gender & Formal Education (Stacked Bar Chart):
Metrics: Gender classified by education level.
Utilize Dimension, Breakdown Dimension, Metric, and Color fields.
Features: Show data labels, include proper chart title.
Filters and Data Cleanup
Each page includes filters to remove null values and irrelevant data (e.g., filtering Gender to only show "Man" and "Woman" on the Demographics page). Use the "Add Quick Filter" option in Google Looker Studio to ensure that only valid data is displayed in each graph.
