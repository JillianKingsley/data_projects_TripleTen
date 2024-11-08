﻿# File Title: superstore.returns.project_v1.6_2024.08.28

This was the first Tableau project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned about Tableau. This project is about analyzing order and return data to help a client decide what products and product sub-categories to discontinue and invest in, what areas to advertise in and how much to spend there, and better understand returns.

[<img src="https://github.com/JillianKingsley/data_projects_TripleTen/blob/ffa6646507b2c00c9956aff0d5ac4dd47316bd12/Superstore_Returns_Project_Files/ProfitsAndLossesDashboard.png" alt="Profits and Losses Dashboard">](https://public.tableau.com/views/SuperstoreReturnsProject_17246215020830/ProfitsLosses?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


The project's Tableau workbook can be found <a href='https://public.tableau.com/views/SuperstoreReturnsProject_17246215020830/AverageProfitAverageReturnRate?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link'><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | Whole Project README | This page with all the pertinent project information.
| 2 | [Superstore Findings and Recommendations README](https://github.com/JillianKingsley/data_projects_TripleTen/blob/ffa6646507b2c00c9956aff0d5ac4dd47316bd12/Superstore_Returns_Project_Files/SuperstoreReturnsREADME.md) | Explanation of my findings and recommendations with a link to the Tableau Public workbook. |
| 3 | [Data Visualizations Rubric](https://github.com/JillianKingsley/data_projects_TripleTen/blob/ffa6646507b2c00c9956aff0d5ac4dd47316bd12/Superstore_Returns_Project_Files/Data_Visualization_Rubric.pdf) | A .pdf file with the provided data visualizations rubric from TripleTen. |
| 4 | [superstore.xls](https://github.com/JillianKingsley/data_projects_TripleTen/blob/ffa6646507b2c00c9956aff0d5ac4dd47316bd12/Superstore_Returns_Project_Files/Superstore%20(1).xls) | The original data file provided by TripleTen that was used in the analysis of this project. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Process | A general outline of how this project was completed. |
| Findings | Insights learned from the data analysis. |
| Reviewer’s Comments | Project reviewer’s comments on the project. |

### Data
The data was one Excel file provided by TripleTen:
- `'superstore.xls'`: Excel workbook with information on the orders, regional managers, and returns for Superstore.
    - `'orders'`: list of unique orders which includes string information like customer and product names, geographic information like customer address, and numeric information like sales amount and profit.
    - `'people'`: list of regional managers and the regions they manage [I did not use this sheet in my analysis].
    - `'returns'`: list of order id numers of orders that were returned and a column with a boolean to indicate that they were returned.

### Description:
- 9 page Tableau workbook
- Includes 8 visualizations [7 bar charts, 1 line chart] and one dashboard.

### Process:
I first reviewed the data.
I opened the orders sheet in Tableau and created visualizations for profit and loss analysis and analysis of best states and months for advertising.
I then LEFT JOIN'ed the returns sheet to the orders sheet.
I created a calculated field to show unreturned orders as 0 and retuned orders as 1.
Lastly, I finalized formatting for the client's readability.

### Findings:
1. The greatest profit centers for the business are the product sub categories of copiers and phones.			
2. The subcategories of tables and bookcases are the greatest loss makers for the company. 	
3. The five products causing the greatest losses for the business, which I therefore recommend be discontinued, are the Cubify CubeX 3D Printer Triple Head Print (product ID TEC-MA-10004125), the Cubify CubeX 3D Printer Double Head Print (product ID TEC-MA-10000418), the GBC DocuBind P400 Electric Binding System (product ID OFF-BI-10004995), the Cisco TelePresence System EX90 Videoconferencing Unit (product ID TEC-MA-10002412), and the Lexmark MX611dhe Monochrome Laser Printer (product ID TEC-MA-10000822).			
4. The states with the highest average profits are Vermont, Rhode Island, and Indiana.
5. The five items with the highest return rates are Global Wood Trimmed Manager's Task Chair, Khaki (product ID FUR-CH-10003774) with 29 returns, Global Troy Executive Leather Low-Back Tilter (product ID FUR-CH-10001215) with 26 returns, Global Leather Task Chair, Black (product ID FUR-CH-10003061) also with 26 returns, Pressboard Covers with Storage Hooks, 9 1/2" x 11", Light Blue (product ID OFF-BI-10000343) with 25 returns, and Xerox 1881/Xerox 1908 (product ID OFF-PA-10001970) with 25 returns.
6. The six customers with the most returns are Seth Vernon (customer ID SV-20365) with 214 returns, William Brown (customer ID WB-21850) with 147 returns, Ted Butterfield (customer ID TB-21055) with 90 returns, Sandra Glassco (customer ID SG-20080) with 83 returns, Dan Reichenbach (customer ID DR-12880) and Stefania Perrino (customer ID SP-20620) both with 82 returns each.

### Reviewer’s Comments:
“Hello, Jillian!

The dashboard is easy to read, you brilliantly answered all the questions. I also want to note that the visualizations themselves are designed in a similar style, this makes it easier to understand the information on dashboard, great!

Alexander Matveevsky”
