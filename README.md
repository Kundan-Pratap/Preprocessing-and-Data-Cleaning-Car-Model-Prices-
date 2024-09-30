# Quikr Car Data Cleaning and Analysis

This repository contains a Jupyter Notebook that demonstrates the process of cleaning and analyzing used car data obtained from Quikr. 

## Data Cleaning Steps

The notebook walks through the following steps:

1. **Data Loading:** Load the raw `quikr_car.csv` dataset.
2. **Data Exploration:** Analyze the structure and properties of the dataset, identify inconsistencies, and explore the unique values of different features.
3. **Data Quality Issues:** Identify and address data quality problems such as inconsistent naming conventions, incorrect data types, missing values, and outliers.
4. **Data Cleaning:** Perform operations to clean the dataset, including:
    - Removing irrelevant rows and entries.
    - Converting data types (e.g., year to integer, price to numeric).
    - Handling missing values (e.g., dropping rows with NaN fuel types).
    - Removing outliers (e.g., cars with unusually high prices).
5. **Data Preprocessing:** Transform the data into a more usable format, including:
    - Standardizing feature values.
    - Creating new derived features.
6. **Data Export:** Export the cleaned dataset as a CSV file `Cleaned_Car.csv`.

## Purpose

The goal of this notebook is to provide a clear example of the data cleaning process, demonstrating best practices for handling various data quality issues that are common in real-world datasets. 

## Usage

1. Clone the repository.
2. Open the Jupyter Notebook.
3. Follow the steps documented in the notebook to run the data cleaning and analysis.

## Dataset

The dataset used in this notebook was originally sourced from Quikr, a popular classifieds website in India. It contains information about various used cars listed on the platform.

## Acknowledgements

The original dataset may have been obtained from a public source, and the notebook code is an original creation for the task of data cleaning and analysis.
