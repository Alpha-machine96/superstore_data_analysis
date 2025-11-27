# Superstore Data Analysis
__________________________________________________________________________________________________________________________________________

## Project Overview

This project analyzes 4 years of retail sales data (2011-2014) for a superstore, focusing on:

-	Inventory optimization - Identifying fast vs slow-moving products

-	Sales performance - Analyzing trends across categories, regions, and time

-	Profitability analysis - Understanding profit margins and discount impacts

-	Operational efficiency - Evaluating delivery performance and shipping methods

Project Type: Business Analytics | Inventory Management | Data Visualization

Dataset Size: 51,290 transactions

__________________________________________________________________________________________________________________________________________

## Business Problem

**Primary Questions:**

1.	Which products should we stock more of? (Inventory velocity analysis)
   
2.	What discount levels maximize profit? (Pricing strategy)
   
3.	Which regions and categories drive the most revenue? (Resource allocation)
   
4.	How can we reduce inventory holding costs? (ABC analysis)
   
5.	What seasonal patterns exist in sales? (Demand forecasting)
   
**Success Metrics:**

-	Identify top 20% products generating 80% of revenue (ABC Analysis)

-	Optimize discount strategy to improve profit margins by 5-10%

-	Reduce slow-moving inventory by 15%

-	Improve delivery efficiency across shipping methods
________________________________________________________________________________________________________________________________________

## Dataset

**Source**

Synthetic data generated using Python to simulate realistic superstore operations, based on characteristics of the Kaggle Superstore Sales Dataset.

**Description**

-	Rows: 51,290 order records

-	Time Period: January 2011 - October 2014

-	Geographic Coverage: 4 US regions (East, West, Central, South)

-	Product Categories: Furniture, Office Supplies, Technology


**Engineered Features:**

-	Order_Year, Order_Month, Order_Quarter - Temporal features for trend analysis

-	Order_Day_of_Week - Day of week for pattern recognition

-	Delivery duration  - Time between order and shipment

________________________________________________________________________________________________________________________________________

## Key Findings

 **Financial Performance**

-	Total Sales: $12,642,905 over 4 years

-	Total Profit: $1,469,034 (11.6% margin)

 **Inventory Insights**

1.	ABC Analysis: Top 20% of products generate 78% of sales

2.	Fast-Moving Items: Office Supplies have highest turnover

3.	Slow-Moving Items: 15% of products have less than 5 sales total

4.	Category Performance: Technology has highest profit margins (25.3%)

 **Critical Issues**

-	High Discounts = Losses: Discounts >30% consistently result in negative profits

-	Regional Imbalance: West region generates 35% of sales vs South at 18%

-	Seasonal Peaks: Q4 shows 40% increase in sales (holiday shopping)

 **Growth Opportunities**

-	Consumer segment represents 50% of orders but untapped potential in Corporate

-	Same-day shipping has highest customer satisfaction but only 5% adoption

-	Technology category has room for expansion (currently 20% of sales)
__________________________________________________________________________________________________________________________________________

## Technologies Used

**Core Libraries:**

-	Python 3.8+ - Programming language

-	Pandas 1.5.0 - Data manipulation and analysis

-	NumPy 1.23.0 - Numerical computing

-	Matplotlib 3.6.0 - Data visualization

-	Seaborn 0.12.0 - Statistical visualizations

**Development Environment:**

-	Jupyter Notebook - Interactive development

-	Git & GitHub - Version control

-	VS Code - Code editor

**Analysis Techniques:**

-	Descriptive Statistics

-	Time Series Analysis

-	ABC (Pareto) Analysis

-	Correlation Analysis

-	Segmentation Analysis

________________________________________________________________________________________________________________________________________

## Installation & Setup

**Prerequisites**

-	Python 3.8 or higher

-	pip package manager

-	Git (for cloning repository)

**Usage**

Step 1: Clone the Repository

Step 2: Create Virtual Environment (Recommended)

Step 3: Install Dependencies

Step 4: Verify Installation

Step 5: Run (Using Jupyter Notebook preferably)
__________________________________________________________________________________________________________________________________________

## Methodology

1. **Data Generation**

Obtained data for project from Kaggle 

Link: https://www.kaggle.com/datasets/aditisaxena20/superstore-sales-dataset

2. **Data Cleaning**

- Checked for missing values (None found)

- Verified data types and conversions

- Created temporal features from dates

- Validated logical consistency

- Calculated derived metrics

3. **Exploratory Data Analysis**

- Univariate Analysis: Distribution of individual variables

- Bivariate Analysis: Relationships between pairs of variables

- Multivariate Analysis: Complex interactions

- Temporal Analysis: Trends over time

- Segmentation: Performance by categories, regions, segments

4. **Visualization**

- Created different professional charts across several dashboards

- Used appropriate chart types for each insight

- Applied consistent styling and color schemes

- Ensured accessibility and readability

5. **Insight Generation**

- Synthesized findings from all analyses

- Prioritized by business impact

- Developed actionable recommendations

- Validated with data evidence

____________________________________________________________________________________________________________________________________________________________________

## Insights & Recommendations

 **Strategic Recommendations**

1. **Inventory Optimization**

      **Finding:** 20% of products generate 80% of sales (ABC Analysis)
      
      **Recommendations:**
      
   - Category A Products (High Priority):
      
      Maintain higher stock levels
      
      Never allow stockouts
      
      Monitor daily
      
      Priority placement in warehouse
      
      
   - Category C Products (Low Priority):
      
      Minimize inventory
      
      Consider discontinuing poor performers
      
      Order only on demand
      
      Clearance sales for slow movers


2. **Discount Strategy Reform**

      **Finding:** Discounts >25% result in losses
      
      **Recommendations:**
      
     - Cap maximum discount at 25%
      
     - Limit high discounts to:
      
     - Clearance of slow-moving inventory
      
     - Bulk orders (>10 units)
      
     - End-of-season sales
      
     - Optimal discount range: 10-15% (maintains profitability)
      
     - Implement dynamic pricing based on inventory age

3. **Regional Resource Allocation**

      **Finding:** West region generates 35% of sales
      
      **Recommendations:**
      
     - Increase inventory allocation to West region (currently underserved)
      
     - Consider opening regional distribution center
      
     - Allocate more marketing budget to high-performing regions
      
     - Study South region's underperformance (only 18% of sales)

4. **Category Expansion**

      **Finding:** Technology has highest profit margin (25.3%) but lowest sales volume
      
      **Recommendations:**
      
     - Expand Technology product line
      
     - Increase marketing for tech products
      
     - Bundle tech accessories with main products
      
     - Train sales team on tech product benefits

5. **Shipping Optimization**

      **Finding:** Same-day shipping has 5% adoption but highest satisfaction
      
      **Recommendations:**
      
     - Promote same-day shipping option
      
     - Offer incentives for faster shipping (customer loyalty)
      
     - Negotiate better rates with carriers
      
     - Optimize warehouse locations for faster delivery

6. **Seasonal Inventory Planning**

      **Finding:** Q4 sales increase by 40%
      
      **Recommendations:**
      
     - Build inventory 2 months before Q4 (August-September)
      
     - Hire seasonal staff in advance
      
     - Negotiate bulk discounts with suppliers
      
     - Prepare marketing campaigns early

___________________________________________________________________________________________________________________________________________________________________________

##Thank you for viewing this project!            










