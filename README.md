# Awesome-Chocolates

## Overview
This is a Power BI project to Analyse the sales data of an imaginary Company called Awesome Chocolate, to discover hidden insights within their data for a more informed decision making.

## Data Source
The Data is downloaded from [chandoo.org](https://chandoo.org/wp/learn-sql-for-data-analysis/) for practice puporses.


# Approach used

Data Import - I used MySQL Database to import the data 

1. Open MySQL Workbench
2. Click on the “server administration” tab
3. Click on “Data Import/Restore”
4. Select the option “Import from self-contained file”
5. Specify the path of the downloaded awesome-chocolates-data.sql file
6. Start import


This data from MySQL Workbench is then connected to Power BI using Get data tab.

1. Open Power BI
2. Click on "Get data" tab
3. Search MySQL Database and connect
4. Enter the server and database name from where you are connecting
5. Load the data to Power BI


Data Cleaning - I proceeded to Power BI to go through the data once more to be sure its ready to be worked with.


Measure Creation - I used DAX to create new columns

1. Created Measures such as Total Sales, Total Boxes sold, Shipment Count and Lox Box Shipment(LBS) by using DAX Formulas.
2. Calculate Low Box Shipment percentage by using DIVIDE Function to divide Low Box Shipment by Shipment Count.


Visualization - Visualized the Total Sales, Total Boxes, Shipment Count, LBS%, Sales trend by year, overall Sales by Geographical area and Top 20 Salesperson put together in a dashboard.
