# Python---Data-Visualization



## Project Overview

This project focuses on loading, cleaning, and visualizing the Seaborn Taxi dataset using Python. It demonstrates how different data visualization techniques can be used to understand taxi fares, trip distances, tips, payment methods, and relationships between numerical variables.

## Objectives

- Load and explore the Taxi dataset.
- Identify and handle missing values.
- Create visualizations using Matplotlib, Pandas, and Seaborn.
- Analyze fare distributions, trip counts, and relationships between variables.
- Interpret the visualizations to understand patterns in the data.

## Dataset

- **Dataset name:** Taxis
- **Source:** Seaborn built-in dataset
- **Loading method:** `sns.load_dataset("taxis")`
- **Key columns:** `pickup`, `dropoff`, `distance`, `fare`, `tip`, `tolls`, `total`, `payment`, `pickup_zone`, and `pickup_borough`.

## Tools and Libraries

- **Python** — programming language used for analysis.
- **Pandas** — data manipulation and cleaning.
- **Seaborn** — statistical data visualization.
- **Matplotlib** — chart creation and customization.

## Project Workflow

### 1. Import Libraries and Load Data

Imported the required Python libraries and loaded the Taxi dataset into a Pandas DataFrame for analysis.

### 2. Data Exploration

Checked the dataset structure, column data types, and missing-value counts using functions such as `head()`, `dtypes`, and `isnull().sum()`.

### 3. Handling Missing Values

- Used `mode()` to identify the most frequently occurring values in categorical columns.
- Filled missing values in the `payment` column using mode imputation with `fillna()`.
- Removed rows with missing values in `pickup_zone`, `dropoff_zone`, `pickup_borough`, and `dropoff_borough` using `dropna()`.
- Verified the result by checking missing-value counts again.

### 4. Data Visualization

#### Matplotlib and Pandas Plots

1. **Line Chart:** Visualized taxi fares over time using pickup timestamps.
2. **Bar Chart:** Compared total fares across pickup boroughs.
3. **Pie Chart:** Displayed the distribution of trips by payment method.
4. **Histogram:** Examined the distribution of taxi trip distances.
5. **Box Plot:** Compared tip distributions across pickup boroughs.

#### Seaborn Visualizations

6. **Count Plot:** Compared the number of taxi trips by pickup borough.
7. **Scatter Plot:** Explored the relationship between trip distance and fare, with colors representing pickup boroughs.
8. **Heatmap:** Visualized correlations among distance, fare, tip, tolls, and total.
9. **Pair Plot:** Examined pairwise relationships between distance, fare, tip, and total, colored by pickup zone.
10. **Violin Plot:** Compared fare distributions across payment methods.

## Key Observations

The visualizations help explore the following patterns:

- Differences in total fares across pickup boroughs.
- The distribution of taxi trip distances.
- Differences in tip amounts between boroughs.
- The relationship between trip distance and fare.
- Correlations among numerical trip variables.
- Differences in fare distributions by payment method.


## Conclusion

This project demonstrates the use of Python for basic data cleaning, exploration, and visualization. By combining Matplotlib, Pandas, and Seaborn, the analysis presents taxi data in several visual formats and helps identify patterns in fares, distances, tips, payment methods, and pickup locations.

## Skills Demonstrated

- Python data analysis
- Pandas DataFrame operations
- Missing-value handling
- Data visualization
- Exploratory data analysis (EDA)
- Interpretation of charts and correlations

drive link: https://drive.google.com/file/d/1fwylEXIgOechaykycXNMdcpYWIxMaJlp/view?usp=sharing
