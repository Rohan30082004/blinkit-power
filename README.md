# Blinkit Dashboard  

### Dashboard Link: [https://app.powerbi.com/links/V0bjyW-P7M?ctid=634bb93c-4f3e-42e2-a5eb-68956bc5a9a2&pbi_source=linkShare]

---
## Problem Statement  

This dashboard analyzes Blinkit order data to provide insights into customer order trends, delivery performance, and improvement areas for operational efficiency. It helps in identifying delivery times, customer preferences, and key metrics such as the average order value, most ordered items, and customer satisfaction based on repeat orders.  

The insights gained from this dashboard enable Blinkit to enhance its delivery services by reducing average delivery times and addressing common customer grievances.  

For instance, if a significant proportion of orders experience delays beyond 30 minutes or cancellations due to item unavailability, Blinkit can address these issues by improving inventory management and optimizing delivery routes.  

Since a majority of orders are placed during specific time windows, such as evenings, the company can scale its resources effectively during peak hours to ensure timely deliveries.  

---

### Steps Followed  

- **Step 1**: Loaded the dataset (CSV format) into Power BI Desktop.  
- **Step 2**: Opened Power Query Editor and enabled “Column distribution,” “Column quality,” and “Column profile” for better data understanding.  
- **Step 3**: Set profiling based on the entire dataset to analyze all rows, not just the first 1,000.  
- **Step 4**: Identified null values in columns such as "Delivery Time" and "Order Status" and decided to exclude nulls in key calculations.  
- **Step 5**: Added measures to calculate average delivery time and order value while excluding incomplete or canceled orders.  
- **Step 6**: Used slicers for fields like "City," "Order Type," and "Payment Method" to allow dynamic filtering.  
- **Step 7**: Designed visuals:  
  - Two card visuals for total number of orders and average order value.  
  - Line chart representing order trends over different time periods (hourly, daily, weekly).  
  - Stacked bar chart to display delivery times segmented by city.  
- **Step 10**: Added KPIs for total number of unique customers and percentage of repeat customers using DAX.  
- **Step 11**: Published the report to Power BI Service for web accessibility and stakeholder reviews.  

---

### Snapshots  

#### dashboard :  
![WhatsApp Image 2024-12-18 at 16 58 34]![blinkit dashboard](https://github.com/user-attachments/assets/c10c1577-f165-44e1-84f3-56a544cba2a1)

 

#### Total sales each year:  
![WhatsApp Image 2024-12-18 at 16 58 34 (1)](https://github.com/user-attachments/assets/029e15b1-c98a-405f-8715-9e5b7a6318a7)


---

## Insights  

A single-page dashboard was created, published to Power BI Service, and analyzed for the following insights:  

### [1] Total Orders and Customers  

- **Total Number of Orders**: 100,000  
- **Total Number of Unique Customers**: 25,000  
- **Repeat Orders**: 40%  

### [2] Delivery Performance  

- **Average Delivery Time**: 25 minutes  
- **Percentage of Orders Delivered in Under 20 Minutes**: 60%  
- **Delivery Delays Beyond 30 Minutes**: 15%  

### [3] Peak Order Times  

- Morning: 10% of orders  
- Afternoon: 25% of orders  
- Evening: 45% of orders  
- Night: 20% of orders  

### [4] Customer Preferences  

- **Most Ordered Categories**:  
  - Grocery (40%)  
  - Beverages (25%)  
  - Snacks (20%)  
  - Personal Care (15%)  
- **Payment Methods**:  
  - Online Payments: 70%  
  - Cash on Delivery: 30%  

---

By addressing inefficiencies in delivery and item availability, Blinkit can achieve higher customer satisfaction and better operational outcomes.
