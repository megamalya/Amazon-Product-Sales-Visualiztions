# Amazon Electronics Sales & Product Insights Project
Project Overview

This project analyzes the Amazon Electronics Products Sales Dataset to gain insights into product performance, pricing strategy, customer satisfaction, and category-level trends. Data cleaning and analysis were performed in Python, while the final visualizations and interactive dashboard were created in Tableau.

Objectives

> Analyze sales performance and product popularity.

> Evaluate pricing strategy and discount impact.

> Measure customer satisfaction through ratings and reviews.

> Identify high-performing and underperforming products.

Dataset Details

Source: https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset

Visualization Details

Source: https://public.tableau.com/views/AmazonElectronicsSalesAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Data Cleaning Process (Python)

--> Removed duplicate product IDs.

--> Handled missing values.

--> Standardized column names.

--> Converted data types for consistency.

--> Created new calculated fields like Discounted Price.

--> Key Performance Indicators (KPIs)

Sales Performance Analysis:

* Top 10 Most Reviewed Products

* Top 5 Highest Rated Products

Pricing Strategy Analysis:

* Average Price by Category

* Discount Percentage Impact on Reviews

Customer Satisfaction Metrics:

* Average Rating by Category

* High Review, Low Rating Products

Category-Level Insights:

* Total Reviews by Category

* Value-for-Money Categories (High Rating & Low Price)

Dashboard Layout (Tableau)

1.Sales Performance Sheet: Product-level performance metrics.

2.Pricing Strategy Sheet: Price and discount analysis.

3.Customer Satisfaction Sheet: Ratings and reviews overview.

4.Category Insights Sheet: Aggregated data by product category.

5.Combined Dashboard: An interactive view of all sheets with filters and highlights.

Visualizations (Python)

1.Bar charts for average price, rating, and discount by category.

2.Count plots for top-reviewed and highly-rated products.

3.Scatter plots to show the impact of discounts on reviews.

Insights & Findings

* High-discount products often attract more reviews.

* Some well-rated products have fewer reviews, highlighting hidden gems.

* Categories like "Computers & Accessories" show strong performance across multiple metrics.

* Discount percentage has a noticeable impact on review count but not always on ratings.

Future Scope

> Include revenue and order data for deeper sales analysis.

> Sentiment analysis on product reviews.

> Predictive modeling for product performance based on current metrics.

How to Run the Project

1.Clean and analyze data using Python scripts.

2.Export cleaned data to a CSV file.

4.Load cleaned data into Tableau.

5.Build visualizations and combine them into a single interactive dashboard.

Tools Used

Python: Pandas, NumPy, Matplotlib, Seaborn

Tableau: Interactive visualizations and dashboard creation

Conclusion

This project provides a holistic view of Amazon’s electronics product performance and pricing strategy. By combining Python’s data analysis power with Tableau’s interactive capabilities, the dashboard enables data-driven decision-making for product managers and business stakeholders.
