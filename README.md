# Adventure Works Sales Project

The purpose of the project is to show the overall sales performance at Adventure Works over the span of two and a half years.

For reference, the [data](./data) directory holds all of the original data used to create the dashboard that reflects key sales metrics. This contains a PowerBI dashboard visualization of that data.

*Note:* All references regarding interactive features can only be experienced through Power BI with the given file [AW_Sales_Project.pbix](./AW_Sales_Project.pbix)

## Analysis

The [`AW_Sales_Project`](./AW_Sales_Project.pdf) PDF consists of 3 major categories that will be explained by each section below.

### Executive Summary
- The "Executive Summary" page displays the summarized sales performance of the company showcasing orders by its categories and subcategories. Though this is a PDF version of the interactive Power BI interface, sales data can be viewed with a given time range. This can be as specific as day, week, month, year.

- Total orders by category:
  - `Accessories` are the most ordered products by category at 17k+ orders
  - `Accessories` make up for almost half of the total orders and `Bikes` at 14k+ total orders, they bring in $1.7 million per month versus `Accessories` at 88k per month
  - `Bikes` bring in the most revenue due to the higher prices when compared to `Accessories`, though the total orders are less
- With monthly orders of 1,157 orders for `Bikes`, the product makes up for $1.7 million out of the total overall montlhy revenue of $1.83 million.
- `Accessories` have the highest monthly orders out of the 2 other categories but make only $88.60k per month in revenue
- Top Selling Accessory product is the "30 oz water bottles" and least are the "All-purpose Bike Stands"
- Top selling bike model is the "Mountain-200 Black, 46" and least is the "Mountain-100 Silver, 48"
- Top selling `Clothing` product is the "AWC Logo Cap" and least is the "Classic Vest, S"
- 30 oz water bottles are the most ordered product and Mountain-200 Black, 46 Bike model bring in the most profit
- Based on the Map visualization in the lower right corner:
  - North America makes the most orders on `Accessories` and `Clothing`
  - North America and Australia order similar amount of `Bikes`

**Summary:** Overall `Bikes` performs the best in terms of profit, monthly revenue, and monthly orders as they hit all of their target goals for their KPIs.

### Product Details
The **Product Details** page goes more in-depth on specific product sales targets including: current month orders, current month revenue, and current month returns, weekly profit, price adjustments.

- The **Executive Summary** page references to the **Product Details** page in terms of a specific item
  - Select a product from the Product Name list in **Executive Summary** page > Select any product > Right-click > Drill through > Product Detail
  - Once that is done, you can see that in the Product Detail it displays all the information of the product you selected to drill through in the Exe Summary page
  - You can check any product to see how well its performing in this Product Details page
  
- Sales information based on our top ordered product, Water Bottle - 30 oz:
  - Near target goal of order volumes and monthly revenue
  - Based on the "Weekly Profit" line chart, the product has a positive trend line, so we can forecast that this will grow in the future
  - On the "Weekly Profit" line chart, I've applied a 90% confidence interval. We can forecast the highest and lowest profit amount that we will be predicted to earn in the next few months

Overall this page summarizes each product's performances if any product and/or sales manager wanted to know its top performers and bottom performers.

### Customer Details
The **Customer Details** page goes more in-depth with the customers and their information such as: gender, income level, and occupation. This page also shows the total number of orders they have made overall and how much the revenue has made from specific customers.

- The matrix on the right shows the top 100 customers by revenue
  - Once we select a customer's name, it will display the customer's demographics including: gender, income level, occupation, and their age
  - For example, if we select "Mr.Maurice Shan", we can see the following details:
    - Gender is "Male"
    - Income Level is "Average"
    - Occupation is categorized in "Professional"
    - Customer has made the most orders in 2016 vs 2017

If we select "F" (Female) in the donut chart called "Orders by Gender", we can see that Mrs. Janet Munoz is our Top female customer with 6 total orders resulting in $12.02 thousand in revenue.
  
Overall, we can see that Mr. Maurice Shan is our top customer overall and top male customer with only 6 orders made over time totaling $12.4 thousand in revenue.

Using this information, we may find the products that best increase our sales as well as what we put our efforts to focus on such as marketing, top customers, top selling products, and etc.
