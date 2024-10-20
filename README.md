# Sales Data Analysis and Forecasting Project

## Overview
This project analyzes a sales dataset to identify trends, answer key business questions, and provide forecasts to support business decision-making. The analysis aims to offer insights into sales performance across different regions and product categories and predict future sales trends using machine learning models.

## Objectives
- Understand sales performance and profitability across regions and product categories.
- Forecast future sales trends using linear regression.
- Provide actionable insights for improving business strategies and optimizing performance.

## Project Structure
- `data/`: Contains the sales dataset (`sales_data.csv` or similar format).
- `notebooks/`: Jupyter notebooks with data exploration, visualization, and forecasting.
- `visualizations/`: Generated graphs and plots showcasing the analysis and forecast results.
- `models/`: Trained models for forecasting future sales trends.

## Tools and Libraries Used
- **Python Libraries**: Pandas, Matplotlib, Seaborn, Scikit-learn, Statsmodels
- **Environment**: Jupyter Notebook
- **Data Visualization**: Matplotlib and Seaborn for visualizing sales trends and KPIs
- **Forecasting**: Linear Regression for predicting sales growth

## Data Cleaning and Exploration
1. **Data Loading**: The sales data was loaded and structured into a DataFrame.
2. **Data Formatting**: Date columns were converted to datetime formats, and the dataset was indexed based on the date.
3. **Missing Values Handling**: Checked and cleaned missing values to ensure the dataset's integrity.
4. **Statistical Summary**: Provided statistical details and visualizations (boxplots, histograms) to understand the distribution of sales and profits.

## Forecasting Methodology
- **Linear Regression**: Used to predict future sales based on past data trends.
- **Time Series Decomposition**: Applied to analyze seasonality, trend, and residual components.
- **Model Evaluation**: Compared actual vs. predicted sales using visual plots to assess model accuracy.

## Visualization
- Visualized key performance indicators (KPIs) such as:
  - **Sales Trends Over Time**: Line charts showing weekly and monthly sales.
  - **Regional Sales Performance**: Maps and bar charts highlighting sales performance across different regions.
  - **Sales and Profit by Category**: Comparison plots for product subcategories.

## Key Insights
- **High-Performing Regions**: Certain regions like California showed consistently high sales.
- **Product Subcategories**: Some categories (e.g., copiers) performed well, while others (e.g., tables) indicated low profitability.
- **Sales Correlation**: Positive correlation between sales and discounts.

## Recommendations
- Focus marketing efforts on high-performing regions and customer acquisition.
- Explore strategies to optimize costs in underperforming categories.
- Monitor sales trends regularly to adapt to emerging challenges.

## How to Run the Project
1. Clone the repository: 
