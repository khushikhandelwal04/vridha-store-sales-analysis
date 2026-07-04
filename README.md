# Vrinda Store Sales Analysis (2022)

An interactive Excel dashboard that analyzes multi-channel e-commerce sales for Vrinda Store — a fashion/apparel retailer selling across Amazon, Myntra, Flipkart, Ajio, Nalli, and Meesho. The dashboard turns raw order-level transaction data into a decision-ready view of channel performance, customer demographics, product mix, and geographic demand.

## Business Problem

Vrinda Store sells the same product catalog across six online marketplaces. Leadership needed a single view to answer:
- Which sales channels actually drive revenue, and which are underperforming?
- Which product categories should get more inventory and marketing focus?
- Who is the core customer — by age and gender — and does that vary by channel?
- Which states are high-value markets worth targeted logistics or campaigns?
- Is order volume and revenue trending up or down month over month, and are returns/cancellations a problem?

## Dataset

Order-level e-commerce transaction data for 2022, including fields such as Order ID, Order Date, Channel, Category, Amount, Customer Age, Gender, State, and Order Status (Delivered / Returned / Cancelled / Refunded).

## Dashboard Overview

A one-page interactive dashboard with slicers for **Channel**, **Category**, and **Month**, feeding eight linked visuals:

| Visual | What it shows |
|---|---|
| Channel Contribution in Total Sales | Revenue by marketplace (Amazon, Myntra, Flipkart, Ajio, Nalli, Meesho, Others) |
| Order Status | Delivered vs Returned vs Cancelled vs Refunded, as % of total orders |
| Highest Selling Category | Units sold by product category |
| Order: Age vs Gender | Order share split by age band (Young / Middle Age / Old) and gender |
| Sales: Men vs Women | Total orders placed by men vs women |
| Sales: Top 10 States | Revenue ranking across India's top 10 states |
| Sales vs Orders | Monthly trend of order count vs revenue |

## Key Insights

- **Amazon and Myntra are the revenue anchors.** Amazon leads channel revenue, with Myntra (₹50.02L) and Flipkart (₹46.47L) close behind. Ajio, Nalli, Meesho, and Others together contribute a much smaller share — the business is concentrated in three channels.
- **Fulfillment is healthy.** 92% of orders are delivered successfully; returns (3%), cancellations (3%), and refunds (2%) together stay under 10%, indicating no major logistics or product-quality red flag.
- **"Set" and "Kurta" dominate the catalog.** These two categories alone account for ~23,000 of total units sold — more than all other categories combined (Western Dress, Top, Saree, Ethnic Dress, Blouse, Bottom). Inventory and ad spend should mirror this concentration.
- **Women drive the bulk of demand.** Women placed 21,553 orders vs 9,494 by men — roughly a 70:30 split. This holds across every age band (middle-aged, young, and old), with middle-aged women being the single largest segment (34.59% of orders).
- **Geographic demand is west/south-skewed.** Maharashtra (₹30.1L) and Karnataka (₹26.9L) are the top two states by a clear margin, followed by Uttar Pradesh, Telangana, and Tamil Nadu. The top 5 states contribute a disproportionate share of total revenue versus the remaining 5 in the top 10.
- **Orders and revenue are gently declining through the year.** Both the order count and revenue lines peak early (around month 3) and taper off toward the later months, suggesting a need to investigate seasonality or a drop-off in channel-level demand.

## Business Recommendations

1. **Double down on Amazon, Myntra, and Flipkart** — they generate the large majority of revenue; consider reallocating marketing spend away from long-tail channels (Nalli, Meesho, Others) unless there's a specific growth strategy for them.
2. **Prioritize inventory planning around Set and Kurta**, since they are by far the highest-velocity categories; stockouts here would hurt disproportionately.
3. **Tailor campaigns to women, 25–45 age group** — creative, sizing guides, and promotions should center this segment, since it's the largest and most consistent buyer group across channels.
4. **Expand targeted logistics/marketing in Maharashtra and Karnataka**, and evaluate why states outside the top 5 lag — potential for regional campaigns or COD/delivery improvements.
5. **Investigate the late-year sales dip** — cross-check with marketing spend, festive season timing, or channel-level promotions to identify the cause and correct it in the next planning cycle.


## Files in This Repo
dashboard_vridha_store/
├── dashboard_screenshot.jpg      # Static preview image
└── README.md

## Author

**Khushi Khandelwal**
