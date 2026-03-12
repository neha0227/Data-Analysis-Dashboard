#Amazon sale Data Analysis(Interactive dashbaord in power Bi)
#Dataset used 
-<a href="https://github.com/neha0227/Data-Analysis-Dashboard/blob/main/Screenshot%202026-03-11%20162134.png"> Dataset</a>
1. KPI Understanding Questions
What is the total YTD (Year-to-Date) sales shown in the dashboard?
What does QTD (Quarter-to-Date) sales represent?
How many products were sold YTD according to the dashboard?
What is the total number of customer reviews YTD?
Which KPI helps measure customer engagement in the dashboard?

Process of Creating Amazon Sales Analysis Dashboard
1. Data Collection
The first step is collecting the Amazon sales dataset.
The dataset contains information such as:
Product Category
Product Name / Description
Order Date
Price (Dollar)
Number of Reviews
Shipment details


2. Data Loading
After collecting the dataset, the data is imported into Power BI using the Get Data option.
The dataset is loaded into the Power BI data model where tables and fields become available for analysis.

3. Data Cleaning and Transformation

In this step, Power Query Editor is used to clean the data:
Removing duplicate values
Handling missing values
Changing data types (text, number, date)
Creating calculated columns such as Month, Quarter, and Week


4. Creating a Date Table

A Date Table is created to perform time-based analysis like:
Month-wise sales
Weekly sales
Quarterly analysis

Date
Month Name
Month Number
Quarter
Week Number

5. Creating KPIs (Measures)
Using DAX (Data Analysis Expressions), important KPI measures are created such as:
YTD Sales (Year-To-Date Sales)
QTD Sales (Quarter-To-Date Sales)
YTD Products Sold
YTD Reviews

6. Data Modeling
Relationships are created between:
Amazon Sales Data Table
Date Table

7. Dashboard Visualization
KPI Cards → YTD Sales, QTD Sales, Products Sold, Reviews
Line Chart → Sales by Month
Bar Chart → Sales by Week
Table/Matrix → Sales by Product Category
Bar Chart → Top 5 Products by YTD Sales
Bar Chart → Top 5 Products by Reviews
These visuals help users easily understand trends and patterns.

8. Adding Filters (Slicers)
Interactive slicers are added for better analysis:
Product Category filter
Quarter filter
These filters allow users to analyze specific data segments dynamically.

9. Dashboard Design and Formatting
The dashboard layout is designed to make it clear and visually appealing:
Dark background theme
Highlighted KPI cards
Proper alignment of charts
Titles and labels for better understanding

Dataset used
-<a href="https://github.com/neha0227/Data-Analysis-Dashboard/blob/main/Amazon_Combined_Data.xlsx">Amazon sale Data</a>

#Dashboard 
-<a href="https://github.com/neha0227/Data-Analysis-Dashboard/blob/main/Screenshot%202026-03-11%20162134.png"> Dataset</a>
