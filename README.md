# E-Commerce Data Analysis: Revenue Insights

## Project Overview

This project analyzes a fictional e-commerce dataset to understand **revenue generation** across **product categories**, **customer segments**, and **locations**. The objective is to practice **data cleaning**, **feature engineering**, **exploratory data analysis (EDA)**, and **visualization** using Python.

The dataset was created to simulate real-world e-commerce scenarios, including **order returns**, **discounts**, and **variations in customer behavior**.

## Dataset Description

The dataset contains the following columns:

**OrderID** — Unique identifier for each order  
**CustomerID** — Unique identifier for each customer  
**OrderDate** — Date when the order was placed  
**ProductID** — Unique identifier for each product  
**ProductCategory** — Category of the product  
**ProductName** — Name of the product  
**Quantity** — Number of units ordered  
**PricePerUnit** — Price per unit of the product  
**PaymentMethod** — Method of payment used  
**OrderStatus** — Status of the order (e.g., Completed, Pending)  
**CustomerLocation** — Location of the customer  
**CustomerSegment** — Type of customer (e.g., New, Returning)  
**DiscountApplied** — Discount applied on the order  
**DeliveryTime(days)** — Delivery time in days  
**IsReturned** — Indicates whether the order was returned  
**TotalAmount** — Total amount generated from the order  

Additionally, a derived column **Revenue** was calculated as:  
Revenue = Quantity * PricePerUnit * (1 - DiscountApplied)

## Tools and Libraries

**Python**  
**Pandas**  
**NumPy**  
**Matplotlib**

## Analysis Highlights

Explored **revenue trends** by **Product Category**, **Customer Segment**, and **Customer Location**.  
Created **visualizations**, including **bar charts** and **pie charts**, to highlight patterns in the data.  
Identified the **key contributors to revenue** within the dataset.

## Key Insights

**Top Product Category:** Electronics  
**Highest Revenue Customer Segment:** New Customers  
**Highest Revenue Location:** Delhi

## Lessons Learned

**Data cleaning** and **feature engineering** are crucial for obtaining meaningful insights.  
**Visualizations** are effective tools for interpreting and communicating data trends.  
**Formulating the right questions** is essential for focused and actionable analysis.

## How to Run

Clone the repository:  
`git clone https://github.com/medisumeet/E-Commerce-Data-Analysis.git`

Install the required Python libraries:  
`pip install pandas numpy matplotlib`

Open the Jupyter notebook and execute the cells to explore the analysis.

## Feedback

This is my **first data analysis project**. I welcome **feedback** and **suggestions** on improvements, additional insights to explore, and approaches to working with **complex or messy datasets**.
