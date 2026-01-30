# Interactive-Superstore-Sales-Analysis-Dashboard
This interactive Power BI dashboard explores sales and profitability in the classic Sample Superstore dataset (2014–2017).
It features two pages:

Executive Overview: KPIs (Total Sales $2.3M, Profit $286K, ~12% Avg Margin), monthly trends with strong Q4 peaks, and regional performance (West leads, Central lags).
Product Deep Dive: Sub-category sales/profit bars, profit vs. discount scatter plot, category comparisons, and segment breakdown (Consumer ~46%).

Slicers enable filtering by year, region, category, and segment. Key insights include discount-driven profit erosion, seasonal patterns, and Technology as the top profit driver.

## Key Features
- **Two Pages**:
  - **Page 1 – Executive Overview**: KPIs, monthly sales/profit/margin trend, profit & sales by region.
  - **Page 2 – Deep Dive**: Sub-category sales & profit, category-level quantity/sales, profit vs discount scatter, profit by segment (pie).
- **Interactivity**: Slicers for Year (2014–2017), Category, Region, Segment (and possibly others).
- Visuals: Cards, line/column combo charts, bar charts, scatter plot, pie chart.
- Consistent theme: Green header, intuitive icons, clear titles.

## Dataset
- Source: Sample Superstore (widely used public dataset, often from Tableau/Kaggle)
- Rows: ~9,994 orders
- Key fields: Order Date, Region, Category, Sub-Category, Sales, Profit, Quantity, Discount, Segment

## Key Business Insights
1. **Strong Seasonality** — Sales & profit peak in Q4 (Nov–Dec holidays), weakest in Jan–Feb.
2. **Regional Leader** — West region dominates both sales and profit; Central lags significantly.
3. **Category Winners** — Technology delivers highest profit (especially Phones & Copiers); Furniture drags profitability due to discounts.
4. **Discount Danger** — Higher average discounts strongly correlate with lower/negative profit (clear in scatter plot).
5. **Customer Driver** — Consumer segment generates ~46% of profit — largest contributor.
6. **Overall** — $2.30M sales, $286K profit (~12% margin). Opportunity to boost margins by optimizing discounts and focusing on high-margin categories/regions.

## Tools & Skills Demonstrated
- Power BI Desktop
- Data modeling & DAX basics
- Visualizations: KPIs, trends, bars, scatter, pie
- Slicers & cross-filtering
- Dashboard layout & design principles

## How to Use
1. Clone/download the repo
2. Open `Superstore_Sales_Dashboard.pbix` in Power BI Desktop
3. Interact with slicers to filter by year, region, category, etc.


