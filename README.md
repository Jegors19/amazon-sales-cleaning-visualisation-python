# amazon-sales-cleaning-visualisation-python
This repository contains Python scripts to analyze the Amazon Sales Report. The scripts perform data cleaning, data exploration, data transformation, and visualizations on the dataset.




Output: 

<img width="915" alt="Screenshot 2023-08-24 at 22 12 02" src="https://github.com/Jegors19/amazon-sales-cleaning-visualisation-python/assets/116096669/ac914748-be12-4eca-9c48-ceabaf6aacc1"><img width="940" alt="Screenshot 2023-08-24 at 22 11 54" src="https://github.com/Jegors19/amazon-sales-cleaning-visualisation-python/assets/116096669/b912718c-236e-4f52-8cd3-bb509ea023ce">

<img width="757" alt="Screenshot 2023-08-24 at 22 13 10" src="https://github.com/Jegors19/amazon-sales-cleaning-visualisation-python/assets/116096669/11981c9f-6217-4e76-9f26-d32fb71298a4">

Dataset: https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data

Table of Contents

    Prerequisites
    Installation
    Usage
    Scripts Overview
        Analysis Script
        Story Three Script
    Contributing
    License

Prerequisites

    Python 3.x
    Pandas
    Matplotlib
    Seaborn
    Missingno
    mplcursors

Installation

    Clone the repository:

bash

git clone https://github.com/yourusername/amazon-sales-report-analysis.git

    Navigate to the directory:

bash

cd amazon-sales-report-analysis

    Install the required packages:

bash

pip install -r requirements.txt

Usage

    Place your 'Amazon Sale Report.csv' and 'sales_report_cleaned.csv' in the root directory.
    Run the scripts:

bash

python analysis.py
python story_three.py

Scripts Overview
Analysis Script:

    Dataset Exploration: Loads the dataset and explores its structure using Pandas.
    Data Cleaning:
        Removes unnecessary columns.
        Handles missing values.
        Drops duplicates.
        Renames columns for better readability.
    Date Conversion: Converts the date column to a datetime format.
    Geographic Names Cleaning: Cleans state and city names.
    Cancelled Parcels Analysis: Segregates the dataset based on shipping status.
    Export: Exports the cleaned dataset to a CSV file.

Story Three Script:

    Dataset Exploration: Loads the cleaned dataset and converts the date column to datetime format.
    Daily Sales over Time: Visualizes daily sales over time, identifies outliers, and adjusts the dataset accordingly.
    Celebrations Analysis: Maps the sales data with holidays to identify patterns and potential reasons for spikes in demand. The holidays are categorized into "Restricted and Gazetted" and "Public Holidays" based on their significance.

Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
