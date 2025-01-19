# Sales Data Analysis Project

## Project Overview
This project involves analyzing and visualizing sales data to gain insights into customer behavior, sales performance, and profitability. The dataset includes order details, sales information, and is supplemented by Power BI visualizations for interactive analysis.

## Files in the Repository

### 1. Orders.csv
- **Description**: Contains basic order details.
- **Columns**:
  - `Order ID`: Unique identifier for each order.
  - `Order Date`: Date of the order.
  - `CustomerName`: Name of the customer who placed the order.
  - `State`: State where the order was delivered.
  - `City`: City where the order was delivered.

### 2. Details.csv
- **Description**: Provides detailed sales data linked to `Order ID`.
- **Columns**:
  - `Order ID`: Unique identifier for each order (links to Orders.csv).
  - `Amount`: Total amount of the order.
  - `Profit`: Profit generated from the order.
  - `Quantity`: Number of items sold.
  - `Category`: Broad category of the items sold.
  - `Sub-Category`: Specific type of items sold.
  - `PaymentMode`: Mode of payment used by the customer.

### 3. Sales data.pbix
- **Description**: A Power BI file for interactive visualizations of the sales data.
- **Purpose**: Enables deeper analysis and visualization of key metrics such as sales trends, profit margins, and customer segmentation.

## How to Use
1. **Data Exploration**:
   - Load the `Orders.csv` and `Details.csv` files in Python, Excel, or any data analysis tool to explore raw data.
   - Use `Order ID` as the key to merge these files for a complete dataset.

2. **Power BI Visualization**:
   - Open the `Sales data.pbix` file in Power BI Desktop.
   - Interact with dashboards to explore metrics like total sales, profits, and product performance.

## Key Insights (Example)
- Identify top-performing cities and states.
- Analyze the most profitable product categories.
- Review customer purchase patterns and preferred payment modes.

## Prerequisites
- Python (with libraries like pandas, matplotlib for analysis).
- Power BI Desktop (to open and interact with the PBIX file).



---
