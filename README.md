# Energy Consumption Analysis
## Overview

This project analyzes worldwide energy consumption, production, emissions, GDP, and population data across multiple countries and years. The goal is to uncover patterns and correlations between economic growth, energy usage, and environmental impact using structured SQL analysis.

The analysis was performed in MySQL, with data integrated from multiple CSV files into a relational database. By designing a normalized schema and executing complex queries, the project provides insights into global energy trends and efficiency.

## Objective

To examine global energy consumption patterns and their relationship with GDP, emissions, and population growth.

To identify high-emission and high-consumption countries.

To explore per-capita energy usage and the emission-to-GDP ratio over the years.

To highlight opportunities for sustainable and efficient energy use.

## Database Design

The project includes six interconnected tables:

country – Contains country names and unique IDs.

emission – Records total and per-capita emissions by country, year, and energy type.

population – Stores population data by country and year.

production – Tracks energy production by country, energy type, and year.

gdp – Includes GDP values by country and year.

consum – Captures total energy consumption data segmented by country, energy type, and year.

All tables are linked through the country_id attribute, ensuring data consistency and integrity.

## Key SQL Analyses

Total emissions per country for the most recent year

Top 5 countries by GDP

Comparison of energy production vs. consumption by year

Correlation between GDP growth and energy production growth

Energy consumption per capita over the last decade

Global share (%) of emissions by country

Global average GDP, emissions, and population by year

## Insights & Findings

Countries with higher GDP generally show increased energy consumption and emissions.

Lower emission-to-GDP ratios indicate better energy efficiency.

Population growth is strongly correlated with rising emissions.

There is a clear need for investment in renewable and cleaner energy sources to achieve sustainable growth.

## Technologies Used

Database: MySQL

Languages: SQL

Tools: Excel, PowerPoint

Skills Applied: Data Modeling, Joins, Subqueries, Aggregations, Schema Design, Data Visualization

## Project Outcomes

Designed and implemented a normalized relational database from raw datasets.

Executed over 30 complex SQL queries for analysis and reporting.

Developed dashboards and presentations summarizing trends and business insights.

LinkedIn: https://www.linkedin.com/in/akshar-sheik-8020662bb/

GitHub: https://github.com/aksharsheik

Email: aksharsheik@gmail.com
