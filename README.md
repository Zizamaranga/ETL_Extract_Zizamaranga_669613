# ETL Extract Lab

Author: Ziza Maranga  
Student ID: 669613

## Description

This notebook demonstrates a basic ETL (Extract, Transform, Load) pipeline using Python. The primary objective is to extract data from a CSV file, perform necessary data transformations such as cleaning and formatting, and finally prepare it for loading into a target data structure or analysis-ready format.

## Tools Used

- Python 3.x
- pandas
- Jupyter Notebook

## How to Reproduce

### Running the Notebook

1. Make sure you have Python and Jupyter Notebook installed to run.
2. The data used is generated synthetically using python

2. Transformation (New Updates)
Today’s transformations include:

Cleaning: Handling missing values and removing duplicate records.

Enrichment: Adding calculated columns such as total_price = quantity * unit_price.

Structural Adjustments: Standardizing date formats and ensuring correct data types.

Both full and incremental datasets have been transformed and saved as:

transformed_full.csv

transformed_incremental.csv