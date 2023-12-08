# Chicago Crime Analysis
This project involves analyzing crime data from Chicago using Jupyter Notebook and Python. The dataset spans multiple years, from 2001 to 2017, and contains information about various crimes reported in the city.

## Objective
The primary goal of this analysis is to explore the dataset, understand trends, and make predictions using time series analysis.

## Tools and Libraries Used
- Python 3.10
- Jupyter Notebook
- Libraries:
  - Pandas
  - NumPy
  - Seaborn
  - Matplotlib
  - Prophet

## Dataset
The dataset comprises several CSV files for different time periods:

1. Chicago_Crimes_2001_to_2004.csv
2. Chicago_Crimes_2005_to_2007.csv
3. Chicago_Crimes_2008_to_2011.csv
4. Chicago_Crimes_2012_to_2017.csv

## Data Import and PreprocessingDataset
The Jupyter Notebook includes steps for importing the data, handling potential issues (such as deprecated arguments and mixed data types), and initial exploration.

## Exploratory Data Analysis (EDA)
- Analysis of columns and their meanings.
- Handling missing values and unnecessary columns.
- Visualizing crime counts by type and location.

## Time Series Analysis
The project involves time series analysis to understand the trends in crime rates over the years.
### Data Preparation
- Resampling the data to a monthly frequency for time series analysis.
- Preparing the dataset for use in the Prophet library.

### Making Predictions
- Using the Prophet library to make predictions on future crime rates.
- Visualizing the predicted crime rates along with confidence intervals.
