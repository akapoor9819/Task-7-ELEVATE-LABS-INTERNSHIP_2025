# Sales Data Analysis Project

## Overview
This project analyzes basic sales data from a small SQLite database using Python. The aim is to calculate total quantity sold and total revenue for each product, and visualize the results with simple bar charts.

## Tools & Libraries
- Python 3.x
- sqlite3 (built-in Python library for SQLite)
- pandas (for data manipulation)
- matplotlib (for data visualization)

## Dataset
The dataset is stored in a SQLite database file `salesdata.db` with a single table named `sales`.
The sales table contains the following columns:
- product (string)
- quantity (integer)
- price (float)

## Steps Performed
1. Connected to the SQLite database using sqlite3.
2. Ran SQL queries to fetch the total quantity sold and total revenue grouped by product.
3. Loaded the query results into pandas DataFrames.
4. Printed summary tables of the results.
5. Created bar charts to visualize product revenue.
6. Saved charts as image files.

## Extra Analysis (Optional)
- Identified top 3 products by revenue.
- Calculated the average price per product.
- Found total quantity sold overall.
- Visualized extra metrics using bar charts.

## How to Run
- Ensure Python and required libraries (pandas, matplotlib) are installed.
- Place `salesdata.db` in your working directory.
- Run the provided Python script or Jupyter notebook.
- Output tables will display in the console and charts will pop up and save as PNG files.

## Results & Insights
- Bar charts show revenue rankings of products.
- Basic summary provides clear understanding of sales distribution.
- Extra analyses offer deeper insights into sales performance.

## Repository Contents
- Python script / Jupyter notebook with code
- salesdata.db (SQLite database file)
- Generated bar chart images (PNG files)
- This README.md file

## Author
[Ashutosh Kapoor]

## License
This project is licensed under the MIT License.
