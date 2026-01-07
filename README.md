# Excel Inventory Management System

## Overview

This project is an Excel-based inventory management system designed to track products, suppliers, stock levels, reorder needs, and order summaries in one place.

It focuses on clarity, automation, and decision support rather than complex tooling.  
Everything runs inside Excel using formulas, structured tables, and conditional logic.

![Screenshot 2025-12-30 141345](https://github.com/user-attachments/assets/22334d41-3e9e-498e-bca8-a5d37e1f4ef7)
![Screenshot 2025-12-30 141520](https://github.com/user-attachments/assets/926362e5-6aa6-4f27-9dca-0bc07eb88dad)
![Screenshot 2025-12-30 141610](https://github.com/user-attachments/assets/4c3cb83d-3dfc-43de-8df5-73bd6ca99bbf)



## Features

### Inventory Dashboard
- Total inventory value
- Number of unique products
- Current date and day tracking
- Real-time stock visibility

### Inventory Tracking
- Product ID and product name
- Quantity in stock
- Cost price and sale price per unit
- Automatically calculated total value per product
- Reorder threshold tracking
- Visual reorder alerts
- Estimated time of arrival (ETA) for restocks

### Vendor & Supplier Management
- Product type categorization
- Supplier details
- Average order lead time
- Reorder quantity per product
- Contact person information
- Supplier email and website reference

### Reorder & Order Summary
- Automatic identification of products below reorder threshold
- Order summary with:
  - Products to reorder
  - Revision rounds
  - Total cost per item
  - Supplier contact details
- Total order cost calculation

## System Structure

The workbook is organized into logical sections:

- **Inventory Sheet**
  - Core stock and pricing data
  - Reorder logic and alerts

- **Vendor Info Sheet**
  - Supplier metadata
  - Lead times and reorder quantities

- **Order Summary Sheet**
  - Aggregated reorder list
  - Cost calculations
  - Supplier contact references

## Logic & Automation

- Conditional formatting highlights products that need reordering
- Reorder status is calculated based on:
  - Quantity in stock
  - Defined reorder threshold
- Inventory value is automatically updated using unit cost and quantity
- Order totals are dynamically calculated from selected reorder items

No macros are required.  
All automation is formula-based for transparency and ease of modification.

## Use Cases

- Small to medium businesses
- Retail inventory tracking
- Personal inventory projects
- Excel portfolio projects
- Operations and supply chain demonstrations

## Tools Used

- Microsoft Excel
- Structured tables
- Excel formulas
- Conditional formatting

## How to Use

1. Update product and stock quantities in the Inventory sheet
2. Adjust reorder thresholds as needed
3. Maintain supplier details in the Vendor Info sheet
4. Review the Order Summary to identify restock needs
5. Use supplier contacts directly from the workbook for ordering

## Project Purpose

This project demonstrates:
- Inventory logic design
- Spreadsheet-based system thinking
- Data organization and automation in Excel
- Practical operations tracking without external tools

## Future Improvements

- Power Query integration for supplier imports
- Pivot-based reporting
- Dashboard visualizations
- Power BI connection
- VBA automation (optional)

## Author

Built as a practical inventory management and analytics project using Excel.

If you’re interested in similar systems, analytics-driven workflows, or process optimization, feel free to reach out.
