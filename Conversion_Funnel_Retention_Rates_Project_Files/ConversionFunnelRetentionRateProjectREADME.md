# File Title: conversion.funnel.retention.rates.project_v1.6_2024.08.28

This was the business analysis module project in the TripleTen Business Intelligence Analysis program. The project was the second one done in Google Sheets to expand my skills working with spreadsheets and it also applied business analytics skills including calculating conversion and retention rates.

[<img src="Conversion_Funnel_Retention_Rates_Project_Files/ConversionFunnelRetentionRatesProject.png" alt="First Page of Project">](https://docs.google.com/spreadsheets/d/1ylkhNU3wNnf1mYEA9I-wngYnJjapI0_dXW0JpJ0Qrlk/edit?gid=868644233#gid=868644233)


Project's Google Sheets workbook can be found <a href='https://docs.google.com/spreadsheets/d/1ylkhNU3wNnf1mYEA9I-wngYnJjapI0_dXW0JpJ0Qrlk/edit?gid=868644233#gid=868644233'><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | README.md | This current page with all relevant information about the project. |
| 2 | [Business Analytics Project Instructions](https://github.com/JillianKingsley/data_projects_TripleTen/blob/940b4878af1efd53349e3f28c815eddb80648035/Conversion_Funnel_Retention_Rates_Project_Files/BusinessAnalyticsProjectInstructions.docx) | A .docx file with the provided project instructions from TripleTen. |
| 3 | [raw_user_activity.csv](https://github.com/JillianKingsley/data_projects_TripleTen/blob/c558c8b4db8b871041e4b27d605639a8ff496cec/Conversion_Funnel_Retention_Rates_Project_Files/Business%20Analytics%20Project%20-%20raw_user_activity.csv) | The original data file provided by TripleTen that was used in the analysis of this project. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions added by me in the course of my analysis. |
| Process | A general outline of how this project was completed. |
| Findings | Insights learned from the data analysis. |
| Reviewer’s Comments | Project reviewer’s comments on the project. |

### Data
The data was one Google spreadsheet file provided by TripleTen:
- `'raw_user_activity.csv'`: each row corresponds to one user id and event logged on the client's website
    - `'Table of Contents'`: a template for a color-coded table of contents
    - `'Executive Summary'`: a template for an executive summary page

### Description:
- 9 page workbook
- Includes raw data (protected), processed data, data analysis, and pivot tables.

### Assumptions:
- Counting unique users at each stage of the funnel (instead of counting actions) will provide an accurate measure of conversion rates.
- That no significant external factors are influencing user behavior across different cohorts.	
- That users follow a logical progression from viewing a product, to adding it to their shopping cart, and then to making a purchase.
- That retention rates are a key indicator of customer loyalty and that lower retention reflects less customer satisfaction or engagement.
- That the cohorts are large enough for the retention rates to be statistically significant.
- That the missing data from the February 2021 cohort does not substantially impact the validity of the overall results.

### Process:
I first created a pivot table to create a conversion funnel and calculate conversion rates.
Next I created the "purchase_activity" sheet for my cleaned and processed data.
I then created more pivot tables to analyze the data further.
I documented all changes to the workbook and created a table of contents and an executive summary for ease of use by the client.
Lastly, I finalized formatting for the client's readability.

### Findings:
1. The total conversion rate from customers viewing products to adding them to their shopping carts was 29.04%.			
2. The conversion rate from adding items to a shopping cart to purchasing the items was 35.61%. 	
3. The total conversion rate from viewing to purchasing products was 10.34%.			
4. Retention rates are low for all cohorts with the highest percentage of returning customers being 12.5% for the September, 2020 cohort in the month following their initial purchase. 
5. The second highest retention rate was that of the October, 2020 cohort at 7.49%.

### Reviewer’s Comments:
“Hello, Jillian! Glad to see you 😊

My name is Dmitry and I will perform a review of your project.
Your Excel is beautifully designed, you answered the questions of the terms of reference in a great way. You once again did a very good job and I see your skills in analytics! I note that Excel is one of the most basic analytics tools, and it is very important to be able to use it.
In the "Executive Summary", you described both the stages of the funnel very well and also in the conclusions, you noted the low user retention perfectly.
Thank you for your work and I wish you success in your next projects!) 😊

Dmitry Mikhalenko”
