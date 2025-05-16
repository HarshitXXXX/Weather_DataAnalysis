Weather Data Analysis Project
Overview
This project involves analyzing a weather dataset using Python and Pandas. The dataset contains hourly weather information for a specific location in 2012, including variables such as temperature, dew point temperature, relative humidity, wind speed, visibility, pressure, and weather conditions. The goal is to explore and answer specific questions about the dataset using Pandas DataFrame operations.
This project is part of a broader exploration of Big Data Analysis and serves as a beginner-friendly introduction to data analysis with Python.
Dataset
The dataset used in this project is Weather Dataset.csv, a time-series dataset with the following columns:

Date/Time: Date and time of the record (format: MM/DD/YYYY HH:MM)
Temp_C: Temperature in Celsius
Dew Point Temp_C: Dew point temperature in Celsius
Rel Hum_%: Relative humidity percentage
Wind Speed_km/h: Wind speed in kilometers per hour
Visibility_km: Visibility in kilometers
Press_kPa: Atmospheric pressure in kilopascals
Weather: Weather condition (e.g., Clear, Fog, Rain)

The dataset contains 8,784 rows, representing hourly data for the entire year of 2012.
Project Objectives
The Jupyter Notebook (Weather_data_analysis.ipynb) demonstrates how to:

Load and inspect the dataset using Pandas.
Perform exploratory data analysis (EDA) using methods like .head(), .shape, .dtypes, .unique(), .nunique(), .count(), .value_counts(), and .info().
Answer specific questions about the dataset, such as:
Finding all unique wind speed values.
Counting the number of times the weather is exactly "Clear."
Identifying instances where the weather is "Clear" and relative humidity is greater than 50%, or visibility is above 40 km.



Requirements
To run this project, you need the following:

Python 3.8 or higher
Jupyter Notebook or JupyterLab
Pandas library (pip install pandas)

Optional for visualization (not included in the current notebook but useful for extensions):

Matplotlib (pip install matplotlib)
Seaborn (pip install seaborn)

Setup Instructions

Clone the Repository:
git clone https://github.com/your-username/weather-data-analysis.git
cd weather-data-analysis


Install Dependencies:Ensure you have Python installed, then install the required libraries:
pip install pandas


Place the Dataset:

Download the Weather Dataset.csv file (not included in the repository due to size or availability).
Place it in the same directory as the Jupyter Notebook or update the file path in the notebook's pd.read_csv() function to match the location of your dataset.


Run the Notebook:Launch Jupyter Notebook:
jupyter notebook

Open Weather_data_analysis.ipynb and run the cells sequentially to perform the analysis.


Usage

Open the Weather_data_analysis.ipynb file in Jupyter Notebook.
Follow the code and markdown cells to understand the dataset and analysis steps.
Modify the code to explore additional questions or visualize the data (e.g., plotting temperature trends or weather condition distributions).

Analysis Highlights
The notebook answers the following questions:

Unique Wind Speed Values: Lists all unique wind speed values in the dataset (34 unique values).
Clear Weather Instances: Counts occurrences where the weather is exactly "Clear" (1,326 instances).
Specific Conditions: Identifies records where:
Weather is "Clear" and relative humidity is greater than 50%, or
Visibility is above 40 km (2,921 instances).



Additional Pandas operations demonstrated:

Viewing the first few rows (.head())
Checking dataset shape (.shape)
Listing column names (.columns)
Checking data types (.dtypes)
Counting unique values (.nunique())
Counting non-null values (.count())
Analyzing value frequencies (.value_counts())

Future Improvements

Add visualizations (e.g., temperature trends, weather condition distributions) using Matplotlib or Seaborn.
Perform statistical analysis (e.g., correlations between temperature, humidity, and visibility).
Extend the analysis to include seasonal patterns or predictive modeling using machine learning.

Contributing
Contributions are welcome! If you'd like to add new analyses, visualizations, or improvements:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m "Add feature").
Push to the branch (git push origin feature-branch).
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Author

Harshit Gaikwad

For any questions or suggestions, feel free to open an issue or contact the author via GitHub.
