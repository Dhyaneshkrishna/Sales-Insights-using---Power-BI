# Sales Insights using Power BI

## Project Overview
This project involves creating a **Sales Insights Dashboard** using **Power BI** to analyze and visualize sales data stored in a **MySQL database**. The goal is to understand market performance, track sales trends, and predict future sales through interactive and dynamic visualizations.

## Key Features
- **Data Cleaning**: Processing raw sales data to ensure accuracy.
- **Data Visualization**: Generating various charts to represent total sales, sales by category, and customer contributions.
- **Sales Insights**: Analyzing trends to highlight top-performing markets and products.
- **Forecasting**: Implementing predictive models to forecast future sales.

## Data Sources
The project uses the following **MySQL databases**:
- **Sales Data**: Contains sales information for various products and markets.
- **Customer Data**: Information about customer purchases and behaviors.
- **Market Comparison Data**: Comparison metrics for different sales markets.

## Libraries Used
- **Power BI**: Data analysis and visualization tool for this project.
- **MySQL**: Used for storing and querying sales data.

## Data Cleaning Process
- **Removed Unnecessary Columns**: Cleaned up irrelevant columns in the dataset.
- **Handled Missing Values**: Addressed any gaps in the data.
- **Formatted Date Columns**: Ensured all date-related columns were in the proper format for time-series analysis.

## Visualizations Created
1. **Revenue by Market**: Bar chart displaying total revenue by market.
2. **Sales Quantity by Product Category**: Horizontal bar chart showcasing sales quantities by product category.
3. **Sales Trend Over Time**: Line chart illustrating sales performance over time.
4. **Top Customers**: Table showing top customers based on sales revenue.

## Insights Gained
- **Delhi NCR** emerged as the highest revenue-generating market.
- **Electricalsara Stores** is the top customer contributing to the most sales.
- Sales consistently grew, with a notable spike in **2019**.

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Dhyaneshkrishna/Sales-Insights-using---Power-BI.git

2.**MySQL Setup**:
Download and install MySQL from here.
Import the provided SQL database schema to your MySQL server.
Ensure the necessary data tables are set up (Sales Data, Customer Data, etc.).

3.In Power BI, connect to your MySQL database to query the required data using SQL.

4.Open the .pbix Power BI file and start exploring the visualizations.

**Sample SQL Query to Fetch Sales Data:**
sql
SELECT market, SUM(revenue) as total_revenue
FROM sales_data
GROUP BY market;

**Installation Requirements:**
Power BI Desktop: Download from Microsoft store.
MySQL Server: Ensure MySQL is set up and running for data storage and querying.
Steps:
1.Clone this repository:
git clone https://github.com/Dhyaneshkrishna/Sales-Insights-using---Power-BI.git
2.Set up the MySQL database and import the relevant data files.
3.Open the .pbix file in Power BI Desktop to view and interact with the dashboard.
   
