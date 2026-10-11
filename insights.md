
# E-Commerce Sales Analysis - Final Report

## Data Cleaning Summary
- Removed 38 duplicate orders (9245 → 9207)
- Fixed 24 dirty category labels → 8 clean: furniture, kitchen, decor, bedding, outdoor, lighting, storage, bath
- Filled 199 missing unit_price using products.list_price
- discount_code 7834 nulls = customers without coupon (not error)

## KPIs
- Revenue (completed): $1,881,275.08
- Orders: 8,456 completed | Return: 4.44% | Cancel: 3.76%
- AOV: $222.48
- Profit: $925,249.06 (49.18% margin)

## Visual 1: Monthly Revenue Trend
- Jan 2024 $54k → Dec 2025 $90k, 65% growth
- Peak Nov 2024 $100k and Nov 2025 $130k = Q4 holiday season
- Shows strong seasonality and growth

## Visual 2: Revenue by Category
- furniture $330k (17.5%) - Highest
- kitchen $281k, decor $279k, bedding $267k
- bath $108k - Lowest opportunity
- Top 3 categories = 47% of revenue

## Top 10 Products
1. Cotton Patio Chair $67k
2. Classic Dining Chair Pair $52k
3. Coastal Picture Frame Set $44k
4. Ceramic Quilt $41k
5. Bamboo Nightstand $41k
- Furniture is revenue driver, focus marketing there

## Recommendations
1. Stock more Cotton Patio Chair before Q4, it drives peaks
2. Bundle low performers (bath+storage) with furniture
3. Investigate return reason for 4.44%
4. Push gift cards - only 532 orders use them

Files: cleaned_orders.csv, monthly_revenue.csv, revenue_trend.png, category_revenue.png
