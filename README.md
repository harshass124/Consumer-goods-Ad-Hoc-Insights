# Consumer Goods Ad Hoc Insights  

## Overview  
This project involves performing **SQL-based ad-hoc analysis** and building **insightful visuals in Power BI** to assist AtliQ Hardware, a leading global computer hardware producer, in identifying trends, making strategic decisions, and scaling its business.  

## Objective  
To assist the management team in making data-driven decisions by providing actionable insights derived from their operational and sales data.  

## Dataset Description  
The analysis is based on a database (`gdb023`) containing six main tables:  
1. **`dim_customer`**: Customer-related data (e.g., customer names, platforms, and regions).  
2. **`dim_product`**: Product-related data (e.g., divisions, segments, and variants).  
3. **`fact_gross_price`**: Gross price information for products.  
4. **`fact_manufacturing_cost`**: Manufacturing costs of products.  
5. **`fact_pre_invoice_deductions`**: Pre-invoice deductions for customers.  
6. **`fact_sales_monthly`**: Monthly sales data for products.  

### Key Fields in the Dataset  
Refer to the **Dataset Description** section above for detailed explanations of columns.

## SQL Questions Addressed  
### The following business questions were answered using SQL queries:  

1. **Markets Analysis**:  
   Identify the markets in the APAC region where the customer "Atliq Exclusive" operates.  

2. **Product Growth**:  
   Calculate the percentage of unique product growth from 2020 to 2021, with fields:  
   - `unique_products_2020`  
   - `unique_products_2021`  
   - `percentage_chg`  

3. **Segment-Wise Product Count**:  
   Report the count of unique products for each segment, sorted in descending order.  

4. **Segment Growth Analysis**:  
   Identify the segment with the highest increase in unique products from 2020 to 2021, with fields:  
   - `segment`  
   - `product_count_2020`  
   - `product_count_2021`  
   - `difference`  

5. **Cost Extremes**:  
   Retrieve the products with the highest and lowest manufacturing costs, with fields:  
   - `product_code`  
   - `product`  
   - `manufacturing_cost`  

6. **Discount Analysis**:  
   Find the top 5 customers with the highest average pre-invoice discount percentage in 2021 in the Indian market, with fields:  
   - `customer_code`  
   - `customer`  
   - `average_discount_percentage`  

7. **Gross Sales by Month**:  
   Generate a monthly gross sales report for "Atliq Exclusive" to identify high and low-performing months, with fields:  
   - `Month`  
   - `Year`  
   - `Gross Sales Amount`  

8. **Quarterly Sales Analysis**:  
   Determine which quarter in 2020 had the maximum total sold quantity, with fields:  
   - `Quarter`  
   - `total_sold_quantity`  

9. **Channel Contribution**:  
   Identify which channel contributed the most gross sales in 2021 and its percentage of contribution, with fields:  
   - `channel`  
   - `gross_sales_mln`  
   - `percentage`  

10. **Top Products by Division**:  
    List the top 3 products in each division by total sold quantity for the fiscal year 2021, with fields:  
    - `division`  
    - `product_code`  
    - `product`  
    - `total_sold_quantity`  
    - `rank_order`  

## Tools and Technologies  
- **SQL**: For data extraction, transformation, and analysis.  
- **Power BI**: For visualizing insights and creating dashboards.  



## Acknowledgements  
This project was inspired by the case studies provided by **Codebasics**. Special thanks to **Dhaval Patel** Sir and **Hemanand Vadivel** Sir.  
THANKYOU♥️
