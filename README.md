# PowerBI Sales Dashboard

This repository contains the data sources and documentation for a Power BI sales analytics dashboard.

## Overview

The dashboard visualizes sales metrics across:
- **Total Sales**: 102.53K
- **Customer Count**: 12 unique customers
- **Sales by Country**: United States, China, Germany, India, OK
- **Sales by Product**: Dell XPS 15, ThinkPad X1, Galaxy S24, HP Spectre x360, and more
- **Product Categories**: Laptop, Smartphone, Tablet, Smart Home, Accessory

## Data Files

### Orders.csv
Contains transaction-level order data:
- OrderID: Unique order identifier
- ProductID: Product reference
- CustomerID: Customer reference
- SalesPersonID: Sales representative
- OrderDate: Order placement date
- ShipDate: Shipment date
- OrderStatus: Delivered or Shipped
- ShipAddress: Shipping address
- BillAddress: Billing address
- Quantity: Order quantity
- Sales: Sales amount
- CreationTime: Record creation timestamp

### Customers.csv
Contains customer master data:
- CustomerID: Unique customer identifier
- FirstName: Customer first name
- LastName: Customer last name
- Country: Customer country
- Score: Customer loyalty/engagement score

## Dashboard Visualizations

1. **Sum of Sales by Country** - Bar chart showing sales distribution across countries
2. **Sum of Sales by Product Name** - Horizontal bar chart ranking products by sales
3. **Sum of Sales by Product Category** - Pie chart showing category breakdown
4. **Sum of Sales by Customer ID** - Bar chart analyzing customer purchasing patterns

## Key Metrics

- **Total Sales**: $102.53K
- **Unique Customers**: 12
- **Top Country**: United States
- **Top Product**: Dell XPS 15
- **Top Category**: Laptop (51.14%)

## Usage

Import the CSV files into Power BI Desktop:
1. Open Power BI Desktop
2. Get Data → CSV
3. Load `Orders.csv` and `Customers.csv`
4. Create relationships between tables using CustomerID and ProductID
5. Build visualizations based on the dashboard specifications

## Author

BhumitJ7
