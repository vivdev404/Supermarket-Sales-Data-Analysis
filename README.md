# Supermarket Sales Data Analysis

## Project Description

This project provides a comprehensive analysis of supermarket sales data from three different branches over a 3-month period. The dataset contains historical sales records that enable predictive data analytics and business insights. The analysis focuses on understanding sales patterns, customer behavior, product performance, and revenue trends across different branches and time periods.

The project utilizes Python's powerful data analysis libraries to explore, visualize, and extract meaningful insights from the supermarket sales data, helping stakeholders make informed business decisions.

## Project Objectives

1. **Sales Performance Analysis**: Analyze total sales, revenue trends, and performance metrics across different branches
2. **Customer Behavior Analysis**: Understand customer demographics, purchasing patterns, and payment preferences
3. **Product Line Performance**: Evaluate which product categories generate the most revenue and profit
4. **Temporal Analysis**: Identify sales patterns across different time periods (daily, weekly, monthly)
5. **Branch Comparison**: Compare performance metrics across the three different branches (A, B, C)
6. **Payment Method Analysis**: Analyze customer payment preferences and their correlation with purchase amounts
7. **Customer Satisfaction**: Examine customer ratings and their relationship with various factors
8. **Predictive Insights**: Provide data-driven recommendations for business optimization

## Tools Used and Their Usage in Project

### Core Libraries:
- **NumPy**: Used for numerical computations and linear algebra operations on the dataset
- **Pandas**: Primary library for data processing, manipulation, and CSV file I/O operations
- **Matplotlib**: Used for creating static visualizations including bar charts, line plots, and histograms
- **Seaborn**: Advanced statistical data visualization library used for creating attractive and informative plots

### Specific Applications:
- **Data Loading**: Pandas `read_csv()` function to import the supermarket sales dataset
- **Data Cleaning**: Handling missing values, data type conversions, and data validation
- **Statistical Analysis**: Calculating descriptive statistics, correlations, and aggregations
- **Data Visualization**: Creating various charts to represent sales trends, customer demographics, and product performance
- **Time Series Analysis**: Analyzing sales patterns over time using datetime operations

## Project Details and Analysis Results

### Dataset Overview
The dataset contains **1000 sales records** with the following key features:
- **17 columns** including Invoice ID, Branch, City, Customer type, Gender, Product line, Unit price, Quantity, Tax, Total, Date, Time, Payment method, COGS, Gross margin percentage, Gross income, and Rating
- **3 branches** located in Yangon, Mandalay, and Naypyitaw
- **6 product lines**: Health and beauty, Electronic accessories, Home and lifestyle, Sports and travel, Food and beverages, Fashion accessories
- **Time period**: 3 months of sales data (January to March 2019)

### Key Findings and Visualizations

#### 1. Sales Distribution by Branch
![Branch Sales Analysis](analysis_screenshots/branch_sales.png)
- **Branch A (Yangon)**: Highest total sales volume
- **Branch B (Mandalay)**: Moderate performance with consistent sales
- **Branch C (Naypyitaw)**: Competitive performance with strong customer base
- All branches show relatively balanced performance with minor variations

#### 2. Customer Demographics Analysis
![Customer Demographics](analysis_screenshots/customer_demographics.png)
- **Gender Distribution**: Nearly equal split between male and female customers (51% vs 49%)
- **Customer Type**: Balanced distribution between Members (50.1%) and Normal customers (49.9%)
- **Member vs Normal**: Members show slightly higher average purchase amounts

#### 3. Product Line Performance
![Product Performance](analysis_screenshots/product_performance.png)
- **Top Performing Categories**:
  1. Food and beverages: Highest total revenue
  2. Sports and travel: Strong performance in all branches
  3. Electronic accessories: Consistent sales across locations
- **Revenue Distribution**: Relatively even across all six product categories
- **Profit Margins**: Consistent 4.76% gross margin across all products

#### 4. Payment Method Preferences
![Payment Methods](analysis_screenshots/payment_methods.png)
- **Cash**: 34.4% of transactions
- **E-wallet**: 33.6% of transactions  
- **Credit Card**: 32.0% of transactions
- Nearly equal distribution suggests diverse customer payment preferences

#### 5. Time-based Sales Analysis
![Sales Trends](analysis_screenshots/sales_trends.png)
- **Peak Hours**: Sales activity highest during afternoon hours (12 PM - 6 PM)
- **Daily Patterns**: Consistent sales throughout the week with slight weekend variations
- **Monthly Trends**: Steady performance across the three-month period

#### 6. Customer Satisfaction Analysis
![Customer Ratings](analysis_screenshots/ratings_analysis.png)
- **Average Rating**: 6.97 out of 10 across all branches
- **Rating Distribution**: Normal distribution with most ratings between 6-8
- **Branch Comparison**: All branches maintain similar satisfaction levels

### Statistical Insights

#### Revenue Metrics:
- **Total Revenue**: $322,966.75 across all branches
- **Average Transaction**: $322.97 per sale
- **Tax Revenue**: $15,379.37 (5% tax rate)
- **Gross Income**: $15,379.37

#### Performance Indicators:
- **Quantity per Transaction**: Average of 5.51 items
- **Unit Price Range**: $10.08 - $99.96
- **Customer Satisfaction**: 6.97/10 average rating

## Project Conclusion and Learning Outcomes

### Key Business Insights:
1. **Balanced Performance**: All three branches show competitive performance with no significant underperformers
2. **Product Diversification**: Even revenue distribution across product lines indicates successful diversification strategy
3. **Customer Loyalty**: Balanced member vs normal customer ratio suggests effective loyalty programs
4. **Payment Flexibility**: Equal adoption of different payment methods indicates good customer service
5. **Consistent Quality**: Uniform gross margins suggest standardized pricing and cost management

### Technical Learning Outcomes:

#### Data Analysis Skills:
- **Data Manipulation**: Mastered pandas operations for data cleaning, filtering, and aggregation
- **Statistical Analysis**: Applied descriptive statistics and correlation analysis
- **Data Visualization**: Created comprehensive visualizations using matplotlib and seaborn
- **Time Series Analysis**: Analyzed temporal patterns in sales data

#### Programming Proficiency:
- **Python Libraries**: Gained expertise in NumPy, Pandas, Matplotlib, and Seaborn
- **Jupyter Notebooks**: Developed skills in interactive data analysis and documentation
- **Code Organization**: Learned to structure analysis code for reproducibility and clarity

#### Business Intelligence:
- **KPI Development**: Identified and calculated key performance indicators
- **Trend Analysis**: Recognized patterns and trends in business data
- **Reporting**: Created comprehensive reports with actionable insights
- **Data-Driven Decision Making**: Translated analytical findings into business recommendations

### Recommendations for Business Optimization:

1. **Inventory Management**: Maintain balanced stock across all product lines given even performance
2. **Customer Retention**: Develop targeted programs to convert normal customers to members
3. **Peak Hour Optimization**: Ensure adequate staffing during afternoon peak hours
4. **Payment Infrastructure**: Continue supporting all payment methods given balanced usage
5. **Quality Improvement**: Focus on initiatives to improve customer satisfaction ratings above 7.0

### Future Analysis Opportunities:
- **Seasonal Analysis**: Extend analysis to full year data for seasonal patterns
- **Customer Segmentation**: Develop detailed customer personas based on purchasing behavior
- **Predictive Modeling**: Build models to forecast future sales and demand
- **Market Basket Analysis**: Analyze product combinations and cross-selling opportunities
- **Competitive Analysis**: Compare performance with industry benchmarks

This project demonstrates the power of data analytics in understanding business performance and provides a foundation for data-driven decision making in retail operations.
