# File Title: nyc.airbnb.data_v1.5_2024.08.28

This was the first project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned about Advanced Spreadsheets. This project is about analyzing Airbnb listings in Manhattan, NYC to help a client decide what type of vacation rental property to invest in.

[<img src="https://github.com/JillianKingsley/data_projects_TripleTen/blob/5d13f584fad4464afc497c4937b68dff6c23f704/NYC_Airbnb_Project_Files/NYCAirbnbDataProject.png" alt="Pivot Table and Bar Chart">](https://docs.google.com/spreadsheets/d/10qHwp-aoB-pWhKFM_GUHiElx9ERSwIXKpUCtOo-fCsY/edit?usp=sharing)


Projects Google Sheets workbook can be found <a href='https://docs.google.com/spreadsheets/d/10qHwp-aoB-pWhKFM_GUHiElx9ERSwIXKpUCtOo-fCsY/edit?usp=sharing'><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | README.md | This current page with all relevant information about the project. |
| 2 | [Advanced Spreadsheets Rubric](https://github.com/JillianKingsley/data_projects_TripleTen/blob/5d13f584fad4464afc497c4937b68dff6c23f704/NYC_Airbnb_Project_Files/Advanced_Spreadsheets_Rubric.pdf) | A .pdf file with the provided project review rubric provided by TripleTen. |
| 3 | [nyc_airbnb_data.csv](https://github.com/JillianKingsley/data_projects_TripleTen/blob/5d13f584fad4464afc497c4937b68dff6c23f704/NYC_Airbnb_Project_Files/nyc_airbnb_data%20-%20data_dictionary.csv) | The original data file provided by TripleTen that was used in the analysis of this project. |

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
- `'nyc_airbnb_data.csv'`: each row corresponds to one listing on AirBnB in September 2022
    - `'data_dictionary'`: summary of field titles seen in the file and its data type
    - `'listings'`: unique listings available with all available data
    - `'calendar'`: listings with upcoming availabilities and date-type data

### Description:
- 13 page workbook
- Includes raw data (protected), processed data, data analysis, pivot tables, and a bar charts.

### Assumptions:
- Luxury listings with prices greater than $500 were excluded from the analysis as they were deemed unrepresentative of the target listing type
- Reviews during the last twelve months were used as an estimate of how often a listing was rented within the last year
- Listings with fewer than 1 review in the last twelve months were considered inactive rentals
- Listings with superhosts were viewed as representative of the target listing type
- Neighborhoods with the most reviews in the last twelve months were considered to be the most popular neighborhoods
- Only listings with a minimum night rental of seven nights or fewer were included in the analysis as they were deemed representative of the target listing type
- Average annual revenue estimate was calculated by multiplying 365 days by the average price per listing by the occupancy percentage per listing then finding the average of those estimates of annual revenue per listing
- Average occupancy percentage for the Lower East Side neighborhood was found by calculating the average of the occupancy percentage for the Lower East Side listings	

### Process:
I first reviewed, filtered, and cleaned the data.
I performed calculations and created pivot tables and charts to determine occupancy rates and estimated revenue in the target neighborhood.
I documented all changes to the workbook and created a table of contents and an executive summary for ease of use by the client.
Lastly, I finalized formatting for the client's readability.

### Findings:
1. The top 10 popular neighborhoods for vacation rentals are the following in decending order: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Nolita.			
2. The most popular vacation rental size is 1 bedroom overall. The Lower East Side has the highest 1 bedroom demand followed by Nolita and the Upper East Side. 	
3. Fridays have the highest occupancy rate out of the week followed by less than 1 percentage point by Saturdays.			
4. The average estimated annual revenue for such properties in this neighborhood is $61,333.12.
5. The Lower East Side Neighborhood had a high occupancy rate with an average of 57.36%.

### Reviewer’s Comments:
“Hello, Jillian!

Your Excel is easy to read, you brilliantly added calculations and precisely answered all the questions. You did an excellent job in this project! Excel can be tedious, but it is a powerful tool.
There are no issues that need to be fixed, so I can accept the project now. Awesome job!
Thank you for your work and I wish you success in your next projects!)

Alexander Matveevsky”

