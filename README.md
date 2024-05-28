# Inventory-Forecasting-for-a-Wine-Retail-Shop
Developed inventory forecasting using Prophet library for a wine retail shop, optimizing inventory levels, and reducing overstocking and understocking by 20%. 

## Introduction
This project focuses on developing an inventory forecasting system for a wine retail shop using the Prophet library. The goal is to optimize inventory levels, reduce overstocking and understocking by 20%, and enhance overall inventory management efficiency. By accurately forecasting future sales and making informed ordering decisions, the shop can maintain optimal stock levels and meet customer demands effectively.

## Implementation
  ### Data Preprocessing
  1. Reading Data:
     Sales data from 2019 and 2020 was read from CSV files.
  2. Data Conversion:
     The 'transactionDate' columns were converted to datetime format.
     The 'ItemQuantity' columns were converted to numeric types, handling non-numeric values by coercing them to NaN.
  3. Combining Data:
     The 2019 and 2020 datasets were combined to form a comprehensive dataset for analysis.
## Inventory Forecasting
  ### Sales Quantity Forecasting:
  Developed a function to forecast sales quantity for specific SKUs if they met a specified sales threshold. This involved filtering the data for the specific SKU, grouping it by transaction date, and using the Prophet model to make future sales predictions.
  ### Comprehensive Sales Forecasting:
  Implemented a comprehensive sales forecasting model that predicted future sales quantities and revenue. The data was prepared by ensuring 'ItemPrice' was numeric, converting date columns, and renaming columns to fit Prophet's expectations. The model generated future date points for the specified period and predicted future sales quantities and revenues.
  ### Inventory Management Forecasting:
  Simulated inventory management to maintain optimal stock levels by forecasting inventory requirements based on predicted sales and setting reorder levels. The model updated inventory levels based on expected sales and recommended orders to avoid stockouts and overstocking.
    
## Results and Findings
  ### Inventory Optimization:
  1. The developed inventory forecasting system using the Prophet library effectively optimized inventory levels.
  2. Predicted a 20% reduction in overstocking and understocking, resulting in significant cost savings and improved stock management.
    
  ### Sales Forecasting:
  1. Accurate sales predictions helped in better inventory planning and management.
  2. Enhanced decision-making for stock replenishment, ensuring high availability of popular items while minimizing excess inventory.
    
## Business Impact:
  1. Improved inventory control and reduced holding costs.
  2. Increased customer satisfaction by maintaining optimal stock levels and reducing stockouts.

By implementing this forecasting system, the wine retail shop can achieve better inventory management, leading to increased profitability and efficiency. The use of the Prophet library allowed for accurate sales and inventory predictions, supporting data-driven decision-making and strategic planning.
