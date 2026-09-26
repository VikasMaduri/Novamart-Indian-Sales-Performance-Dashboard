# Novamart-Indian-Sales-Performance-Dashboard

# Indian Sales Performance Dashboard

## Overview

This project delivers an interactive sales performance dashboard for a company that sells multiple products across regions, sales channels, and customer types. It is built from order-level sales data and enables the management team to monitor key metrics, identify trends, and make data-driven decisions.


---

## Business Scenario

You are working on a project that sells different products across multiple regions, sales channels, and customer types. You have order-level sales data. The manager wants a dashboard to review sales performance, including:

- Revenue
- Orders
- Quantity sold
- Average order value
- Trends over time
- Regional performance
- Product category performance
- Sales channel contribution
- Top products by revenue

---

## Key Performance Indicators (KPIs)

| KPI                      | Description                              | Calculation Basis          |
|--------------------------|------------------------------------------|----------------------------|
| **Total Revenue**        | Overall sales revenue                    | Sum of Revenue             |
| **Total Orders**         | Number of unique orders                  | Count of Order ID          |
| **Total Quantity**       | Units sold                               | Sum of Quantity            |
| **Average Revenue**      | Average order value                      | Revenue / Orders           |
| **Monthly Revenue Trend**| Revenue performance by month             | Date + Revenue             |
| **Regional Performance** | Revenue by geographic region             | Region + Revenue           |
| **Category Performance** | Revenue by product category              | Product Category + Revenue |
| **Channel Contribution** | Revenue share by sales channel           | Sales Channel + Revenue    |
| **Top Products**         | Highest revenue-generating products      | Product + Revenue          |

### Snapshot Metrics (as of latest data)

| Metric              | Value      |
|---------------------|------------|
| Total Revenue       | $152.04M   |
| Total Orders        | 2,500      |
| Total Quantity      | 11,123     |
| Average Revenue     | $60.82K    |

---

## Dashboard Features

### Interactive Filters
- **Region:** North, South, West, East, Central
- **Sales Channel:** Corporate Sales, Marketplace, Online, Retail Store
- **Customer Type:** New, Returning
- **Product Category:** Accessories, Computers, Monitors, Networking, Office Supplies, Storage
- **Date Slicers:** Days, Months, Years, Quarters (supports multi-period analysis)

### Visualizations

1. **KPI Cards**
   - Total Revenue
   - Total Orders
   - Total Quantity
   - Average Revenue

2. **Monthwise Revenue**  
   Line chart showing average revenue trend across months (Jan–Dec).

3. **Regionwise Revenue**  
   Bar chart comparing revenue performance across North, South, West, East, and Central regions.

4. **Channelwise Revenue**  
   Pie/Donut chart showing revenue contribution by sales channel:
   - Corporate Sales
   - Marketplace
   - Online
   - Retail Store

5. **Categorywise Revenue**  
   Column chart displaying revenue by product category (Computers is the dominant category).

6. **Top 5 Products**  
   Horizontal bar chart ranking products by revenue:
   - Gaming Laptop
   - Laptop Air
   - All-in-One PC
   - Business Laptop
   - Desktop Mini

---

## Data Insights (Sample)

### Regional Performance (Average Revenue)
| Region   | Average Revenue |
|----------|-----------------|
| East     | $71.52K         |
| West     | $62.74K         |
| South    | $59.24K         |
| Central  | $55.80K         |
| North    | $53.46K         |
| **Grand Total** | **$60.82K** |

### Sales Channel Performance
| Sales Channel    | Average Revenue |
|------------------|-----------------|
| Marketplace      | $65.11K         |
| Corporate Sales  | $64.77K         |
| Online           | $57.34K         |
| Retail Store     | $55.86K         |

### Product Category Performance
| Category        | Average Revenue |
|-----------------|-----------------|
| Computers       | $249.88K        |
| Monitors        | $84.93K         |
| Networking      | $17.83K         |
| Storage         | $16.73K         |
| Accessories     | $6.31K          |
| Office Supplies | $1.21K          |

### Top Products by Average Revenue
| Product         | Average Revenue |
|-----------------|-----------------|
| Gaming Laptop   | $344.77K        |
| Laptop Air      | $272.39K        |
| All-in-One PC   | $240.63K        |
| Business Laptop | $230.23K        |
| Desktop Mini    | $152.94K        |

### Monthly Revenue Trend (Average)
| Month | Average Revenue |
|-------|-----------------|
| Apr   | $71.78K         |
| Jan   | $68.41K         |
| May   | $66.65K         |
| Sep   | $64.92K         |
| Mar   | $60.96K         |
| Nov   | $65.05K         |
| Dec   | $59.91K         |
| Oct   | $57.00K         |
| Feb   | $59.29K         |
| Aug   | $56.38K         |
| Jun   | $52.90K         |
| Jul   | $46.23K         |

---

## Project Structure

```
indian-sales-performance-dashboard/
│
├── data/                       # Raw and processed sales data
│   └── sales_data.csv          # Order-level sales data
│
├── dashboard/                  # Dashboard files (Power BI / Tableau / etc.)
│   └── Indian_Sales_Performance_Dashboard.pbix
│
├── analysis/                   # Supporting analysis notebooks or scripts
│   └── exploratory_analysis.ipynb
│
├── screenshots/                # Dashboard visuals
│   ├── c:\Users\Vikas Maduri\Pictures\Screenshots\Screenshot 2026-09-26 232017.png
│   └── c:\Users\Vikas Maduri\Pictures\Screenshots\Screenshot 2026-09-26 232056.png
│
└── README.md                   # Project documentation
```

---

## How to Use

1. **Open the Dashboard**  
   Launch the `.pbix` (Power BI) or equivalent file in the appropriate tool.

2. **Apply Filters**  
   Use the left-side filter panes (Region, Sales Channel, Customer Type, Product Category) and date slicers to focus on specific segments.

3. **Explore Visuals**  
   Hover over charts for detailed tooltips. Cross-filter by clicking on chart elements (e.g., select a region to see its impact on other visuals).

4. **Review KPIs**  
   Monitor the top-level cards for a quick health check of overall performance.

---

## Tools & Technologies

- **BI Tool:** Power BI / Tableau / Excel (Pivot Tables & Charts)
- **Data Source:** Order-level sales transactional data
- **Key Techniques:** Pivot tables, Interactive slicers, Cross-filtering

---

## Business Value

This dashboard enables stakeholders to:

- Track overall sales health through clear KPI cards
- Identify high-performing and underperforming regions
- Understand which sales channels and product categories drive the most revenue
- Spot seasonal trends and monthly performance patterns
- Focus on top revenue-generating products for inventory and marketing decisions
- Slice data by customer type (New vs Returning) for retention and acquisition insights

---

## Future Enhancements

- Year-over-year (YoY) and period-over-period comparisons
- Customer segmentation and lifetime value analysis
- Profitability metrics (if cost data becomes available)
- Automated alerts for underperforming regions or products
- Mobile-optimized dashboard view
- Integration with real-time data sources

---

## Author

**Vikas Maduri**



*This project was created as a part of my data analysis learning journey*
