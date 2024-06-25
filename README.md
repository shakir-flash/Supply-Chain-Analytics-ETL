# Supply-Chain-Analytics

![supply chain image](https://github.com/shakir-flash/Supply-Chain-Analytics-ETL/assets/59859522/4ce3eaf4-13a2-46e7-aa1b-3b33d3f3c54f)

## Overview
This project focuses on analyzing and visualizing the supply chain data for a fashion and makeup product company. The dataset includes various aspects of the supply chain process, such as product details, sales, revenue, customer demographics, inventory levels, lead times, shipping information, supplier details, and more.

The workflow consists of three main stages: Extract, Transform, and Load (ETL) the data using Python, loading the transformed data into Snowflake, and creating a dashboard in Power BI for visualization.

## Dataset Overview
The dataset contains the following features related to the supply chain:

- **Product Type**: Category of the product (e.g., clothing, accessories, makeup).
- **SKU**: Stock Keeping Unit, a unique identifier for each product.
- **Price**: Price of the product.
- **Availability**: Current availability status of the product.
- **Number of Products Sold**: Number of products sold over a given period.
- **Revenue Generated**: Total revenue from product sales.
- **Customer Demographics**: Information about customers, such as age, gender, location, etc.
- **Stock Levels**: Quantity of each product available in inventory.
- **Lead Times**: Time taken for an order to be fulfilled from the supplier to the customer.
- **Order Quantities**: Number of products ordered in each transaction.
- **Shipping Times**: Time taken to ship products to customers.
- **Shipping Carriers**: Companies responsible for shipping the products.
- **Shipping Costs**: Costs incurred for shipping each product.
- **Supplier Name**: Name of the supplier providing the products.
- **Location**: Location of the supplier.
- **Production Volumes**: Volume of products manufactured.
- **Manufacturing Lead Time**: Time taken for the manufacturing process.
- **Manufacturing Costs**: Costs incurred during the manufacturing process.
- **Inspection Results**: Results of quality inspections for products.
- **Defect Rates**: Percentage of defective products.
- **Transportation Modes**: Modes of transportation used to deliver products.
- **Routes**: Transportation routes taken for delivery.
- **Costs**: Various costs associated with the supply chain process.

## Visualizations from Dashboard

### Dashboard of overall status:
![image](https://github.com/shakir-flash/Supply-Chain-Analytics-ETL/assets/59859522/bb51d2c4-3d4f-422f-aff7-d2860292ee9b)

### Revenue Analysis
![image](https://github.com/shakir-flash/Supply-Chain-Analytics-ETL/assets/59859522/2a772f85-5280-45e2-aa25-e253aac43b5b)

### Supply Chain Analysis
![image](https://github.com/shakir-flash/Supply-Chain-Analytics-ETL/assets/59859522/3c7953b2-2402-466f-af9e-e87e7cdf70ca)


## Project Steps
### Step 1: Extract, Transform, and Load (ETL)
- **Data Extraction**: Source the dataset from a specific location or file (e.g., CSV or Excel file).
- **Data Cleaning and Transformation**: Use Python to clean the data and handle missing values, making it suitable for analysis.
- **Data Integration**: Integrate data from different sources into a cohesive dataset.
- **Data Loading into Snowflake**: Load the transformed dataset into the Snowflake data warehouse for efficient storage and processing.

### Step 2: Data Visualization with Power BI
- **Data Connection**: Connect Power BI to the Snowflake data warehouse to access the dataset.
- **Dashboard Creation**: Create a comprehensive dashboard in Power BI, showcasing various supply chain metrics and KPIs with interactive visualizations like charts, graphs, tables, and maps.
- **Data Insights**: Use the Power BI dashboard to gain insights into the supply chain process, identify trends, and make data-driven decisions to optimize operations.

## Project Structure
The project repository includes the following structure:

- README.md
- data/
  - processed/
    - processed_data.csv
  - raw/
    - supply_chain_data.xlsx
- script/
  - ETL.py
  - snowflake_utils.py
- power_bi/
  - supply_chain_dashboard.pbix

## Getting Started
1. Clone the repository to your local machine.
2. Ensure you have Python and the required libraries installed.
3. Run the ETL script (ETL_script.py) to perform data extraction, transformation, and loading into Snowflake.
4. Connect Power BI to Snowflake using the provided connection credentials (snowflake_connection_credentials.json).
5. Open the Power BI file (supply_chain_dashboard.pbix) to explore the supply chain dashboard.

## Conclusion
This project demonstrates the use of ETL processes to handle supply chain data, loading it into Snowflake, and creating an interactive dashboard with Power BI. The dashboard provides valuable insights into the supply chain, helping users make informed decisions to enhance overall efficiency.
