Revenue Analysis 

Overview

This project performs a quantitative analysis of internal sales data for Q1 2023 (January - March). Using Python and Pandas, the analysis processes raw sales records to derive insights regarding revenue generation, product performance, temporal trends, and customer demographics.

Files in this Repository

revenue_Analysis-checkpoint.ipynb: The primary Jupyter Notebook containing the Python code for data creation, cleaning, analysis, and visualization.

revenue_analysis_report.md: A summary report highlighting key findings, including total revenue and top-performing demographics.

young_customer_report.csv: (Generated Output) A filtered dataset containing sales records for customers under the age of 30.

young_customer_report.xlsx: (Generated Output) An Excel version of the filtered dataset.

Technologies Used

Python 3

Pandas: For data manipulation, cleaning, and aggregation.

Matplotlib: For generating visualizations (bar charts).

Jupyter Notebook: Interactive development environment.

Setup & Installation

To run the analysis locally, ensure you have the following dependencies installed:

pip install pandas matplotlib openpyxl


Note: openpyxl is required for exporting the Excel report.

Analysis Workflow

The notebook performs the following steps:

Data Ingestion: Creates a mock dataset representing sales transactions (Date, Product, Price, Quantity, Customer Age).

Data Cleaning: Converts date strings to datetime objects and calculates a new Total_Sales metric (Price * Quantity).

Exploratory Analysis:

Aggregates revenue by Product to identify top sellers.

Aggregates revenue by Month to track seasonal trends.

Visualization: Generates a bar chart visualizing total revenue by product.

Demographic Filtering: Isolates transactions for customers under 30 years old to analyze youth purchasing behavior.

Export: Saves the filtered demographic data to CSV and Excel formats.

Key Findings

Total Revenue: $5,375

Top Product: Laptops ($4,000 revenue)

Key Demographic: Customers under 30 accounted for roughly 74% of the total revenue.

For a detailed breakdown of the results, please refer to revenue_analysis_report.md.
