# Maven's Pizza Sales Insights

![Pizza Banner](https://github.com/user-attachments/assets/190fced6-a2a6-4382-919f-3d89de89cddf)

## Table of Contents
- [Project Background](#project-background)
- [Data Structure](#data-structure)
- [Key Findings](#key-findings)
- [Dashboard](#dashboard)
- [Recommendations](#recommendations)
---

## Project Background
A full year of sales data from a fictitious pizza restaurant was analysed to identify bestselling products, customer size and category preferences, peak trading periods, and ingredient demand. The analysis aims to deliver actionable insights to refine sales strategies and streamline operations.

## Data Structure

The dataset consists of four tables with **48,620 records** covering a full year of pizza sales transactions.

![Pizza ER Diagram](<Pizza ER Diagram.drawio.png>)

| Table | Description |
|-------|-------------|
| `order_details` | Line-item details per order (`order_details_id`, `order_id`, `pizza_id`, `quantity`) |
| `orders` | Order-level data (`order_id`, `date`, `time`) |
| `pizzas` | Pizza variants with size and price (`pizza_id`, `pizza_type_id`, `size`, `price`) |
| `pizza_types` | Pizza names, categories and ingredients (`pizza_type_id`, `name`, `category`, `ingredients`) |
---

## Key Findings

### Pizza Performance

- Thai Chicken Pizza leads at $43.4K in sales — 274% more than the lowest performer (Brie Carre at $11.6K)
- Barbecue Chicken Pizza is a close second at $42.8K — non-vegetarian pizzas consistently outperform vegetarian across all categories

### Category & Size Preferences

- Classic category leads with 14,888 orders — 24% ahead of Supreme (11,987 orders)
- Large is the most popular size at 18,526 units sold; XL and XXL are the least favoured

### Ingredient Popularity

- Garlic is the top ingredient at $27.4K in sales, followed by Tomatoes ($26.6K) and Red Onions ($19.5K)
- Mozzarella rounds out the top 5 at $10.3K

### Peak Hours & Days

- Afternoons are the busiest with 29,468 orders — 70% more than evenings (17,356 orders)
- 12 PM is the peak hour at 6,776 pizzas sold
- Friday is the top day at 8,106 pizzas; Thursday and Saturday follow closely

### Monthly Performance

- July is the top month at $72.6K in sales and 4,301 pizzas sold
- October is the weakest month — likely impacted by seasonal demand shifts

## Dashboard
![Mavens Pizza Dashboard](https://github.com/user-attachments/assets/ac5fa199-5b2d-407f-9d24-5b1b2fb71ac4)

## Recommendations

1. Promote non-vegetarian bestsellers — Thai Chicken and Barbecue Chicken drive the most revenue; feature them in meal deals and seasonal promotions to maintain momentum
2. Revive or replace low performers — Brie Carre at $11.6K is 274% below the top seller; consider a recipe refresh or replacing it with a customer-designed pizza option
3. Capitalise on Friday afternoon peak — 12 PM and Friday are the busiest window; align staffing, inventory and promotions to this period to maximise throughput
4. Drive October sales with seasonal theming — the weakest month coincides with Halloween; limited-time themed pizzas could boost revenue during the slow period
5. Introduce a half-and-half option for XL/XXL — low demand for larger sizes suggests customers are hesitant; a split topping option could make larger pizzas more appealing
---
