# Pesa Pulse: Customer Data Analysis

## Project Overview

Pesa Pulse is a customer data analysis project for a fictional Nairobi fintech startup. The project retrieves customer records from an API, explores nested JSON data, extracts useful attributes, performs analysis using Python and pandas, and visualizes customer distribution.

## Objectives

- Retrieve customer data from an API using Python.
- Explore nested dictionaries and identify data types.
- Extract customer attributes into a structured dataset.
- Identify unique cities and count customers by city and email domain.
- Convert the extracted data into a pandas DataFrame.
- Export analysis results to CSV files.
- Create and save a customer distribution chart.

## Tools and Technologies

- Python 3.12
- Jupyter Notebook
- Requests
- pandas
- Matplotlib
- uv for Python project and package management

## Data Source

The project uses the JSONPlaceholder sample API:

https://jsonplaceholder.typicode.com/users

The endpoint returns 10 sample customer records containing personal details, addresses, geographical coordinates, and company information. These are mock records, not real fintech customer data.

## Key Analysis

- Retrieved and inspected 10 customer records.
- Extracted customer information, including email domains, cities, ZIP codes, coordinates, company names, and websites.
- Counted customers by city and email domain using plain Python.
- Used pandas to organize the extracted data and verify the city counts.
- Created a bar chart showing customer counts by email domain.

## Key Findings

- The sample contains 10 customer records.
- Each customer in the sample has a different city.
- Each email domain appears once, so no email domain dominates the sample.
- The sample is small and should not be treated as representative of actual customer distribution.

## Project Outputs

The `output/` folder contains:

- `customers.csv` — extracted customer attributes.
- `city_counts.csv` — customer counts by city.
- `customer_distribution.png` — customer distribution by email domain.

## How to Run

1. Clone or download the project.
2. Install Python 3.12 and uv.
3. Open the project folder in VS Code.
4. Install the project dependencies with `uv sync`.
5. Open `analysis.ipynb` and select the project's `.venv` Python environment.
6. Run the notebook cells from top to bottom.

## Conclusion

This project demonstrates Python API requests, nested dictionary exploration, data extraction, dictionary and set operations, pandas analysis, CSV exports, and data visualization. It provides a foundation for further customer analytics using larger and more representative datasets.