📊 RFM Customer Segmentation Project
📌 Project Overview

This project performs Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis on the Online Retail dataset.
The goal is to identify valuable customer groups and suggest business strategies for each segment.

🗂 Dataset

Online Retail Dataset (CSV format)

Contains transactional data including:

InvoiceNo

InvoiceDate

CustomerID

Quantity

UnitPrice

🧹 Data Cleaning

Removed null Invoice numbers

Removed cancelled orders (Invoice starting with "C")

Removed missing CustomerID

Converted InvoiceDate to datetime format

Created TotalPrice column

📈 RFM Calculation

Recency → Days since last purchase

Frequency → Number of unique invoices

Monetary → Total spending amount

Customers were scored using quantiles (1–5 scale).

🏷 Customer Segments

Champions

Loyal Customers

Potential Loyalists

New Customers

At Risk

Cannot Lose Them

Hibernating

📊 Visualization

A bar chart was created to show customer distribution across segments.

📁 Output

The final customer segmentation table is exported as:

Customer_RFM_Segmentation.csv

🎯 Business Value

This segmentation helps businesses:

Identify high-value customers

Improve retention strategies

Increase customer lifetime value

Run targeted marketing campaigns

🛠 Tools Used

Python

Pandas

NumPy

Matplotlib
