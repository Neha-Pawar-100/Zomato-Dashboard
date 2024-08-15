# Zomato Sales and User Analysis Dashboard

## DESCRIPTION
This Power BI dashboard provides an in-depth analysis of Zomato sales and user data. It provides detailed insights into sales performance, user demographics, and city-specific metrics, all designed to facilitate data-driven decision making.

## FEATURES
### Overall Sales Analysis
* **Sales Visualization** : Displays amount-wise and quantity-wise sales with interactive slicers.
* **City Rankings** : Explores sales data for Top 5, Top 10, Top 20, Top 50, Top 100 cities by both-sales amount and sales quantity.
* **Yearly Sales Trends** : Analyzes sales trend over the years using a line chart.
* **Summary Cards** : View key metrics including total sales amount, total quantity, total orders, and total ratings.

### Segment Analysis
* **Sales by segemnt** : Examine sales data by segments (Veg, Non-Veg, Others) and their corresponding ratings using card visualization.

### Search Bar Functionality
* **City Search** : Utilize the search bar to filter and view insights for specific cities through interactive charts.

### User Analysis Page
* **Age Distribution** : Analyze total users by age using a column chart.
* **User Gain and Loss** : Examined Total gained and lost users and examined gender-wise proportion.
* **Summary Metrics** : View Total users, Total ratings, Total sales amount, and Total orders.
* **Interactive Slicer** : Filter user data by sales amount and quantity.

### City Analysis Page
* **City Metrics** : Analyzes sales, user count, and ratings by city using a bar chart.
* **Detailed Metrics** : Build a table with city-wise order counts and sales amount.
* **Search and Filter** : Use the search bar to filter the city data.
* **Bookmark Feature** : Access detailed analysis by Year, Quarter, Month, and specific Dates using the bookmark functionality.

## INSTALLATION
### Prequisites
* Power BI Desktop

## SETUP INSTRUCTIONS
* Download the Power BI file from this repository.
* Open the file in Power BI desktop.
* Connect to the data source if needed.

## USAGE
* **Interactivity** : Use slicers and search bars to filter and interact with the data.
* **Navigation** : Switch between pages for sales analysis, user analysis, and city analysis.
* **Bookmarks** : Utilize bookmarks for in-depth city-wise analysis across different time periods.


## SCREENSHOTS
### Dashboard Overview

<img width="1080" alt="ZPic 4" src="https://github.com/user-attachments/assets/74c85323-88c4-4a5e-b820-b9be56922ce3">

### User Analysis

<img width="1080" alt="ZPic 2" src="https://github.com/user-attachments/assets/c89366f1-5072-4526-a15c-65f892e1584c">

### City Analysis

<img width="1080" alt="ZPic 3" src="https://github.com/user-attachments/assets/a87a2d58-ca2a-4ffb-8722-dd14d1bcb191">

## DAX FUNCTIONS USED
### Utilized a range of DAX functions to enhance data analysis and modellinng.
* **Calculate** : Applied for complex calculations and aggregations.
* **SelectedValues** : Used to retrieve values from tables and columns.
* **Right** : Employed for text manipulation and data extraction.
* **Filter** : Implemented to refine data subsets and apply conditional logic.
* **Summarize** : Created aggregated summaries and table.
* **If** : Incorporated for conditional calculations and logic.
* **Count,Sum,DistinctCount** : Utilized for various counting and aggregation needs.
* **Floor** : Applied to round down numerical values for reporting purposes.
* **RankX** : Used for ranking data and generating performance metrics.
* **DataTable** : Created static data table within the Power BI model.
