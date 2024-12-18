### 3Signet Pharmaceutical

My name is Abah Chekwube David, and I'm a Phyisicist interested in all things about Data Analysis.

This repository contains a pharmaceutical dataset provided by 3Signet LTD. The dataset includes information on various pharmaceutical products, distributors, sales channels, and sales performance.

## Table of Contents

* [Introduction](#introduction)
* [Dataset Description](#dataset-description)
* [Data Dictionary](#data-dictionary)
* [Analysis Breakdown](#analysis-breakdown)
* [Results and Findings](#results-and-findings)
* [Insights and Recommendations](#insights-and-recommendations)
* [Getting Started](#getting-started)
* [Acknowledgments](#acknowledgments)

## Introduction(Problem Statement)

This dataset is provided by 3Signet LTD and contains information on pharmaceutical products, distributors, sales channels, and sales performance. ABC Pharmaceutical Company operates in a highly competitive and regulated market, where understanding the dynamics of sales performance and customer purchasing behavior is crucial.Currently, the company struggles to integrate diverse data sources and cannot perform granular analysis, leading to missed opportunities in targeting key customer segments and optimizing product distribution. This project aims to overcome these challenges by conducting a comprehensive data and geospatial analysis, revealing intricate patterns and correlations. By leveraging advanced analytical techniques, the company can uncover hidden insights, refine marketing strategies, and improve overall operational efficiency. The dataset is intended for generating insights of the organization over a four years period and creating an ACTION PLAN to help business growth.

## Dataset Description

The dataset includes the following columns:

* Distributor
* City
* Country
* Latitude
* Longitude
* Channel
* Sub-channel
* Product Name
* Product Class
* Quantity
* Unit Price
* Sales
* Month
* Year
* Name of Sales Rep
* Manager
* Sales Team

## Data Dictionary

A data dictionary is provided in the [(Dataset)]((https://drive.google.com/file/d/1Mh6NjWYK898-UT1UhEp7gYH5d6jgN0UV/view?usp=drive_link)) file, which describes the variables in the dataset, including their data types and descriptions.

## Analysis Breakdown

The data was given to me in excel, I cleaned the data using POWER QUERY in excel, then I imported my data to sql workbench where I did further cleaning and created a database for my data. Finally, I took my database to Python where I was able to perform other task. Details of the task are as follows

## The Objectives
1. Identify Sales Trends: Uncover trends in sales data over time, including peak periods and
sales dips.
2. Understand Customer Behavior: Examine customer demographics and purchasing patterns
to identify key customer segments and behaviors.
3. Evaluate Product Performance: Assess the performance of different products, identifying
best-sellers and underperforming items.
4. Analyze Geospatial Impact: Understand the impact of geography on sales to identify high
and low-performing regions.
5. Channel Performance: Compare sales performance across different customer channels
(e.g., Hospital vs. Pharmacy).
6. Optimize Sales Strategies: Provide recommendations for improving sales strategies based
on data insights.
7. Enhance Product Offerings: Suggest optimizations for product offerings based on
performance and customer preferences.

## with SQL
I peformed the following after cleaning my data with power Query in excel 
1. Sales Performance Analysis
• Finding the total total sales for each product? (Identify the top-selling products)
• How do sales vary month by month within a specific year? 
2. Sales by Location
• Which cities have the highest total sales? 
• How do sales compare across different countries? 
3. Customer Segmentation
• What is the total sales by customer type?
• How do sales differ across various sectors
4. Product Analysis
• What are the top-selling products within each drug class?
• What is the average price for each class of drugs? (Analyze pricing by product class)
5. Sales Representative Performance
• Who are the top-performing sales representatives based on total sales?
• How does sales performance vary across different sales teams?
6. Time Series Analysis
• What is the year-over-year growth in total sales? (Measure growth trends over the years)
• Which months consistently have the highest sales volume? (Identify seasonal sales
patterns)

## Data Preprocessing, Data Exploration, and Visualization with Python
I went further to
• Import my data using SQLite3 into Python IDE, and perform data
validation to ensure consistency and data quality
• Conduct exploratory data analysis (EDA) to understand data distributions, outliers, and
relationships.
• Analyze sales data by year, product, and region to identify trends and patterns.
• Analyze customer demographics and purchasing patterns to understand customer behavior.
• Analyze product performance and trends, including product lifecycle and sales distribution.
## I also carried out
## Geospatial and Channel Analysis with Python
• Used suitable geospatial library (e.g. geopandas, etc.) and perform geospatial analysis
to understand the impact of geography on sales.
• Analyzed sales performance across different channels (Hospital vs. Pharmacy).
• Evaluated the impact of external factors (e.g., healthcare infrastructure, population density)
on sales.
## Hypothesis Testing and Statistical Analysis
• Used appropriate statistical methods, test hypotheses to confirm or reject the declared
hypotheses.
• Conducted advanced statistical analysis to understand relationships between variables (e.g.,
regression analysis, correlation analysis).
• Interpreted statistical results and provide actionable insights based on findings.

## USED POWER BI in Building Dashboards
• Develop interactive dashboards using Power BI to present key findings in an accessible
format.
• Prepare a comprehensive final presentation for stakeholders, summarizing the project,
methodology, findings, and recommendations.

## Results and Findings

The results and findings of my analysis are presented in the the links 
((https://colab.research.google.com/drive/1SSEC-DNlfgBBKzLDMyPtsEDgBm_5Pvjq?usp=sharing))
((https://colab.research.google.com/drive/11tK-SCHaAeFX9RqXqkk-yFXgNw58rhTU?usp=sharing)) 
((https://colab.research.google.com/drive/1j3MgRQorHynEfa1PFP9fAIxmG8o5HOiM?usp=sharing))
((https://drive.google.com/file/d/1JJNTc0Qfrv-v5F8RtEy7pG8v0GHaB1D1/view?usp=sharing))
((https://drive.google.com/file/d/1sboe0A_FVTH1HS2KUWrfjziBwEYTr_Jz/view?usp=sharing)).

## Insights and Recommendations

Insights and recommendations based on my analysis are presented in the 
((https://drive.google.com/file/d/1owKQZ1WC0Hrs6ol9lv17LXE9jtqII9eB/view?usp=sharing))
((https://drive.google.com/file/d/1owKQZ1WC0Hrs6ol9lv17LXE9jtqII9eB/view?usp=sharing)) file.

## Getting Started

To get started with this dataset, simply clone the repository and explore the data using your preferred data analysis tool.

## Acknowledgments

This dataset was provided by 3Signet LTD. We thank them for their generosity in sharing this data with the public.
