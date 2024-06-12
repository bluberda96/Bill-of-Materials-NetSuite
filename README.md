# Bill of Materials - NetSuite

## Overview
This project consists of several Python scripts designed to process and transform data from CSV files, particularly focusing on Custom Frame (CF) items. The scripts read data from an input CSV file, perform various transformations, and generate output files suitable for importing into NetSuite. The scripts also handle splitting the output files to ensure they do not exceed NetSuite import limits.

## Requirements
- Python 3.6+
- pandas
- numpy
- requests
- requests_oauthlib
- oauthlib

You can install the required Python packages using the following command:

pip install pandas numpy requests requests_oauthlib oauthlib

# Files
- main.ipynb: This Jupyter Notebook contains the primary script for processing the CF item data. The script is divided into multiple code cells, each performing specific tasks.
- Template CF Bill of Materials Revision.csv: This CSV file serves as a template for generating the Bill of Materials (BOM) revision data.
- CF Item Data test.csv: This is the input CSV file containing the CF item data to be processed.
# Usage
- Set Up the Environment: Ensure you have installed the required Python packages.
- Prepare Input Files: Place the CF Item Data test.csv file in the same directory as the script.
- Run the Script: Open the main.ipynb Jupyter Notebook and run each cell sequentially. This will process the input data and generate the output files.
