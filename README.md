# Chicago Crime Analysis
This project involves analyzing crime data from Chicago using Jupyter Notebook and Python. The dataset spans multiple years, from 2001 to 2017, and contains information about various crimes reported in the city.

## Prophet Model
- Install fbprophet package as follows: ```pip install prophet```
- Prophet is an open source software released by Facebook's Core Data Science Team.
- Used for forecasting time series data based on additive model when non-linear trends are fit with yearly, weekly and daily seasonality.

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
The Chicago Crime dataset contains a summary of the reported crimes occurred in the City of Chicago from 2001 to 2017. 
Dataset has been obtained from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system.
Dataset contains the following columns: 
    - ID: Unique identifier for the record.
    - Case Number: The Chicago Police Department RD Number (Records Division Number), which is unique to the incident.
    - Date: Date when the incident occurred.
    - Block: address where the incident occurred
    - IUCR: The Illinois Unifrom Crime Reporting code.
    - Primary Type: The primary description of the IUCR code.
    - Description: The secondary description of the IUCR code, a subcategory of the primary description.
    - Location Description: Description of the location where the incident occurred.
    - Arrest: Indicates whether an arrest was made.
    - Domestic: Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.
    - Beat: Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police beat car. 
    - District: Indicates the police district where the incident occurred. 
    - Ward: The ward (City Council district) where the incident occurred. 
    - Community Area: Indicates the community area where the incident occurred. Chicago has 77 community areas. 
    - FBI Code: Indicates the crime classification as outlined in the FBI's National Incident-Based Reporting System (NIBRS). 
    - X Coordinate: The x coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection. 
    - Y Coordinate: The y coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection. 
    - Year: Year the incident occurred.
    - Updated On: Date and time the record was last updated.
    - Latitude: The latitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
    - Longitude: The longitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
    - Location: The location where the incident occurred in a format that allows for creation of maps and other geographic operations on this data portal. This location is shifted from the actual location for partial redaction but falls on the same block.
Datasource: https://www.kaggle.com/currie32/crimes-in-chicago
  
The dataset comprises several CSV files for different time periods:

1. Chicago_Crimes_2001_to_2004.csv
2. Chicago_Crimes_2005_to_2007.csv
3. Chicago_Crimes_2008_to_2011.csv
4. Chicago_Crimes_2012_to_2017.csv



## Usage
1. Clone the repository:
   ```
   git clone https://github.com/Devansh-Gupta-Official/facebook-prophet-chicagocrime.git
   ```
2. Install necessary Python dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook (code.ipynb) using Jupyter or any compatible environment.

## Data Import and Preprocessing
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


## Conclusion
The analysis provides insights into the trends and patterns of crimes reported in Chicago over the years, aiding in understanding the dynamics and possibly helping in future crime rate predictions.
