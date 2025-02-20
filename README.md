# Airbnb_data_research

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Airbnb data for Munich to better understand how much you should pay more depends on accommodates
For that it was done for now:

- Distribution of listings by accommodates and distance from the city center.
- Price distribution by accommodates and distance from the city center.
- Correlation analysis between various features and price.
- Average price calculation for different property types.


## File Descriptions <a name="files"></a>

There are 2 notebooks available here to showcase work related to the above questions.
### preprocess.ipynb

This notebook is responsible for preprocessing the raw Airbnb listings data. The main tasks performed in this notebook include:

- Loading the raw data from CSV files.
- Cleaning and transforming the data.
- Calculating additional features such as distance from the city center.
- Filtering relevant property types.
- Saving the processed data to new CSV files.

### analis.ipynb

This notebook performs the analysis on the preprocessed Airbnb listings data. The main tasks performed in this notebook include:

- Loading the processed data from CSV files.
- Analyzing the distribution of listings based on various features.
- Visualizing the data using plots and charts.
- Calculating and comparing prices, reviews, and other metrics.

## Results<a name="results"></a>

The main findings of the code can be found at the post available here: https://www.linkedin.com/pulse/family-travel-digits-what-really-costs-accommodate-5-rastaturin-sw09e

## Licensing, Data, Authors, Acknowledgements<a name="licensing"></a>

Feel free to use the code here as you would like!

Data i took from this page: https://insideairbnb.com/get-the-data/

Particully: https://data.insideairbnb.com/germany/bv/munich/2024-12-27/data/listings.csv.gz

