# Marketing Campaign Effectiveness Analysis

## Project Overview

This project analyzes customer data to evaluate marketing campaign effectiveness and identify customer characteristics associated with campaign responses.

The analysis uses Python for data cleaning, transformation, exploratory data analysis (EDA), visualization, and business insight generation.

## Objectives

- Clean and prepare customer marketing data.
- Explore customer demographics and purchasing behavior.
- Analyze campaign response rates across different customer segments.
- Identify factors associated with customer responses.
- Develop data-driven recommendations to improve marketing campaigns.

## Dataset

The dataset contains **2,240 customer records and 22 original variables**.

It includes information about:

- Customer demographics
- Income and household information
- Product spending
- Purchase behavior
- Website activity
- Campaign response

The `Response` variable indicates whether a customer responded to the campaign:

- `0` — No response
- `1` — Responded

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Project Workflow

1. **Data Collection and Exploration**
   - Loaded the dataset.
   - Examined data structure and summary statistics.
   - Identified missing values and potential data quality issues.

2. **Data Cleaning and Transformation**
   - Handled missing income values.
   - Investigated extreme income values.
   - Prepared customer and campaign-related variables.
   - Created additional features for analysis.

3. **Exploratory Data Analysis**
   - Analyzed overall campaign response.
   - Compared response rates by education and marital status.
   - Examined spending and purchasing behavior.
   - Explored customer enrollment-year cohorts.
   - Studied correlations between key variables.
   - Identified high-performing and underperforming customer segments.

4. **Business Insights and Recommendations**
   - Interpreted customer behavior patterns.
   - Identified useful indicators of campaign response.
   - Developed recommendations for more targeted marketing.

## Key Findings

- The overall campaign response rate was approximately **14.9%**.
- Responders had higher average spending and purchase activity than non-responders.
- Customers with lower recency values showed greater campaign responsiveness.
- Education groups showed differences in response rates.
- Total spending had a stronger positive relationship with campaign response than income.
- Monthly website visits showed little linear relationship with campaign response in this dataset.

## Business Recommendations

- Focus marketing efforts on customers with recent purchasing activity.
- Use spending and purchase history to support customer segmentation.
- Develop targeted campaigns for customer groups with higher response rates.
- Investigate why certain customer segments respond less frequently.
- Collect campaign-level information to evaluate campaign ROI more accurately.

## Conclusion

This project demonstrates how Python and exploratory data analysis can help businesses understand customer behavior and evaluate marketing campaign responses.

The findings can support better customer segmentation, more targeted marketing strategies, and improved campaign planning.

## Author

**Bibek Sapkota**
