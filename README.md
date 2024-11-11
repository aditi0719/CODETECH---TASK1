NAME - ADITI SONI
COMPANY - CODETECH IT SOLUTIONS
ID - CT08DS8707
DOMAIN - POWER BI 
DURATION- 1 MONTH

# Sales Dashboard Analysis
snapshot - 
![Screenshot 2024-10-25 235613](https://github.com/user-attachments/assets/b027420c-7642-4716-992d-b666ad2a8394)

---

## Problem Statement

This dashboard provides insights into the sales performance across regions, product categories, and customer segments. It helps in identifying high and low-performing areas, tracks revenue trends over time, and provides key metrics for decision-making. The dashboard highlights the proportion of sales across product lines and customer preferences, assisting the sales team in targeting strategies to boost sales and improve customer satisfaction.

---

## Steps Followed to Build the Dashboard

1. **Data Import**:
   - Imported the CSV sales data file into Power BI Desktop.

2. **Data Profiling**:
   - Enabled `Column Distribution`, `Column Quality`, and `Column Profile` in Power Query Editor to review data quality.
   - Selected “Column profiling based on entire dataset” for complete data analysis.

3. **Data Cleaning**:
   - Removed null values in non-critical columns and formatted fields for easier analysis.

4. **Theme Selection**:
   - Selected a custom theme to ensure a consistent look and feel across the dashboard visuals.

5. **KPI Creation**:
   - Used card visuals to highlight:
     - Total Revenue
     - Total Orders
     - Average Order Value
     - Profit Margin

6. **Slicers for Filtered Insights**:
   - Added slicers for `Region`, `Product Category`, `Sales Rep`, and `Quarter`.

7. **Revenue Trend Line**:
   - Added a line chart visual to display revenue trends over time, segmented by quarters to observe seasonal patterns.

8. **Top Performing Products and Regions**:
   - Created bar charts to show the top 5 performing products and regions by sales volume.

9. **Customer Segmentation**:
   - Visualized customer segments by purchase behavior and average order size using pie and donut charts.

10. **Product Sales Analysis**:
    - Used stacked bar charts to show sales across product categories and their contribution to total revenue.

11. **Text and Branding**:
    - Added text boxes for the company name and dashboard title. A rectangle shape and the company logo were added for branding consistency.

12. **Calculated Columns and Measures**:
    - Added custom DAX measures for:
      - Profit Margin Calculation:
        ```DAX
        Profit Margin = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Revenue])) * 100
        ```
      - Average Order Value:
        ```DAX
        Average Order Value = DIVIDE(SUM(Sales[Revenue]), COUNT(Sales[OrderID]))
        ```
    - Snap of the Profit Margin Measure:

      ![Screenshot 2024-10-25 235613](https://github.com/user-attachments/assets/7326d211-317d-42fd-893e-43baaef6adfe)

13. **Publishing**:
    - Published the dashboard to Power BI Service.

---

## Dashboard Snapshots

**Power BI Desktop View**  
      ![Uploading Screenshot 2024-10-25 235613.png…]()
      ![Uploading Screenshot 2024-10-25 235613.png…]()


---

## Insights

### Sales Overview

- **Total Revenue**: $5.7M
- **Total Orders**: 14,000
- **Average Order Value**: $407.14
- **Profit Margin**: 23.5%

### Regional Sales Distribution

- **Top Regions by Revenue**:
  - North America: 35%
  - Europe: 30%
  - Asia: 20%
  - South America: 10%
  - Other: 5%
- Insight: North America contributes the highest sales, suggesting strong market presence.

### Product Performance

- **Top Product Categories**:
  - Electronics: 40%
  - Furniture: 25%
  - Office Supplies: 20%
  - Apparel: 15%
- Insight: Electronics and Furniture are the top-performing categories.

### Customer Segmentation

- **Key Customer Segments**:
  - Small Businesses: 50%
  - Corporate Accounts: 35%
  - Individual Consumers: 15%
- Insight: Small businesses account for the majority of sales, followed by corporate accounts.

### Quarterly Revenue Trends

- Revenue peaks in Q2 and Q4, indicating potential seasonal sales boosts during these periods.

---

## How to Use

1. **Filters**: Use slicers to analyze sales data by region, product category, sales representative, and quarter.
2. **KPIs**: Quickly review key KPIs such as total revenue, order count, average order value, and profit margin.
3. **Top Insights**: Utilize visuals to identify top-performing products, regions, and customer segments.
4. **Revenue Trends**: Use the line chart to observe sales trends over quarters and adjust strategies accordingly.

