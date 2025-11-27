# Nike Product Data Analysis & Visualization

A comprehensive data analysis and business intelligence project exploring Nike product listings, pricing, discounts, and customer ratings using a scraped dataset. The insights are presented through an interactive dashboard built with Power BI for actionable business insights.


## Overview

This project is a **Business Intelligence (BI)** case study focused on analyzing and visualizing scraped data from Nike's online product listings.

The core objective was to transform raw product data (including pricing, discounts, and product details) into actionable insights to understand the company's product performance, pricing strategy, and customer engagement.

The final output is an interactive **Power BI Dashboard** (`Nike.pbix`) that allows users to filter, explore, and derive insights on the product catalog, discount effectiveness, and average customer ratings.

## Data Source

The analysis is based on a single dataset:

* **`nike_2020_04_13.csv`**: A CSV file containing product information scraped on April 13, 2020.
    * **Volume**: Contains data for a single day's snapshot.
    * **Key Fields**:
        * `Product Name`, `Product ID`
        * `Listing Price`, `Sale Price`, `Discount`
        * `Rating`, `Reviews`
        * `Description`, `URL`, `Images`

## Tools and Technologies

| Category | Tool / Technology | Purpose |
| :--- | :--- | :--- |
| **Data Analysis & Visualization** | **Power BI Desktop** | Core tool used for data modeling, transformation (Power Query/M), DAX calculations, and final report visualization. |
| **Data Storage** | **CSV** | Format for the raw, structured product data. |

## Key Features and Analysis Highlights

The Power BI dashboard provides several analytical perspectives, including:

1.  **Discount Strategy Analysis**: Visualizing the distribution of products across different discount brackets and identifying the total revenue impact of discounts.
2.  **Product Catalog Exploration**: Dynamic slicers and filters to explore products by name and category (inferred from names/descriptions).
3.  **Pricing Distribution**: Histograms or charts showing the range and concentration of `Sale Price` and `Listing Price`.
4.  **Customer Engagement**: Analysis of average `Rating` and count of `Reviews` to highlight top-rated and most-reviewed products.
5.  **Interactive Filters**: Time-based and product-attribute filters allow for deep-dive exploration.

## How to View the Report

To interact with the full report, you will need **Microsoft Power BI Desktop** (available for free).

1.  **Download**: Clone or download this GitHub repository.
2.  **Open**: Double-click the file **`Nike.pbix`**.
3.  **Explore**: The report will load, allowing you to interact with all the charts, tables, and slicers.

## Project Structure
