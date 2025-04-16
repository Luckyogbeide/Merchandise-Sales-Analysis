# Merchandise Sales Analysis
## Introduction
Lee Chatmen is a popular influencer from the United States with over 7 million TikTok followers. He became famous for his entertaining videos, where he plays popular songs on miniature guitars. In 2023, Lee launched his own line of merchandise. This analysis looks at how his merchandise sales are going and what we can learn from the data.

These questions guided the analysis:
- What are the overall sales trends?
- Which product categories perform the best?
- What are the most and least popular products?
- How does location affect sales performance?
- What impact does international shipping have on sales?
- What is the demographic profile of buyers?
- How do ratings and reviews correlate with sales?

## Key Deliverables
`Customer Persona Profiles:`
- Detailed profiles of target customers based on demographic data, location, and spending patterns.
  
`Low-Performing Region Insights:`
- A clear action plan to penetrate low-performing regions with tailored marketing strategies.
  
`Rating and Review Dashboard:`
- Visualizations of rating trends and actionable insights from review sentiment analysis.
  
`Cost Analysis Report:`
- Recommendations for reducing shipping and operational costs while maintaining service quality.

## Exploratory Data Analysis
The following scenario analysis were adopted;
1. Identifying Target Customers
  - Demographic Segmentation:
    - Analyze buyer demographics (Gender and Age) to identify the largest customer base.
    - Determine the age group and gender that contribute most to total sales.
    - Product preferences: Explore which product categories (Clothing, Ornaments, Others) are most popular among specific demographics.
  - High-Value Locations:
    - Identify order locations with the highest sales volume and total sales.
    - Analyze buyer demographics within these high-performing regions to uncover customer profiles.
  - Spending Behavior:
    - Evaluate the average sales per unit and quantity purchased across demographics and regions to identify high-spending customers.
2. Improving Ratings and Identifying Issues with Poor Ratings
  - Ratings Distribution:
    - Analyze the average ratings by product category, location, and demographic to identify trends in poor ratings.
    - Filter orders with ratings below a threshold (e.g., <3) to explore potential issues.
  - Review Analysis:
    - Perform sentiment analysis on Review data to identify common complaints or pain points (e.g., shipping delays, product quality, high prices).
  - Product and Region Insights:
    - Highlight products or regions frequently associated with poor ratings.
    - Compare ratings for domestic vs. international orders to check if shipping impacts customer satisfaction.

## Extraction, Transformation and Loading of Data
The datasets were sourced from an `Excel file`, and several key data transformation steps were performed using the Power Query Editor to ensure the data was clean, accurate, and ready for analysis.

The transformation process began with data cleaning to enhance data quality. This involved removing null values and eliminating empty spaces within data rows, ensuring consistency and completeness across the dataset. By addressing these inconsistencies, the data was optimized for analysis, reducing the risk of errors or inaccurate insights.

## Skills/concepts demonstrated:
The following Power Bi features were incorporated
-  Bookmarking and Filtering
-  DAX and Quick measures
-  Page Navigation
## The Logic
- Creating Age bracket into 18-24 (Gen Z), 25-29 (early career professional or millennials), 30-35 (matured buyers)
- A KPI visual is used to measure MoM and MoM percentage on Sales, Orders and Quantities of product
- Measures on Local Performance and International performance on Sales, Orders and Quantities of product
- Measures of shipping and reviews of product
## Visualization
The report comprises of five(5) pages:
- KPI overview of Quantity, Order and Sales
- Shipping and Reviews
  
You can interact with the report [here](https://app.powerbi.com/view?r=eyJrIjoiMzlhYmRjMDEtYmIzMi00MTEwLWJlNzktZmUyYWYwOTc4NTZlIiwidCI6ImYzMzNmMDE4LWE3OTYtNGQ5Yy1iNmM4LThmY2RmYzAyNzEwYiJ9)

