## 🛒 E-commerce Sales Data Analysis with Dask

## 📌 Project Overview

The **E-commerce Sales Data Analysis with Dask** project focuses on processing and analyzing a large dataset of sales transactions from an e-commerce platform. 

This project was completed as part of a 6-week internship at Codtech IT Solutions in the **Data Analytics** domain. 

The primary goal was to gain insights from big data using **Dask**, a parallel computing library in Python, capable of handling datasets larger than memory.

E-commerce platforms generate large volumes of data from customer interactions, product transactions, pricing changes, and inventory movements.

Processing and analyzing such data using traditional pandas methods often results in performance bottlenecks due to memory constraints. 

This project overcomes these limitations using **Dask**, enabling distributed computing and out-of-core processing to derive insights efficiently.

![image](https://github.com/user-attachments/assets/45088028-9b53-4cbd-95f8-4d7cac873881)

## 🎯 Objectives

- To explore, clean, and analyze a large e-commerce sales dataset.

- To use Dask for high-performance and scalable data processing.

- To identify key sales trends, customer behavior patterns, and product performance.

- To visualize key insights that help in data-driven decision-making.

## 🔍 Key Features and Analysis

- **Data Loading with Dask**: Leveraged Dask DataFrames to load and explore large CSV files efficiently, parallelizing operations for faster processing.

- **Data Cleaning**: Handled null values, removed duplicates, parsed dates, and standardized data types for better analysis.

- **Sales Analysis**:

  - Monthly and daily revenue tracking.

  - Best-selling products and categories.

  - City-wise and region-wise sales performance.

- **Customer Behavior Analysis**:

  - Repeat purchase trends.

  - Peak shopping hours and days.

  - Average order value and purchase frequency.

- **Time Series Analysis**: Identified trends and seasonality in the sales data using resampling and rolling mean methods.

- **Visualizations**: Used `matplotlib` and `seaborn` for insightful plots, including bar graphs, time series line charts, and heatmaps to illustrate sales and customer trends.

## 🛠️ Technologies Used

- **Python**

- **Dask**

- **Pandas**

- **Matplotlib**

- **Seaborn**

- **Jupyter Notebook**

## 📁 Project Structure

├── Big_Data_Analysis.ipynb # Jupyter Notebook with all analysis steps

├── ecommerce_sales_data.csv # Raw e-commerce sales dataset

├── README.md # Project documentation
