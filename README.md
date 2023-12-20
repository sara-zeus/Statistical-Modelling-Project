# Final Project: Statistical Modelling with Python

## Project/Goals

The goal is to analyze bike rental station data from Vancouver and nearby points of interest. This involves building a dataset and a statistical model (using linear regression with the `statsmodel` module in Python) to unveil the relationship between the number of bikes available for rental at each station and the characteristics of nearby points of interest.

### Subgoals:

- Query 3 different APIs using Python and parse JSON data into Pandas dataframes.
- Manipulate, clean, and pivot dataframes for analysis using Pandas.
- Utilize `matplotlib` and `seaborn` modules to create visualizations for Exploratory Data Analysis (EDA) and aid in building the regression model.
- Create a local SQLite file database and store dataframe data within it using the `sqlite3` module.
- Employ the `statsmodel` module to develop multivariate linear regression models, assess feature inclusion, and evaluate and interpret the results.

## Process

### Preparation: Analysis/Examination of APIs

Before accessing the APIs, several factors were considered:
- Number of free API calls available in the "free tier" for each API.
- Authorization types required for each API.
- API call limit reset frequency and timing.

### API Calls

1. Call citybikes API (2 endpoints) to retrieve information about bike stations in Vancouver.
2. Call Yelp API (Businesses Search endpoint) to gather information about points of interest within 1 km of each bike station.
3. Call Foursquare API (Place Search endpoint) to collect information about points of interest within 1 km of each bike station.

### Initial EDA for Data Cleaning

Perform data cleaning and validation on the returned data for all 3 dataframes.

### Data Transformation for Model Building

- Join various dataframes for further investigation and graphing.
- Pivot and "collapse" dataframes to obtain aggregated data suitable for model building/linear regression.

### Write Dataframe to SQLite Database

Create a local SQLite DB and table to hold dataframe information, then insert rows into the table and confirm completeness.

### Build Statistical Model and Interpret Results

- Employ model evaluation methods to determine which features to include.
- Create a linear regression model with appropriate features.
- Evaluate Adjusted R-squared, p-values, and interpret the results.

## Results

Findings from the statistical model:
- Certain types of points of interest from Foursquare and the minimum distance to the nearest point of interest do not strongly predict the number of rental slots in a bike station.
- The impactful features identified are:
  - Number of POIs with "outdoor" characteristics within 1 km radius from bike station (coefficient: 0.6735, p-value: 9.162179e-07).
  - Number of POIs with "snack" characteristics within 1 km radius from bike station (coefficient: -0.0496, p-value: 0.015).

## Challenges

The primary challenges faced were time constraints and API call limits, particularly with regards to:

- Time allocation for project completion.
- API call limitations and their impact on data collection and analysis.

## Future Goals

With more time, potential future areas of exploration include:

- Analyzing the correlation between the operating company of bike stations and their characteristics.
- Evaluating the predictive capability resulting from features in the Yelp dataset (number of ratings, average rating).
- Collecting more comprehensive data regarding bike utilization and points of interest, considering seasonal changes and optimizing API calls.
