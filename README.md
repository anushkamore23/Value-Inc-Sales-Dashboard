## ValueInc Sales Dashboard

A Tableau dashboard project designed to help **Value Inc.**, a global retail store that sells household items in bulk, gain clear insights into their sales, cost, and profit performance using Excel data.

## Project Overview

Value Inc.'s Sales Manager had no access to structured reporting and lacked visibility into monthly costs, top-selling items, and customer demographics. This project bridges that gap using a visually interactive dashboard built with **Tableau** and powered by data preprocessing in **Python**.

## Goals

- Visualize monthly **sales**, **cost**, and **profit** per transaction.
- Identify the **most profitable item codes**, **countries**, and **client segments**.
- Provide actionable insights for the sales manager to make **data-driven decisions**.
- Build a real-world analytics project using **Python + Excel + Tableau**.

## Data Source

- Format: `.xlsx` (Excel Spreadsheet)
- Fields included: `Transaction Date`, `Sales`, `Cost`, `Profit`, `Item Code`, `Client Age`, `Client Type`, `Country`
- Data was cleaned and prepared using the [`valueinc_sales.py`](https://github.com/anushkamore23/Python-Tableau/blob/main/valueinc_sales.py) Python script.



## 📊 Dashboard Features

| Component                        | Description                                                                |
|----------------------------------|----------------------------------------------------------------------------|
| **Sales per Transaction**        | Line chart showing monthly sales trends. Feb 2018 had the highest spike.   |
| **Cost per Transaction**         | Line chart for monthly cost insights. Useful for cost control.             |
| **Profit per Transaction**       | Highlights profit fluctuations over time. Feb 2018 was the peak.           |
| **Profit by Item Code**          | Bar chart to identify top-selling & profitable items (e.g., Item 465780).  |
| **Profit by Country**            | Geographic map showing global profit distribution.                         |
| **Profit by Client Age Group**   | Identifies most profitable customer age group (Seniors).                   |
| **Profit by Client Type**        | Shows which client category (Corporation, Small Business, Solo) is best.   |



## Key Insights

-  **Item 465780** generated the highest profit: `$52.94M`
-  **USA** was the top contributing country: `$229.14M` profit
-  **Senior clients** brought in the most revenue: `$58.46M`
-  **Corporations** were the most profitable client type: `$62.58M`
-  **February 2018** had an unusually high sales and profit spike



## Tech Stack

| Tool        | Purpose                             |
|-------------|-------------------------------------|
| **Python**  | Data cleaning and preprocessing     |
| **Pandas**  | Data manipulation                   |
| **Tableau** | Interactive dashboard and visuals   |
| **Excel**   | Original data source                |





