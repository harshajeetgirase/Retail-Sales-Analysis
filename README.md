📌 Project Overview

This project focuses on analyzing retail sales data using Python to extract meaningful business insights. The analysis covers customer behavior, product performance, pricing patterns, and revenue trends. Both Exploratory Data Analysis (EDA) and basic inferential statistics are applied to support data-driven decision-making.

🎯 Objectives

Understand sales patterns across regions, products, and customer groups.

Identify high-performing and low-performing products.

Analyze revenue distribution and detect skewness/outliers.

Use statistical tests to compare groups (e.g., Gender vs Revenue, Region vs Payment Method).

Provide actionable insights for business improvement.

🗂️ Dataset Overview

The dataset contains the following key features:

Customer Information: CustomerID, Gender, City, Region

Product Details: ProductName, Category, SubCategory

Transaction Details: Price, Quantity, Discount, PaymentMethod

Store Details: StoreName, Store_City

Sales Metrics: Revenue, Profit

🛠️ Tools & Technologies

Python

Pandas – data cleaning and manipulation

NumPy – numeric computation

Matplotlib & Seaborn – data visualization

SciPy Stats – statistical testing

Jupyter Notebook – analysis workflow

🔍 Exploratory Data Analysis

Key EDA steps performed:

Handling missing values and duplicates

Summary statistics (mean, median, mode, std)

Revenue and quantity distribution plots

Skewness analysis and log transformation

Category-level and region-level analysis

Outlier detection using IQR

Correlation matrix for numerical features

📊 Statistical Analysis

Applied basic inferential statistics to answer business questions:

Normality Checks: Histogram, KDE plot, Q-Q plot, Shapiro test

Two-Sample t-Test: Compare revenue between genders

Chi-Square Test: Relationship between region and payment method

Variance Analysis: Revenue differences across categories

(Only simple statistical tests used — no advanced non-parametric tests.)

📈 Visualizations

The project includes:

Revenue distribution plots

Region-wise total revenue bar chart

Category-wise performance charts

Correlation heatmap

Payment method distribution

Time-series trend analysis (if date is available)

🧠 Key Insights

Identified the top revenue-generating categories and products

Detected skewness in numerical variables and applied transformations

Found statistically significant differences between customer groups

Highlighted region-level sales disparities and payment preferences

Recommended pricing and product strategy improvements
