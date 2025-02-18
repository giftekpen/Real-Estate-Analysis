# Real-Estate-Analysis
## PROJECT OVERVIEW 
This project analyzes real estate sales trends using historical sales data, focusing on property valuations, sales patterns, and market dynamics across different property types. By leveraging data visualization and statistical techniques, this project aims to provide actionable insights into sales performance, market dynamics, and opportunities for optimization.

## ANALYSIS STEPS
1. Data Collection and Preparation:
- Gathered real estate data from <a href="https://catalog.data.gov/dataset/real-estate-sales-2001-2018">GOV.COM
- Cleaned and preprocessed the data to ensure accuracy and consistency.

2. Exploratory Data Analysis (EDA):
- Visualized total sales amounts and property counts by year to identify overall trends.
- Analyzed monthly sales trends to understand seasonal patterns.
- Examined the relationship between assessed values and sale amounts to evaluate pricing accuracy.
- Investigated sales performance by property type to identify high-performing categories.

3. Trend Analysis:
- Plotted average assessed values over the years to observe market valuation trends.
- Analyzed the average sales ratio by residential type to assess pricing consistency.

4. Visualization:
- Created visualizations using Python's matplotlib and seaborn libraries

## KEY INSIGHTS
1. Seasonal Sales Patterns
- Peak sales volume (95,000+ transactions) occurs in June-August
- December shows a 45% increase in average sale amounts compared to November
- January and February show lowest transaction volumes (~60,000 transactions each)

2. Long-term Market Trends
- Average sale prices increased from $300,000 (2000) to $500,000 (2020), representing a 67% growth
- Property sales volume peaked in 2005-2006 with ~75,000 annual transactions
- Assessed values grew from ~$50,000 (2000) to ~$325,000 (2020), a 550% increase
- Recent years (2015-2020) show 15-20% annual growth in average sale prices

3. Property Type Analysis
- Single-family properties account for approximately $1.5×10¹¹ in total sales volume
- Single-family homes show a sales ratio of 6.0, significantly higher than other types
- Property type distribution:
  - Single Family: 65% of total sales
  - Commercial: 15%
  - Condo: 10%
  - Other types: 10% combined

4. Value Assessment Relationship
- Correlation coefficient of 0.23 between assessed values and sale amounts
- Assessed values show an average annual increase of 8.5%
- 90% of properties show assessed values under $2 million
- Outliers present in properties valued above $8 million

## Recommendations
- Focus on single-family homes, representing 65% of market volume. which also showed 300% higher sales ratios than other types
- Allocate 15-20% of portfolio to commercial properties, matching market distribution
- Implement strategies such as targeted discounts, loyalty programs, or clearance sales to mitigate sales declines during off-peak periods.
- Monitor assessed values as they've shown consistent 8.5% annual growth
- List properties during peak season (June-August) when transaction volumes are 58% higher
- Prepare listings by April-May to capture 95% of peak season potential
- Consider December listings for premium properties, with 45% higher average sales prices

## CODE
The Analysis can be found in the jupyter notpad: <a href="https://github.com/giftekpen/Real-Estate-Analysis/blob/main/Real%20estate.ipynb">SEE MY ANALYSIS

## Note: 
This analysis is based on historical data and should be combined with current market conditions and local factors for decision-making purposes.


