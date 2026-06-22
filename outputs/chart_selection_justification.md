# Chart Selection Justification

## 1. Sales Trend View

### Business Question
How are sales changing over time?

### Chart Type Used
Line Chart

### Why This Chart Type Is Appropriate
A line chart is the best visualization for showing trends and patterns over time. It helps leadership quickly identify periods of growth and decline.

### Fields Used
- X-Axis: Order Date (Month)
- Y-Axis: Sales

### Design Principle Applied
Used a simple and uncluttered design to emphasize trends and make month-to-month comparisons easy.

### Mistake Avoided
Avoided pie charts and categorical charts that cannot effectively display time-series data.

---

## 2. Regional Sales Performance

### Business Question
Which region generates the highest sales?

### Chart Type Used
Horizontal Bar Chart

### Why This Chart Type Is Appropriate
Bar charts allow easy comparison across multiple regions and clearly highlight the highest and lowest performers.

### Fields Used
- Rows: Region
- Columns: Sales
- Color: Profit

### Design Principle Applied
Sorted values to improve readability and quickly identify top-performing regions.

### Mistake Avoided
Avoided complex maps that could make comparisons more difficult.

---

## 3. Category Profitability View

### Business Question
Which categories and sub-categories generate the most profit?

### Chart Type Used
Horizontal Bar Chart

### Why This Chart Type Is Appropriate
Bar charts clearly compare profitability across many sub-categories while maintaining readability.

### Fields Used
- Rows: Sub-Category
- Columns: Profit
- Color: Category

### Design Principle Applied
Used color grouping to distinguish categories while maintaining consistent formatting.

### Mistake Avoided
Avoided overcrowded visualizations that reduce readability.

---

## 4. Customer Segment Performance

### Business Question
Which customer segment contributes the most sales?

### Chart Type Used
Horizontal Bar Chart

### Why This Chart Type Is Appropriate
The chart makes comparison between customer segments straightforward and easy to understand.

### Fields Used
- Rows: Customer Segment
- Columns: Sales

### Design Principle Applied
Kept the visualization simple with clear labels and sorting.

### Mistake Avoided
Avoided unnecessary visual effects that could distract from the comparison.

---

## 5. Shipping Performance Analysis

### Business Question
How does shipping mode affect delivery performance?

### Chart Type Used
Stacked Bar Chart

### Why This Chart Type Is Appropriate
Stacked bars allow comparison of shipping modes while also displaying delivery delay categories.

### Fields Used
- Rows: Ship Mode
- Columns: Average Delivery Days
- Color: Shipping Delay Bucket

### Design Principle Applied
Used color to distinguish delivery speed categories for quick interpretation.

### Mistake Avoided
Avoided tables that would require users to manually compare values.

---

## 6. Discount Impact On Profit

### Business Question
How do discounts affect profitability?

### Chart Type Used
Scatter Plot

### Why This Chart Type Is Appropriate
Scatter plots are ideal for identifying relationships between two numerical variables.

### Fields Used
- X-Axis: Discount
- Y-Axis: Profit
- Color: Category
- Size: Sales

### Design Principle Applied
Used visual encoding to reveal patterns and outliers without overcrowding the chart.

### Mistake Avoided
Avoided bar charts which cannot effectively show relationships between continuous variables.

---

## 7. Return Analysis View

### Business Question
Which categories experience higher return rates?

### Chart Type Used
Stacked Bar Chart

### Why This Chart Type Is Appropriate
The chart allows easy comparison of return patterns across product categories and customer segments.

### Fields Used
- Rows: Category
- Columns: Return Rate
- Color: Customer Segment

### Design Principle Applied
Used consistent colors and clear labels to improve interpretability.

### Mistake Avoided
Avoided pie charts that would make category comparisons difficult.

---

## Dashboard-Level Design Decisions

### KPI Cards Included
- Total Sales
- Total Profit
- Profit Margin
- Average Order Value
- Return Rate

### Filters Included
- Region
- Category
- Customer Segment
- Ship Mode

### Interactivity Used
Dashboard filter action allows users to interact with charts and explore specific segments of data.

### Visual Design Principles Applied
- Clear visual hierarchy
- Consistent color usage
- Minimal clutter
- Appropriate chart selection
- Readable labels and titles
- Business-focused presentation

### Overall Goal
The dashboard was designed to provide leadership with a clear overview of business performance, risks, and opportunities while supporting data-driven decision-making.