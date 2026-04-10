# Sales Data Analysis

## 📌 Project description

This project analyzes global sales data of a company operating in both offline and online markets. The goal was to clean the data, combine multiple tables, and extract valuable business insights.

## 🗂 Dataset

The dataset consists of three tables:

* `events.csv` — sales data over several years
* `products.csv` — product categories and product codes
* `countries.csv` — countries and regions

## 🛠 Tech stack

* Python
* pandas
* matplotlib / seaborn

## 🔧 Data preparation

* Handled missing values and data inconsistencies
* Fixed data types
* Removed duplicates
* Merged datasets into a single dataframe

## 📊 Analysis

* Calculated key business metrics:

  * total orders
  * total revenue
  * number of countries
* Analyzed sales by:

  * product categories
  * regions and countries
  * sales channels (online/offline)
* Studied delivery time and its impact on profit
* Analyzed sales trends over time
* Checked seasonality and weekday patterns

## 📈 Key insights

* Identified top-performing product categories
* Found differences in performance across regions
* Discovered relationship between delivery time and profit
* Detected seasonal trends in sales

## 📂 Project structure

* `data/` — raw data
* `sales_analysis.ipynb` — full analysis
