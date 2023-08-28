# data_wrangling_function

# Mexico City Real Estate Data Cleaning

This project focuses on cleaning and wrangling real estate data for Mexico City. The goal is to prepare a clean dataset that can be used for analysis and machine learning modelling.

## Data

The original data consists of 5 CSV files containing information on real estate listings in Mexico City, including:

- Price 
- Location (latitude, longitude)
- Size (total area and covered area)
- Number of rooms
- Neighborhood

## Data Cleaning

The Python notebook `real_estate_data_cleaning.ipynb` documents the process of cleaning and wrangling the data. The key steps include:

- Subsetting the data to focus only on apartments under $400,000 in Distrito Federal
- Handling outliers in the covered area column 
- Splitting the latitude and longitude into separate columns
- Creating a neighborhood column from the location data
- Dropping unnecessary, high-cardinality, null, and duplicate columns

## Output

The result is a clean CSV file `mexico-city-real-estate-clean.csv` containing preprocessed data ready for analysis and modelling.

## Usage

The notebook provides a clear record of the data-cleaning process. The cleaned CSV file can be loaded for any future real estate modelling or analysis.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
