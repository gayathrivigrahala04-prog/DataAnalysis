# Sales Data Analysis Using Pandas

## Project Overview

This project analyzes sales data using Python, Pandas, and Matplotlib. The goal is to explore the dataset, generate useful insights, and visualize sales performance across different products and regions.

## Objective

* Load and analyze sales data from a CSV file.
* Perform exploratory data analysis (EDA).
* Calculate sales statistics.
* Generate product-wise and region-wise sales summaries.
* Create visualizations for better understanding of the data.

## Tools Used

* Python
* Pandas
* Matplotlib
* Google Colab / Jupyter Notebook

## Dataset

The dataset contains the following columns:

| Column  | Description  |
| ------- | ------------ |
| Product | Product name |
| Region  | Sales region |
| Sales   | Sales amount |

## Analysis Performed

1. Loaded the dataset using Pandas.
2. Examined the dataset structure using:

   * `head()`
   * `info()`
   * `describe()`
3. Calculated:

   * Total Sales
   * Average Sales
   * Maximum Sales
   * Minimum Sales
4. Performed product-wise sales analysis using `groupby()`.
5. Performed region-wise sales analysis using `groupby()`.
6. Generated charts for data visualization.

## Visualizations

* Bar Chart: Sales by Product
* Bar Chart: Sales by Region
* Pie Chart: Product Sales Distribution

## Key Insights

* Laptop is the highest-selling product.
* North region generated the highest sales revenue.
* Mouse recorded the lowest sales among the products.
* Sales revenue is largely driven by Laptop sales.

## Conclusion

This project demonstrates the use of Pandas for data analysis and Matplotlib for visualization. The analysis helps identify top-performing products and regions, providing valuable business insights.