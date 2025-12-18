# Lenskart Sales Analysis Dashboard – Project Report

## 1. Project Overview

This project focuses on analyzing **Lenskart sales and customer data** using **Power BI** to gain actionable business insights. The dashboard provides a clear view of customer behavior, product performance, sales channels, and payment preferences to support data-driven decision-making.

---

## 2. Objectives of the Project

The main objectives of this project are:

* To analyze overall sales performance
* To understand customer demographics and behavior
* To identify top-performing products and brands
* To evaluate sales channels and payment modes
* To build an interactive and visually appealing dashboard for stakeholders

---

## 3. Dataset Description

The dataset contains sales-related information from Lenskart. Key fields include:

* Customer_ID
* Customer_Age
* Gender
* Customer_Segment (New, Premium, Repeat)
* Product_Category (Contact Lenses, Sunglasses, Eyeglasses)
* Brand (Lenskart Air, John Jacobs, Vincent Chase)
* Sales_Channel (Website, Store, App)
* Payment_Mode (Cash, Card, UPI)
* Prescription_Type (Power, Zero Power)
* Quantity
* Unit_Price
* Cost_Price
* Order_Status

The dataset was cleaned and transformed before analysis.

---

## 4. Tools & Technologies Used

* **Power BI Desktop** – Data visualization and dashboard creation
* **DAX (Data Analysis Expressions)** – Measures and calculated columns
* **Microsoft Excel** – Initial data storage and formatting

---

## 5. Data Preparation & Modeling

The following steps were performed:

* Removed inconsistencies and ensured correct data types
* Created calculated columns for age grouping
* Created DAX measures for KPIs such as Total Sales and Total Orders
* Applied proper sorting using numeric sort columns
* Built relationships (if required) for smooth analysis

### Sample DAX Calculations

```DAX
Age_Group = INT ( lenskart_sales[customer_Age] / 10 ) * 10

Total Sales = SUM ( lenskart_sales[Sales_Amount] )

Total Orders = DISTINCTCOUNT ( lenskart_sales[Customer_ID] )
```

---

## 6. Dashboard Design & Visuals

The dashboard includes the following visuals:

### KPI Cards

* Sum of Cost Price
* Count of Customers
* Sum of Quantity
* Sum of Unit Price

### Charts & Graphs

* Customer count by **Customer Segment**
* Customer distribution by **Gender**
* Customer count by **Brand**
* Customer count by **Product Category**
* Customer count by **Payment Mode**
* Customer count by **Sales Channel**
* Customer distribution by **Prescription Type**

### Table Visual

* Detailed customer-level information including age, gender, payment mode, and order status

---

## 7. Key Insights

* Premium and repeat customers contribute significantly to overall sales
* Female and male customers show nearly balanced participation
* Contact lenses are the most popular product category
* Website is the most preferred sales channel
* Card and UPI are widely used payment methods
* Power prescription products have slightly higher demand compared to zero power

---

## 8. Business Impact

This dashboard helps:

* Management understand customer preferences
* Identify high-performing products and brands
* Optimize sales channels and payment strategies
* Improve marketing and customer targeting decisions

---

## 9. Conclusion

The Lenskart Sales Analysis Dashboard demonstrates how **Power BI and DAX** can be effectively used to convert raw sales data into meaningful insights. This project highlights strong skills in data analysis, visualization, and business storytelling.



