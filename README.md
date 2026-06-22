# abhishekmishra_2511066_part4_tableau_dashboard

# Retail Executive Performance Dashboard

## Business Problem Summary

The leadership team required an executive dashboard to monitor overall business performance across sales, profitability, customer segments, shipping efficiency, discount impact, and return behavior. The objective was to identify business opportunities, operational risks, and performance trends to support data-driven decision-making.

---

## Dataset Description

The dataset contains retail transaction records including:

* Order information
* Customer segment information
* Product category and sub-category details
* Regional and geographic data
* Sales and profit metrics
* Shipping details
* Discount information
* Return indicators

The dataset was provided as:

`dashboard_sales_data.xlsx`

---

## Tableau Workbook Description

The Tableau workbook was developed to provide an executive-level view of business performance through interactive visualizations and KPI tracking.

Workbook File:

`executive_dashboard.twbx`

The dashboard enables leadership to monitor revenue, profitability, customer behavior, return rates, and operational performance through filters and interactive analysis.

---

## Calculated Fields Created

### Profit Margin

Profit divided by Sales.

### Cost

Sales minus Profit.

### Average Order Value

Total Sales divided by distinct Order Count.

### Return Rate

Returned Orders divided by Total Orders.

### Shipping Delay Bucket

Delivery performance categorized as:

* Fast
* Normal
* Delayed

---

## Dashboard Components

### KPI Cards

* Total Sales
* Total Profit
* Profit Margin
* Average Order Value
* Return Rate

### Visualizations

* Sales Trend View
* Regional Sales Performance
* Category Profitability View
* Customer Segment Performance
* Shipping Performance Analysis
* Discount Impact on Profit
* Return Analysis View

---

## Filters And Interactions Used

### Filters

* Region
* Category
* Customer Segment
* Ship Mode

### Dashboard Interaction

An action filter was implemented using the Regional Performance View to allow users to interactively filter and analyze related dashboard visualizations.

---

## Key Business Insights

* Sales performance fluctuates throughout the year with identifiable peak periods.
* South region generates the highest sales.
* Technology-related products contribute the highest profits.
* Copiers are the most profitable sub-category.
* Home Office customers generate the highest sales.
* Furniture products exhibit higher return rates.
* Increased discount levels are associated with lower profitability.
* The company maintains a healthy profit margin while generating strong revenue.

---

## Dashboard Story Summary

The dashboard demonstrates strong overall business performance supported by healthy profitability and significant sales volume. Regional performance varies across markets, with South leading sales performance. Technology products drive profitability, while return rates and discounting behavior present opportunities for improvement. The dashboard helps leadership identify growth opportunities and operational risks.

---

## Assumptions And Limitations

### Assumptions

* Data provided is accurate and complete.
* Return indicators correctly represent returned transactions.
* Delivery days accurately reflect shipping performance.
* Sales and profit measures are recorded consistently.

### Limitations

* Dashboard uses historical data only.
* External market conditions are not included.
* Customer satisfaction information is unavailable.
* Forecasting and predictive analytics are outside the scope of this dashboard.

---

## Screenshots Included

* full_dashboard.png
* sales_trend_view.png
* regional_performance_view.png
* category_profitability_view.png
* filter_interaction_view.png


