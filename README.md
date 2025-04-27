# Sales Analysis Project


This Jupyter Notebook (`sales_analize_tamrin_1.ipynb`) performs a sales analysis on a given dataset (`sales.csv`). The analysis includes data transformation, feature engineering, and basic exploratory data analysis to derive insights from the sales data.

## Libraries Used

* **numpy:** For numerical operations and array manipulation.
* **pandas:** For data handling and analysis, particularly using DataFrames.
* **matplotlib.pyplot:** For creating visualizations such as plots and charts.
* **matplotlib.dates:** For handling date-related operations in plots.

## Data Transformation and Feature Engineering

The script performs the following data transformation and feature engineering steps:

1.  **Data Loading:** Reads the sales data from a CSV file (`sales.csv`) into a pandas DataFrame.
2.  **Date Conversion:** Converts the `Date` column to datetime format to facilitate date-based operations.
3.  **Weekday Extraction:** Extracts the day of the week from the `Date` column and creates a new column `day_name` with the days ordered from Sunday to Saturday.
4.  **Season Mapping:** Maps the month of the year to seasons (Winter, Spring, Summer, Autumn) and creates a new column `season`.
5.  **Month Extraction:** Extracts the month name from the `Date` column and creates a new column `month`.

## Exploratory Data Analysis

The script performs basic exploratory data analysis, including:

* **Displaying Sample Data:** Shows the first few rows of the DataFrame and a random sample of 10 rows to get a quick overview of the data.
* **Data Summary:** Provides a summary of the DataFrame including column names, data types, and non-null counts using the `df.info()` method.
* **Daily Sales Average:** Calculates the average daily sales by grouping the data by `Date` and computing the mean `Revenue`.

## Visualizations

* **Daily Sales Trend:** A line plot is generated to visualize the trend of daily sales over time.
* **Sales by Product:** A bar chart is used to compare sales across different products.
* **Sales by Day of Week:** A bar chart is created to analyze sales performance on each day of the week.
* **Sales by Month:** A bar chart illustrates the sales distribution across different months.
* **Sales by Season:** A bar chart compares sales across different seasons.
* **Product Sales Quantity per Weekday:** A bar chart shows the sales quantity for each product per weekday.

## How to Use

1.  **Prerequisites:** Ensure you have Python installed along with the libraries mentioned above (numpy, pandas, matplotlib). You can install them using pip:
    ```bash
    pip install numpy pandas matplotlib
    ```
2.  **Data File:** Make sure the `sales.csv` file is in the same directory as the notebook or provide the correct file path in the script.
3.  **Run the Notebook:** Open the `sales_analize_tamrin_1.ipynb` in Jupyter Notebook or JupyterLab and run the cells sequentially to execute the analysis and generate the visualizations.
# Sales-Analysis
