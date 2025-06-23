# Real-time Inventory Optimization Dashboard

## Project Overview
This project is designed to analyze and visualize inventory data in real-time using Power BI. A dynamic connection to a Google Sheets dataset enables automatic updates to the dashboard, making it suitable for practical use in retail, office supply, or warehouse environments.

The dataset tracks multiple parameters for 20 unique products, including:
- **Product ID and name**
- **Category** (Electronics, Furniture, Stationery, etc.)
- **Current stock** and **minimum stock levels**
- **Last restock date**
- **Supplier name**
- **Reorder status** (Yes/No)

## Real-Time Data Integration
Instead of using static Excel files, the inventory data is maintained in a **live Google Sheet**, which is connected to Power BI using a published `.csv` web link. This setup:

- Eliminates the need for manual data refreshes  
- Simulates a real-time environment  
- Enables version-free, cloud-based updates without breaking the model  

## Insights Derived
Some of the actionable insights from this dashboard include:
- **Products that require immediate reorder** based on minimum threshold logic  
- **Categories most at risk of stockouts**  
- **Supplier-wise inventory responsibilities**  
- **Recent restock patterns** (by date or by supplier)  
- **Overall inventory health** across departments  

## Power BI Screenshots

#### 🔹 Dashboard View 1
![Screenshot (1)](https://github.com/user-attachments/assets/920b0395-3ac0-49a6-b0f0-8948481c684c)

#### 🔹 Dashboard View 2
![Screenshot (2)](https://github.com/user-attachments/assets/4d6546f2-7d16-4dbc-a3c6-7ba76f53fa2c)

### Dataset
https://docs.google.com/spreadsheets/d/1UgunsCpiBfrUGC6CsE3Dxjoa8g8DKyi_uC_-XtdbrBU/edit?usp=sharing
