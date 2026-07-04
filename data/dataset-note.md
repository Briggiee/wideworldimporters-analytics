# Wide World Importers Dataset Note

## Source
The dataset used in this project was obtained from the **Wide World Importers** sample database backup available on **Kaggle**.

## Data Environment
The backup file was loaded into a SQL environment and used as the primary data source for this Power BI analytics project.

## Data Preparation Approach
The following steps were taken before dashboard development:

- Connected Power BI directly to the SQL database
- Selected only the relevant business tables required for analysis
- Removed unnecessary tables to reduce model complexity and improve performance
- Removed irrelevant columns in Power Query Editor
- Cleaned and transformed fields for reporting and KPI analysis
- Built relationships across the selected tables through data modeling
- Created DAX measures for revenue, customer analytics, supplier analysis, profitability, warehouse analysis, financial reporting and forecasting

## Main Data Domains Used
The project used a combination of data related to:

- Customers
- Orders
- Invoices
- Products / Stock Items
- Suppliers
- Purchase Orders
- Inventory / Warehouse
- Financial / Payment records
- Regional / country data

## Note
The full raw SQL backup file is not included in this repository due to size and because the project is intended to showcase the analytical workflow, dashboard solution and business insights rather than redistribute the original source database.
