# Weather Data Analysis

## Overview
This project involves analyzing a time-series weather dataset using Python and the Pandas library. The dataset contains hourly weather conditions at a specific location, including temperature, dew point temperature, relative humidity, wind speed, visibility, pressure, and weather conditions. The analysis explores the dataset through various Pandas operations to answer specific questions about the data.

## Dataset
The dataset (`Weather Dataset.csv`) is a time-series dataset with the following columns:
- **Date/Time**: Date and time of the observation
- **Temp_C**: Temperature in Celsius
- **Dew Point Temp_C**: Dew point temperature in Celsius
- **Rel Hum_%**: Relative humidity percentage
- **Wind Speed_km/h**: Wind speed in kilometers per hour
- **Visibility_km**: Visibility in kilometers
- **Press_kPa**: Atmospheric pressure in kilopascals
- **Weather**: Weather condition (e.g., Clear, Fog, Rain)

The dataset contains 8,784 rows, covering hourly observations for the year 2012.

## Prerequisites
To run this project, you need the following:
- **Python**: Version 3.6 or higher
- **Libraries**:
  - `pandas`
- **Jupyter Notebook**: To execute the provided `.ipynb` file
- **Dataset**: `Weather Dataset.csv` (not included in this repository; provide your own or use a similar dataset)

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. **Set Up a Virtual Environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install pandas jupyter
   ```

4. **Place the Dataset**:
   - Ensure `Weather Dataset.csv` is available in the project directory or update the file path in the notebook (`Weather_data_analysis.ipynb`) to match the location of your dataset.

## Usage
1. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook Weather_data_analysis.ipynb
   ```

2. **Run the Notebook**:
   - Execute the cells sequentially to load the dataset and perform the analysis.
   - The notebook includes exploratory data analysis (EDA) steps, such as:
     - Viewing the dataset structure (`.head()`, `.shape`, `.info()`)
     - Finding unique values (`.unique()`, `.nunique()`)
     - Counting occurrences (`.value_counts()`, `.count()`)
     - Answering specific questions, such as:
       - Unique wind speed values
       - Number of times the weather is exactly "Clear"
       - Instances where weather is "Clear" with relative humidity > 50% or visibility > 40 km

3. **Modify the Analysis**:
   - Adjust the code to explore other questions or add visualizations (e.g., using Matplotlib or Seaborn for plots).
   - Update the file path in the `pd.read_csv()` function if your dataset is located elsewhere.

## Analysis Questions Answered
The notebook addresses the following questions:
1. Find all unique wind speed values in the data.
2. Find the number of times the weather is exactly "Clear."
3. Find instances when:
   - Weather is "Clear" and relative humidity is greater than 50%, **or**
   - Visibility is above 40 km.

## Notes
- The dataset file path in the notebook (`C:\\Users\\ROHIT GREWAL\\...`) is specific to the original author's environment. Update it to match your local setup.
- The column name in the dataset is `Weather`, but some cells reference `Weather Condition`. Ensure consistency in column names (e.g., rename the column to `Weather Condition` or update the code to use `Weather`).
- To extend the analysis, consider adding visualizations or statistical summaries (e.g., mean temperature, correlation between variables).

## Contributing
Contributions are welcome! Please:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.


## Author
- Harshit Gaikwad
