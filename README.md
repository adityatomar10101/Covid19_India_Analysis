# COVID-19 Data Extraction and Analysis Project

## Project Description

The COVID-19 Data Extraction and Analysis Project aims to extract, clean, and analyze COVID-19 data from two JSON datasets related to the COVID-19 pandemic in India. The project utilizes Python for data extraction and cleaning, SQL for data analysis, and Microsoft Excel for creating interactive dashboards to visualize insights.

## Problem Statement

The primary objectives of this project are as follows:
1. Extract COVID-19 data from JSON datasets provided through specific URLs.
2. Clean and transform the raw data into a structured CSV format.
3. Perform data analysis to gain insights into the pandemic's trends and patterns.
4. Present the findings and trends through interactive dashboards for easy visualization and understanding.

## Data Description

### Data Sources
- [Dataset 1](https://data.covid19india.org/v4/min/data.min.json): Contains COVID-19 data, including daily cases, deaths, testing, and more.
- [Dataset 2](https://data.covid19india.org/v4/min/timeseries.min.json): Provides time-series data for COVID-19 cases, testing, and other metrics.

### Data Format
The data is originally provided in JSON format, which is unstructured and complex. It includes information such as date-wise case counts, state-wise data, and various metrics related to the pandemic.

## Data Cleaning

The data cleaning process involves several steps to make the data suitable for analysis:
1. Retrieval of JSON data from the provided URLs.
2. Parsing and cleaning of the JSON data.
3. Transformation of the cleaned data into CSV format for easy analysis.

## Exploratory Data Analysis (EDA)

EDA is conducted using SQL and Excel to derive insights from the COVID-19 data:
- SQL queries are used to summarize and analyze the data, focusing on trends, regional patterns, and key metrics.
- Statistical analysis, including correlations, death rates, and growth rates, is performed using Excel.

## Insights

Key insights from the data analysis include:
- Trends in COVID-19 cases over time.
- Regional variations in case counts and vaccination rates.
- Correlations between testing, vaccination, and case counts.
- Calculation of death rates and recovery rates.
  ![image](https://github.com/adityatomar10101/Covid19_India_Analysis/assets/137819767/65e42c6b-125b-4c41-809e-0c313bf027ae)


## Challenges Faced

Several challenges were encountered during the project:
1. Dealing with unstructured JSON data and converting it into a structured format.
2. Handling missing or incomplete data points.
3. Ensuring data accuracy and consistency.
4. Creating interactive dashboards in Excel for effective data visualization.

## Key Learnings

The project provided valuable learning experiences:
1. Proficiency in data extraction and cleaning using Python.
2. SQL skills for data analysis and querying.
3. Excel skills for statistical analysis and dashboard creation.
4. Problem-solving skills when dealing with real-world, messy data.

## Future Scope

This project can be extended in the following ways:
1. Automating data extraction and cleaning processes to update the dataset regularly.
2. Enhancing the dashboard with more interactive features and real-time data updates.
3. Incorporating machine learning models for predictive analysis of COVID-19 trends.
4. Expanding the analysis to include demographic and socio-economic factors' impact on COVID-19.

By following the provided documentation and code, others can reproduce the data extraction and analysis processes to gain insights into the COVID-19 pandemic in India. The interactive dashboards facilitate a user-friendly exploration of the data and its trends.
