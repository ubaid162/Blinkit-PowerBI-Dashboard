### 1. Blinkit Sales Dashboard
**Business Context**: E-grocery platform needs to track sales performance, customer ratings, and outlet efficiency.

**KPIs Tracked**:
- Total Sales (₹1.20M)
- Average Rating (3.9/5)
- Number of Items Sold (8523)
- Average Sales per Order

**Key Features**:
- Sales by outlet location (Tier 1/2/3 cities)
- Category-wise revenue breakdown
- Outlet size vs performance analysis
- Time-based sales trends
- Interactive slicers for filtering

**DAX Measures Created**:
- Total Revenue = SUM(Sales[Amount])
- Average Rating = AVERAGE(Sales[Rating])
- Sales Growth = (Current Month - Previous Month) / Previous Month

**Business Insights**:
- Tier 1 cities generate 45% of revenue
- Fruits & Vegetables category highest volume
- Medium-sized outlets most profitable
- Peak sales during weekends
