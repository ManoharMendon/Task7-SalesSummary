Features
- Connects to an SQLite database (`sales_data.db`) containing sales records.
- Runs SQL queries to compute:
  - Total quantity sold per product
  - Total revenue per product
- Displays results in the console using Python `print`.
- Visualizes revenue per product using a bar chart.

- install dependencies - pip install pandas matplotlib(%matplotlib inline)
- Tool used - Jupyter Notebook


In this project, we created a basic sales analysis pipeline using Python and SQLite. The main steps we completed are:

Database Setup
  Created a small SQLite database sales_data.db with a single table sales.
  Populated the table with sample sales data including order_date, product, quantity, and price.

SQL Queries
  Wrote SQL queries to calculate total quantity sold and total revenue per product.
  Used GROUP BY and SUM() to aggregate data for meaningful insights.

Data Loading and Analysis in Python
  Connected to the SQLite database using Python’s sqlite3 module.
  Loaded SQL query results into a pandas DataFrame for easy manipulation and display.
  Added a total row to show overall sales and revenue.

Visualization
  Plotted a bar chart using matplotlib to visualize revenue per product.
  Optional enhancements could include pie charts, monthly trends, or exporting outputs.
