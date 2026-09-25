# Jumia-Project
# Jumia Product Performance Dashboard

## 📊 Project Overview

This project analyzes Jumia product data to understand product performance, pricing, discounts, customer ratings, and customer reviews.

The main objective was to clean and analyze the dataset, identify important patterns, and create an interactive Excel dashboard that can help users understand product performance and make data-driven observations.

## 🎯 Project Objectives

The project focused on:

* Cleaning and preparing the Jumia product dataset
* Checking the dataset for missing values, duplicates, and data quality issues
* Analyzing product prices and discounts
* Analyzing customer ratings and reviews
* Identifying the top-performing products
* Examining relationships between:

  * Discount percentage and reviews
  * Ratings and reviews
  * Product price and ratings
* Creating product categories based on ratings, discounts, and prices
* Building an interactive Excel dashboard
* Providing business insights and recommendations

## 🗂️ Dataset

The dataset contains information about Jumia products, including:

* Product name
* Current price
* Old price
* Discount amount
* Discount percentage
* Customer reviews
* Customer ratings
* Rating category
* Discount category
* Price category

## 🛠️ Tools Used

* **Microsoft Excel**

  * Data cleaning
  * Data validation
  * Formulas
  * Sorting and filtering
  * PivotTables
  * PivotCharts
  * Slicers
  * Data visualization
  * Correlation analysis

* **GitHub**

  * Project documentation
  * Version control
  * Portfolio presentation

## 🔍 Data Cleaning

Before analyzing the data, several data-quality checks were performed.

These included:

1. Checking the number of rows and columns
2. Identifying missing values
3. Checking for duplicate records
4. Checking spelling and consistency
5. Checking numerical values
6. Checking rating values
7. Checking review values
8. Checking discount and price calculations
9. Creating appropriate categories for analysis

The purpose of this step was to make the dataset more reliable before creating the dashboard.

## 📈 Key Analysis

### 1. Product Ratings

The products were analyzed based on their customer ratings to identify highly rated products.

The top-rated products included products with ratings of **5.0**, followed by products with ratings of **4.8** and **4.7**.

### 2. Customer Reviews

Products were also ranked according to the number of customer reviews.

The product with the highest number of reviews in the dataset was:

**120W Cordless Vacuum Cleaners Handheld Electric Vacuum Cleaner — 69 reviews**

Other highly reviewed products included cake decorating tools, digital measuring equipment, and shower curtains.

### 3. Discounts

Products were analyzed according to their discount percentages.

The highest discounts in the dataset reached approximately **64%**.

### 4. Discount vs Reviews

A scatter plot was used to investigate the relationship between discount percentage and the number of reviews.

The correlation calculated from the dataset was approximately:

**-0.137**

This indicates a **weak negative linear relationship** between discount percentage and number of reviews in this dataset.

This does not mean that discounts cause fewer reviews. It only describes the relationship observed in the available data.

### 5. Rating vs Reviews

The correlation between rating and number of reviews was approximately:

**0.057**

This indicates a **very weak positive relationship** between the two variables.

### 6. Price vs Rating

The correlation between current price and rating was approximately:

**0.110**

This indicates a **weak positive relationship** between price and rating in the dataset.

## 📊 Dashboard

The final dashboard contains key performance indicators and visualizations covering:

* Total number of products
* Average current price
* Average discount
* Average rating
* Total reviews
* Top 10 products by rating
* Top 10 products by reviews
* Top 10 products by discount
* Product category analysis
* Discount analysis
* Rating analysis
* Relationship analysis

### Interactive Features

Slicers were added to make the dashboard interactive.

Users can filter the dashboard using:

* **Rating Category**
* **Discount Category**
* **Price Category**

These filters allow users to explore different sections of the dataset without manually filtering the original data.

## 💡 Key Insights

Some observations from the analysis include:

* High discounts were not strongly associated with higher numbers of reviews.
* Customer ratings and review counts showed very little linear relationship.
* Product price had only a weak relationship with customer ratings.
* Some products received high ratings despite having relatively few reviews.
* Some highly reviewed products did not necessarily have the highest ratings.
* Large discounts do not automatically indicate strong customer satisfaction.

These observations demonstrate why multiple variables should be considered when evaluating product performance rather than relying on a single metric.

## 📌 Recommendations

Based on the analysis, businesses could:

* Monitor both ratings and review volumes when evaluating products.
* Avoid using discount percentage alone as a measure of product performance.
* Investigate highly reviewed products with relatively low ratings.
* Identify highly rated products with low review volumes for further promotion or visibility.
* Continue monitoring price, discount, ratings, and reviews together to understand product performance.

## 📁 Project Files

The repository contains:

```text
Jumia-Product-Performance/
│
├── README.md
├── Jumia_Product_Performance_Dashboard.xlsx
├── Excel_jumia_dataset.csv
└── images/
    └── dashboard.png
```

## 🚀 Learning Outcomes

Through this project, I developed practical experience in:

* Excel data cleaning
* Data quality checks
* Excel formulas
* Data analysis
* Correlation analysis
* PivotTables
* PivotCharts
* Interactive dashboards
* Data visualization
* Business insights
* GitHub project documentation

This project is part of my journey toward developing practical skills in **data analytics, statistics, and data science**.

## 👤 Author

**Yop Gony**


