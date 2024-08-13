# Inventory-Management
A data analysis project for managing and analyzing inventory data.
---

## Project Overview
The **Inventory Management** project is a data analysis tool developed using Google Sheets (Spreadsheet) to efficiently track and manage inventory levels. It is designed to help users monitor stock levels, reorder requirements, and product locations within a store, ensuring smooth inventory operations.

## Features

### 1. Product Search
- **Search Products:** Quickly search for any product using its Product ID.
- **Stock Information:** View available stock, location within the store, reorder level, and whether a reorder is required.
  
  Example:
  - **Product ID:** 10010
  - **Product Name:** Product-10
  - **Available Stocks:** 57
  - **Location (Within Store):** D10
  - **Re-order Level:** 24
  - **Re-order Required:** No

### 2. Inventory Summary
- **Comprehensive Summary:** Displays a summary of all products as of the current date.
- **Key Metrics:** Shows opening balance, quantities added (In), quantities removed (Out), closing balance, reorder level, and whether a reorder is necessary.
  
  Example:
  | Date       | Product ID | Product Name  | Opening Balance | In | Out | Closing Balance | Re-order Level | Re-order Required |
  |------------|------------|---------------|-----------------|----|-----|----------------|----------------|-------------------|
  | 12/7/2023  | 10001      | Product-1     | 30              | 0  | 0   | 30             | 40             | Yes               |
  | 12/7/2023  | 10002      | Product-2     | 10              | 35 | 0   | 45             | 39             | No                |

### 3. Input Sheet
- **Transaction Entry:** Users can enter transaction data for both incoming (In) and outgoing (Out) quantities.
  
  Example:
  | Date       | Product ID | Product Name  | Transaction Type | Qty |
  |------------|------------|---------------|------------------|-----|
  | 12/1/2023  | 10001      | Product-1     | In               | 100 |
  | 12/2/2023  | 10001      | Product-1     | Out              | 70  |

### 4. Product Master
- **Product Details Maintenance:** Keep track of product details, including location within the store and reorder levels.
  
  Example:
  | Product ID | Product Name | Location (within Store) | Re-order Level |
  |------------|--------------|-------------------------|----------------|
  | 10001      | Product-1    | D1                      | 40             |
  | 10002      | Product-2    | D2                      | 39             |

## How to Use
1. **Product Search:** Use the "Product Search" feature to look up any product by its ID and view the relevant stock details.
2. **Inventory Summary:** Visit the "Inventory Summary" tab to see an overview of all inventory items as of the latest date.
3. **Input Sheet:** Enter transaction data in the "Input Sheet" for stock movements (In/Out).
4. **Product Master:** Update and maintain product details, such as location and reorder level, in the "Product Master" sheet.

## Conclusion
This **Inventory Management** tool is a simple yet powerful solution for managing inventory using Google Sheets. It is ideal for small to medium-sized stores looking to streamline their inventory processes.

---
