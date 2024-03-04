# File Title: nyc_airbnb_data

My first project in the TripleTen Business Intelligence Analytics Program. It was a solo project to showcase my skills in Advanced Spreadsheets.

Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1pLIpok9BPEhwFzKUP93dXIRwF6_cKqtj-jqO6nnzvmk/edit?usp=sharing' target=_blank><u>here</u>.</a>

 ### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 2 | [Requirements.txt](https://github.com/Jesuscorrea10/Data_projects_TripleTen/blob/main/Vacation%20Rental%20Market/Requirements.txt)| A simple .txt file with the provided project requirements as provided by TripleTen. |

| Section Title | Description |
| ----------- |----------- |
| Data | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final products purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
The data was one Google spreadsheet file provided by TripleTen:
- `'nyc_airbnb_data.csv'`: each row corresponds to one listing on AirBnB in September 2022
    - `'data_dictionary'`: summary of field titles seen in file and it's data type
    - `'listings'`: uniquely listings available with all available data
    - `'calendar'`: listings with upcoming availabilities and date type data
 
### Description:
- 11 page spreadsheet
- Includes raw data, processed data, data analysis, pivot tables, and a bar chart.
- The objective was to identify the ideal properties for targeting the vacation rental market in the Manhattan borough of New York City, utilizing available Airbnb data.

  ### Assumptions:
- Airbnb rentals are equivalent to the general vacation rental statistics.	
- Rental activity is assumed through the number of reviews in the last 12 months.
- Properties with no reviews in the last 12 months were considered inactive.
- High review ratings are greater than or equal to 4.5.
- Very actively rented properties are rented greater than or equal to 40 times over the last 12 months.
- The dataset suggests a higher demand for property rentals on weekedns

### Process:
- Explored and cleaned the NYC Airbnb dataset, addressing data cleaning challenges.
- Utilized aggregations and pivot tables to identify attractive neighborhoods and popular property sizes.
- Calculated occupancy rates and estimated annual revenue for targeted properties.
- Explored the impact of superhosts, instant booking, doorman presence, and review ratings on pricing and occupancy.
- Organized and documented cleaning steps.
- Created an Executive Summary for overview.
- Applied consistent formatting for client readability.

### Findings:
- Top 3 neighborhoods for short-term rentals in the New York market: Lower East Side, Harlem, Hell's Kitchen.
- Most popular & better performance vacation rental size: 1 bedroom overall.
- Fridays have the highest weekly occupancy rate.
- Investment highlight: Lower East Side and 1-bedroom properties with an 88.96% occupancy rate, $254.17 nightly cost, and potential annual revenue of $82,531.29.
