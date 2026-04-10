# Sales Data Analysis

## Project description

This project analyzes global sales data of a company operating in both offline and online markets. The goal was to clean the data, combine multiple datasets, and extract meaningful business insights.

## Dataset

The dataset consists of three tables:

* `events.csv` — sales data over several years
* `products.csv` — product categories and product codes
* `countries.csv` — countries and regions

## Tech stack

* Python
* numpy
* pandas
* matplotlib
* seaborn
  

## Data preparation

* Handled missing values
* Fixed incorrect data types
* Removed duplicates
* Merged datasets into a single dataframe

## Analysis

* Calculated key business metrics (total orders, revenue, number of countries)
* Analyzed sales by product categories, regions, and sales channels
* Studied delivery time and its impact on profit
* Analyzed sales trends over time
* Explored seasonality and weekday patterns

## Key insights

* Identified top-performing product categories
* Found differences in performance across regions
* Observed relationship between delivery time and profit
* Detected seasonal patterns in sales

## Project structure

* `data/` — raw data (events, products, countries)
* `notebooks/sales_analysis.ipynb` — full analysis

## How to run

Open and run the notebook in Google Colab or Jupyter Notebook
