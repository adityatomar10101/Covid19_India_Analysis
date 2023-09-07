# COVID-19 Data Extraction and Analysis Project

## Introduction

This project aims to extract COVID-19 data from two JSON datasets, clean and transform the data into CSV format, perform data analysis, and present insights through interactive dashboards.

## Data Sources

- [Dataset 1](https://data.covid19india.org/v4/min/data.min.json)
- [Dataset 2](https://data.covid19india.org/v4/min/timeseries.min.json)

## Tools Used

- Python
  - Pandas
  - Requests
  - NumPy
  - JSON
- SQL
- Microsoft Excel

## Data Extraction

The data extraction process involved using Python and the following steps:
1. Retrieving JSON data from the provided URLs.
2. Parsing and cleaning the data.
3. Converting the cleaned data into CSV format.

For detailed code and steps, refer to the [Covid_Project_json_to_csv.ipynb](Covid_Project_json_to_csv.ipynb) notebook.

## Data Analysis

Data analysis was conducted using SQL, Excel, and statistical methods. Key tasks included:
- SQL queries to derive insights (refer to [Covid_Project.sql](Covid_Project.sql)).
- Statistical analysis such as correlations, death rates, etc. in Excel.

For summarized insights and interactive dashboards, see [Project_dashboard.xlsx](Project_dashboard.xlsx).

## Folder Structure

- **Cleaned Extracted Data**: Contains the cleaned data in CSV format.
- **Notebooks**: Stores Jupyter notebooks used in data extraction and analysis.
- **SQL**: SQL scripts for data analysis.
- **Dashboard**: Excel files with interactive dashboards.

## Usage

To reproduce the data extraction and analysis:
1. Clone this repository.
2. Refer to the notebooks and scripts in their respective folders for detailed steps.
3. Explore the interactive dashboards in [Project_dashboard.xlsx](Project_dashboard.xlsx).
