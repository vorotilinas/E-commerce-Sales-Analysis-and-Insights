# Portfolio Project: E-commerce Sales Analysis and Insights

This project focuses on analyzing e-commerce sales data to identify trends, product categories, and user behaviors across different regions, devices, and channels. The analysis leverages statistical methods, data visualization, and correlation studies to provide actionable insights for marketing, inventory management, and user engagement strategies.

## Project Overview
**Objective**: Analyze e-commerce sales data to uncover regional, device, and channel-specific trends, product categories, and user behavior patterns.

**Key Metrics**:
- Sales by continent, country, and device type.
- Sales by product category and traffic channel.
- User behavior metrics (registered vs unregistered users, email verification rates, subscription rates).
- Correlations between sessions and sales, across continents, channels, and product categories.
- Seasonal trends and daily/weekly sales patterns.

## Tools Used:
- **Python** (Pandas, Matplotlib, Seaborn, Plotly, SciPy, Statsmodels)
- **Google BigQuery** (for data extraction)
- **Jupyter Notebook** (`E-commerce Sales Analysis and Insights.ipynb`)
- **PDF Summary** (`E-commerce Sales Analysis and Insights.pdf`)

## Files in the Repository:
- **`E-commerce Sales Analysis and Insights.ipynb`**: Jupyter Notebook containing the complete analysis, including exploratory data analysis, statistical testing, and visualizations.
- **`E-commerce Sales Analysis and Insights.pdf`**: PDF version of the analysis, summarizing key findings and actionable recommendations.

## Data Source:
The dataset was extracted directly from **Google BigQuery**, combining session-level user activity with product, account, and traffic metadata. The data covers the period from **November 1, 2020** to **January 27, 2021**, with ~33k rows and 18 columns.

## Key Findings and Recommendations

### Summary of Analytical Insights:
- **Sales Distribution**:
  - The majority of revenue comes from the **United States**, followed by **India** and **Canada**.
  - Organic Search and Paid Search channels drive over **60%** of total sales.
- **Top Products and Devices**:
  - Sofas & Armchairs and Chairs are the most purchased categories.
  - Desktop devices contribute ~**59%** of sales; mobile contributes ~**39%**.
- **User Behavior**:
  - Registered users make more frequent but smaller purchases.
  - Unregistered users generate higher order values per transaction.
  - Email verification rate is ~**71%**, while ~**16%** of users unsubscribe.
- **Seasonality**:
  - Clear spike in sales around New Year; lower activity in early January.
  - Higher average sales on **Tuesdays** and **Wednesdays**.
- **Correlations**:
  - Daily sessions and sales have a strong positive correlation (**r ≈ 0.96**).
  - Similar sales patterns are observed across product categories and traffic channels.

### Actionable Recommendations:
#### Marketing:
- Focus campaign spend on **Organic Search** and **Paid Search** — the top-performing channels.
- Introduce mid-week promotions (**Tue/Wed**) to leverage higher purchase activity.
- Launch retargeting campaigns for unregistered users to encourage account creation.

#### Inventory & Merchandising:
- Prioritize stock for **Sofas**, **Chairs**, and **Beds** — the highest-selling categories.
- Prepare extra inventory ahead of holidays (especially December).
- Use product bundles to encourage cross-category purchases (e.g., Sofa + Armchair).

#### User Engagement:
- Offer loyalty incentives to increase order value for registered users.
- Add in-site nudges for email verification to improve communication rates.
- Promote newsletter opt-ins with first-order discounts or exclusive offers.

## Observations on Behavior & Seasonality:
- Weekday patterns indicate strong business-hour engagement — align campaigns accordingly.
- Mobile traffic drives ~**40%** of sales — ensure mobile checkout is fast and frictionless.
- Correlated demand across product categories allows for bundling and smart recommendations.

## Conclusion
This project provides comprehensive insights into e-commerce sales trends, user behavior, and market opportunities. By leveraging statistical analysis and data-driven recommendations, businesses can optimize their marketing strategies, improve inventory management, and enhance user engagement.

For further details, refer to the **PDF summary** (`E-commerce Sales Analysis and Insights.pdf`) and the **Jupyter Notebook** (`E-commerce Sales Analysis and Insights.ipynb`).
