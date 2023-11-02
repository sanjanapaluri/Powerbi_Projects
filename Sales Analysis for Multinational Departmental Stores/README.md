# Sales Analysis for Multinational Departmental Stores

## Business Problem

The primary goal of this data analysis is to extract meaningful insights from the dataset and address critical business questions. By doing so, we aim to enhance various aspects of the company's operations and overall performance:

### Region and Product Category Analysis

- **Region Analysis:** We will analyze sales performance across different regions where the company operates. This will help identify regions that require improvement and those that are performing well.

- **Product Category Analysis:** Understanding product categories is essential for optimizing sales and marketing efforts. We will investigate which categories are driving sales and profitability.

### Best Performing Products and Top Customers

- **Best Performing Products:** Identifying the products that contribute the most to sales revenue and profitability can guide inventory management and marketing strategies.

- **Top Customers:** Recognizing and rewarding the top-performing customers who significantly impact sales and profitability is crucial for customer retention and growth.

### Delivery Performance Analysis

- **Delivery Status Analysis:** Analyzing delivery statuses will help us assess how well the company is meeting customer expectations regarding order delivery. This can lead to improvements in the shipping process.

### Department-Level Sales and Profit Analysis

- **Department-Level Analysis:** We will conduct a detailed analysis of sales and profits at the department level within the stores. This can reveal which departments are performing exceptionally well and which may need attention or restructuring.

## Final Dashboard

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/6e3e8cc2-63bc-41c7-9a70-559766838611)

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/ac0c3f6d-d5d1-4e44-9607-0169d0e702cd)

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/b824e057-ed8a-4d99-a272-ab267cd34367)

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/fc90449d-134d-43da-aae0-4444efe3ae57)

## Dataset Overview

This dataset provides a comprehensive view of sales transactions conducted by a multinational company through its departmental stores across the world. It encompasses a wide array of details related to sales, including discount rates, profits, product information, customer data, store data, and geographical location.

## Dataset
You can access the dataset [here](https://drive.google.com/file/d/1rNK3nmroxnxiZahUlR9g0I9rZM7uW0W5/view?usp=drive_link)

| Column Name              | Description                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------------------|
| Type                     | Type of transaction made                                                                           |
| Days for shipping (real) | Actual shipping days of the purchased product                                                      |
| Days for shipment (scheduled) | Days of scheduled delivery of the purchased product                                            |
| Delivery Status          | Delivery status of orders: Advance shipping, Late delivery, Shipping canceled, Shipping on time    |
| Late_delivery_risk       | Categorical variable that indicates if sending is late (1) or not late (0)                         |
| Category Name            | Description of the product category                                                                |
| Customer Fname           | Customer name                                                                                      |
| Customer Id              | Customer ID                                                                                        |
| Customer Lname           | Customer last name                                                                                 |
| Customer Segment         | Types of Customers: Consumer, Corporate, Home Office                                               |
| Department Id            | Department code of the store                                                                       |
| Department Name          | Department name of the store                                                                       |
| Latitude                 | Latitude corresponding to the location of the store                                                |
| Longitude                | Longitude corresponding to the location of the store                                               |
| Market                   | Market to where the order is delivered: Africa, Europe, LATAM, Pacific Asia, USCA                 |
| Order City               | Destination city of the order                                                                      |
| Order Country            | Destination country of the order                                                                   |
| order date (DateOrders)  | Date on which the order is made                                                                   |
| Order Id                 | Order code                                                                                         |
| Order Item Discount      | Order item discount value                                                                          |
| Order Item Discount Rate | Order item discount percentage                                                                     |
| Order Item Id            | Order item code for stores                                                                         |
| Order Item Product Price | Unit Price of products without discount                                                            |
| Order Item Profit Ratio  | Order Item Profit Ratio                                                                            |
| Order Item Quantity      | Number of products per order                                                                       |
| Sales                    | Value in sales                                                                                     |
| Order Item Total         | Total amount per order                                                                             |
| Order Profit Per Order   | Order Profit Per Order                                                                             |
| Order Region             | Region of the world where the order is delivered                                                   |
| Order State              | State of the region where the order is delivered                                                    |
| Order Status             | Order Status: COMPLETE, PENDING, CLOSED, PENDING_PAYMENT, CANCELED, PROCESSING, SUSPECTED_FRAUD, ON_HOLD, PAYMENT_REVIEW |
| Product Card Id          | Product code                                                                                        |
| Product Category Id      | Product category code                                                                               |
| Product Description      | Product Description                                                                                |
| Product Name             | Product Name                                                                                       |
| Product Price            | Product Price                                                                                      |
| Product Status           | Status of the product stock: 1 for not available, 0 for available                                    |
| Shipping date (DateOrders)| Exact date and time of shipment                                                                   |
