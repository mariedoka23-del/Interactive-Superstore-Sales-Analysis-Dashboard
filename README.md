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
Key Business Insights from Your Dashboard

**Overall Performance**
**Total Sales**: $2.30 Million across 2014–2017
**Total Profit**: $286,400 (healthy but only ~12.5% margin on average)

**Average Profit Margin**: ~12% (varies a lot by category, month, discount level)
**Total Quantity Sold**: ~38,000 units
→ Strong top-line revenue, but profitability is moderate — discounts and certain categories drag it down.

**Seasonality & Time Trends (Page 1)**
Sales peak strongly in Q4 (October–December) — November & December often double or triple low months like January/February.
Profit follows sales but with bigger swings (peaks in March & Nov–Dec, some low/negative months).
Profit Margin % spikes in high-sales months but drops when discounts rise.
→ **Business takeaway**: Plan inventory, marketing, and staffing heavily for holiday/Q4 season. 
Investigate why early-year months underperform (possibly post-holiday slowdown + higher discounts?).

**Regional Performance (Page 1)**
West region leads in both Sales (~highest bar) and Profit (top of the area chart ~100K+).
East close second in sales, but profit drops noticeably.
Central and South lag behind: lowest sales and especially lowest profit (Central often weakest).
→ **Recommendation**: Focus expansion/retention efforts in West & East. Investigate issues in Central (higher discounts? weaker product mix? competition?).

**Category & Sub-Category Performance (Page 2)**
Technology category delivers highest profit per your scatter plot (blue dot high on Y-axis) despite moderate average discount. Phones & Copiers stand out as top profit drivers.
Office Supplies has solid sales volume but lower profit contribution.
Furniture suffers: high sales in some sub-categories (Chairs, Tables, Storage) but often low/negative profit (likely due to high discounts).
Top profit sub-categories: Copiers, Phones, Accessories, Paper, Binders.
Weakest: Tables, Bookcases, Supplies, some Appliances (negative profit bars).
**→ Insight**: Prioritize Technology push (highest ROI). Reduce aggressive discounting on Furniture :it's eating into margins.

**Discount Impact (Scatter Plot)**
Higher average discount (~0.18) correlates with lower profit (green Technology dot at low discount = high profit; orange Furniture/Supplies at higher discount = lower profit).
→ Key red flag: Discounts are a major profit killer, especially in Furniture & some Office Supplies. Consider targeted discount strategy (e.g., volume-based only for high-margin items).

**Customer Segment (Pie Chart)**
Consumer segment drives ~46% of profit: largest slice.
Corporate ~21%, Home Office ~32%.
→ All segments contribute positively, but Consumer is the volume driver. Tailor promotions/loyalty for them.


## Tools & Skills Demonstrated
- Power BI Desktop
- Data modeling & DAX basics
- Visualizations: KPIs, trends, bars, scatter, pie
- Slicers & cross-filtering
- Dashboard layout & design principles

## How to Use
1. Clone/download the repo
2. Open `Superstore_Project.pbix` in Power BI Desktop
3. Interact with slicers to filter by year, region, category, etc.


