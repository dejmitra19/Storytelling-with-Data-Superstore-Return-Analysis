# Storytelling with Data: Superstore Return Analysis

## Project Overview
This project investigates the high number of returned orders at the Superstore. The goal is to analyze return rates and identify their root causes. A dashboard was created using Tableau to visualize insights and present actionable recommendations to the CEO to help reduce the volume of returned orders.

## Objectives
1. **Analyze Root Causes**:
   - Identify patterns and factors contributing to returns.
   - Understand geographic, seasonal, and product-level influences on return rates.
2. **Create Dashboards**:
   - Develop a dashboard for monitoring returns and identifying root causes.
   - Provide actionable insights for stakeholders.
3. **Present Findings**:
   - Construct a story arc summarizing the analysis and proposed actions.

## Tools and Techniques
- **Datasets**: `Superstore.xls`
- **Tableau**: For creating visualizations, dashboards, and storytelling.
- **Analysis**:
  - Returns data was joined with orders using a LEFT JOIN.
  - Created calculated fields for return rates and total returns.

## Key Insights
### 1. Root Causes of Returns
- **Sales vs. Returns**:
  - High sales categories like **Phones** and **Binders** also had higher return rates.
  - Some subcategories like **Fasteners** showed lower returns despite moderate sales.
- **Geographic Patterns**:
  - States like **Montana**, **Utah**, and **Indiana** had higher return rates.
- **Seasonal Trends**:
  - January and December had the highest return rates, suggesting a possible seasonal impact.
- **Customer Behavior**:
  - Customers like **Sandra Glassco** and **William Brown** had significantly higher return rates.
- **Subcategory Return Rates**:
  - **Binders**, **Paper**, and **Phones** had the highest return rates.

### 2. Dashboard Features
- **Scatterplot**: Shows the correlation between total sales and returns by subcategory.
- **Geographic Map**: Visualizes return rates by state.
- **Bar Charts**: Highlight return rates by product category, customers, and time (months).
- **Composite Charts**: Show multi-factor relationships, such as geography and product category.

## Visualizations
The Tableau dashboard includes:
1. **Sales vs. Returns Scatterplot**: Highlights correlation between total sales and returns.
2. **Return Rate by Geography**: Displays return rates across states.
3. **Return Rate by Time**: Identifies seasonal patterns in returns.
4. **Return Rate by Subcategory**: Highlights subcategories with the highest returns.
5. **Composite Views**: Combines multiple dimensions to uncover deeper insights.

## Files Included
- [Superstore Return Analysis Dashboard on Tableau Public](https://public.tableau.com/shared/6YPSSYNKX?:display_count=n&:origin=viz_share_link): Tableau Public dashboard.
- `Superstore.xls`: Dataset used for the analysis.

## How to Use
1. Open the Tableau Public dashboard [here](https://public.tableau.com/shared/6YPSSYNKX?:display_count=n&:origin=viz_share_link).
2. Explore each visualization to identify root causes of returns.
3. Use filters on the dashboard to focus on specific states, months, or subcategories.

## Story Arc
The analysis and dashboard are structured to:
1. Summarize the root causes of returns.
2. Explain how return rate, total returns, and total costs are measured.
3. Highlight key visualizations and their implications.
4. Demonstrate how the dashboard can be used to identify actionable insights.
5. Recommend next steps to reduce returns.

## Recommendations
- Focus on subcategories like **Binders**, **Paper**, and **Phones** to identify product-specific issues.
- Investigate states with high return rates, like Montana and Utah, for potential process improvements.
- Address seasonal peaks in returns by analyzing post-holiday behavior.

## Future Improvements
- Add predictive analytics to forecast return rates based on historical data.
- Automate dashboard updates for real-time monitoring.
- Implement customer feedback analysis to identify dissatisfaction trends.

## Submission Instructions
This repository contains all files necessary for the project review:
- `README.md`
- Dataset: `Superstore.xls`
- Link to Tableau Public Dashboard.

---

## Contact
If you have any questions or need further details, feel free to reach out!
