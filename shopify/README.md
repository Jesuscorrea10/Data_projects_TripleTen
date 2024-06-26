# File Title: Shopify.pbix

This project was part of my sprint 6  in the TripleTen Business Intelligence Analytics Program. It was a solo project where I got to demonstrate what I've learned about using Power BI.

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 2 | [Requirements.txt](https://github.com/Jesuscorrea10/Data_projects_TripleTen/blob/main/shopify/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 3 | [Shopify.pdf](https://github.com/Jesuscorrea10/Data_projects_TripleTen/blob/main/shopify/Shopify.pdf) | A .pdf file with screenshots of the 3 page Power BI Dashboards of my project. |

| Section Title | Description |
| ----------- |----------- |
| Data | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final products purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
The excel file provided by TripleTen was was public data scraped from the Shopify App Store.
- `'shopify.xlsx'`: Excel Workbook containing 4 sheets:
    - `'apps'`: Details of the apps on Shopify apps marketplace
    - `'apps_categories'`: Join tables to connect apps with categories
    - `'categories'`: Categories of the apps. Each app has multiple categories
    - `'reviews'`: Each review (row) contains information on user opinion about the related app (rating and comment). It also contains the response from the developer if present.

### Description:
- 3 page Power BI Dashboards
- Includes data analysis, KPI cards and Charts
- Purpose was to review the landscape of apps on the Shopify platform, using data scraped from publicly available Shopify websites, and to figure out what key factors play into the success of a Shopify app.

### Assumptions:
- The scraped data from Shopify websites is accurate and representative of the actual app landscape.
- The data in the shopify.xlsx file is complete and consistent, with minimal missing values or inconsistencies.
- The provided column names and data types in the tables accurately reflect their content.

### Process:
I first assessed the app store landscape using KPI cards and charts.
Then I cataloged review data with cards and charts.
Lastly I analyzed app developers across review types.

### Findings:
1. New Apps are more likely to be rated early in their deployment.
2. Most apps are rated favorably.
3. Reviews are higher for an app if a developer answered the review.
4. Reviews that have been voted as helpful have a weighted average of 4.97.
5. Most apps have fewer reviews, which hints that most apps get limited attention 

