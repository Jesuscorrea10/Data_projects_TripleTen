 # File Title: raw_transaction_logs

This was my third project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned for Business Analytics.

Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1uqM7DHuwv_mSoyxGjCFQm_HQSKJazqADh6-2H5cB320/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 2 | [Requirements.txt]() | A simple .txt file with the provided project requirements as provided by TripleTen.

| Section Title | Description |
| ----------- |----------- |
| Data | Describes the source of data, including files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
The data was one Google spreadsheet file provided by TripleTen
- `'Business Analyst Project.csv'`: raw transaction logs
    - `'raw_user_activity'`: Each row represents an activity, or event, by a user on the company’s website
        - `'user_id'`: unique customer IDs
        - `'event_type'`: the type of activity by the user
        - `'category_code'`: category of the product being viewed or purchased
        - `'brand'`: the company that makes the product
        - `'price'`: price of the product, in USD
        - `'event_date'`: date of the user activity, in YYYY-MM-DD format
    - `'Table of Contents'`: Preformated yet empty table of contents sheet
    - `'Executive Summary`: Preformated yet empty executive summary sheet
 
  ### Description:
- 8-page spreadsheet
- Includes raw data, processed data, data analysis, and pivot tables.
- The purpose was to analyze the companys' raw transaction logs and turn the event logs into business metrics.

  ### Assumptions:
- The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data format (columns, data types) is correct and consistent.

  ### Process:
- I first explored, filtered, and cleaned the data.
-  We use the raw data to analyze the customers activity through the sales cycle using a timeframe of a month since the first purchase.
-  Constructed a conversion funnel.
-  Prepared data for cohort analysis.
- Calculated retention rates.
- Finalized formatting and documentation for client readability.

### Findings:
| Results | Synopsis |
| :-----------: | ----------- |
| Conversion Funnel | Just 10.34% of users who view the page ended up buying. | 
| Retention Rates | There is a general pattern of decreasing retention rates over time. The highest retention is observed in the first month after the first purchase, followed by a consistent decline in subsequent months. | 



