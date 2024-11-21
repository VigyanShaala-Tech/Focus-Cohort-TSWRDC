# Kalpana Focus Cohort TSWRDC Data Pipeline

## Overview

Welcome to the Kalpana Focus Cohort TSWRDC Data Pipeline repository! This project is designed to facilitate the cleaning and transformation of data from various sources, such as graphy and form. The processed data is then stored in a MySQL database, and Excel files are generated for further analysis and reporting.

## Folder Structure

- **scripts/:** Includes the Python script for processing and cleaning data.
  
- **output/:** Contains the output Excel files generated by the tool.

- **data_files/:** Holds the raw data from various sources, serving as input for the data cleaning and remapping process.
- 
- **excel_automation_scripts/:** Provide a Python script that replicates all tasks currently performed in Excel..


## How it Works

The Kalpana Incubator Data Remapping Tool follows these key steps:

1. **Data Ingestion:** Raw data from various sources is placed in the "Data Files" folder.

2. **Data Cleaning:** The code in the "scripts" folder processes and cleans the raw data to ensure it is ready for analysis and storage.

3. **Data Storage:** The cleaned data is stored in a MySQL database for further use.

4. **Output Generation:** The tool generates Excel files containing the cleaned data and places them in the "Output" folder.

## Getting Started

To start using the Data Pipeline, follow these steps:

1. Place your raw data files in the "Data Files" folder.

2. Execute the code in the "scripts" folder to process and clean the data.

3. Retrieve the cleaned data from the MySQL database for analysis.

4. Find the generated Excel files in the "Output" folder for reporting and sharing.

## Prerequisites

Make sure you have the following prerequisites installed:

- Python (version 3.6 or higher).
- Jupyter Notebook

## Additional Information

- **Dependencies:** Ensure you have the necessary dependencies and database connection information configured in the code before running it.

