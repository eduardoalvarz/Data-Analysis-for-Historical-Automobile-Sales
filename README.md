# Data Analysis for Historical Automobile Sales

## Introduction
Welcome to the GitHub repository for a data analysis project focused on historical automobile sales. This project utilizes Python and various data visualization libraries to analyze trends in automobile sales, specifically during recession periods.

<img src="https://github.com/eduardoalvarz/Data-Analysis-for-Historical-Automobile-Sales/blob/main/Figures/mapp.PNG" width="400">

## Objectives
1. **Load Data:** Import the historical automobile sales dataset into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA):** Understand key trends and patterns in automobile sales data.
3. **Create Informative Visualizations:** Utilize Matplotlib, Seaborn, and Folium to create visually appealing and insightful plots.
4. **Customize Visualizations:** Tailor visualizations to effectively communicate insights from the data.

## Setup
To run this analysis, make sure you have the following libraries installed:
- `pandas` for data management.
- `numpy` for mathematical operations.
- `matplotlib` and `seaborn` for data visualization.
- `folium` for interactive maps.

```python
%pip install seaborn
%pip install folium
```

## Dataset Description
The dataset comprises "historical_automobile_sales" data, including information on automobile sales, recession periods, GDP, unemployment rate, consumer confidence, and more. The data is sourced from [this URL](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv).

### Variables Overview

| Variable                  | Description                                                                        |
|---------------------------|------------------------------------------------------------------------------------|
| Date                      | The observation date.                                                             |
| Recession                 | A binary variable indicating recession periods; 1 denotes a recession, 0 signifies a normal period. |
| Automobile_Sales          | The number of vehicles sold during the specified period.                             |
| GDP                       | Per capita GDP value in USD.                                                      |
| Unemployment_Rate         | Monthly unemployment rate.                                                        |
| Consumer_Confidence       | A synthetic index reflecting consumer confidence, influencing consumer spending and automobile purchases. |
| Seasonality_Weight        | The weight representing the seasonal effect on automobile sales during the period.  |
| Price                     | The average vehicle price during the specified period.                              |
| Advertising_Expenditure   | The company's advertising expenditure.                                            |
| Vehicle_Type              | The type of vehicles sold, including Supperminicar, Smallfamilycar, Mediumfamilycar, Executivecar, and Sports. |
| Competition               | A measure of market competition, such as the number of competitors or market share of major manufacturers. |
| Month                     | The month of the observation extracted from the date.                               |
| Year                      | The year of the observation extracted from the date.                                |


## Data Analysis Process
1. **Data Import:** Import the dataset and get an overview of the data using descriptive statistics.
2. **Visualization Tasks:** Perform a series of visualization tasks to analyze historical automobile sales trends, recession impact, GDP comparison, seasonality effects, and more.
3. **Insights and Documentation:** Document insights gained from visualizations, providing a narrative that communicates the story behind the data.

## Insight Tasks
- Task 1.1: Yearly Automobile Sales Line Chart
- Task 1.2: Recession Sales Trends by Vehicle Type
- Task 1.3: Seaborn Comparison - Vehicle Sales during Recession vs. Non-Recession
- Task 1.4: GDP Comparison - Recession vs. Non-Recession
- Task 1.5: Seasonality Impact Bubble Plot
- Task 1.6: Matplotlib Scatter - Price vs. Sales Correlation in Recessions
- Task 1.7: Pie Chart - Advertising Expenditure in Recession vs. Non-Recession
- Task 1.8: Pie Chart - Ad Expenditure by Vehicle Type (Recession)
- Task 1.9: Line Plot - Unemployment Rate Impact on Vehicle Sales (Recession)
- Task 1.10: Sales Region Map - Highest during Recession

## Conclusion
This project offers a detailed analysis of historical automobile sales, providing insights into trends during recession periods and visualizing key factors influencing sales. The Jupyter Notebook in this repository contains the code, visualizations, and explanations for each step, making it easy to replicate and understand the analysis.

Feel free to explore the code, adapt it to your specific needs, or reach out if you have any questions or suggestions. Happy analyzing!
