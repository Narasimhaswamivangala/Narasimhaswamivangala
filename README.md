# CRM Sales Analysis Project

This project provides a comprehensive CRM system for sales analysis using SQL and PL/SQL.

## Project Structure

- **sql/**: Directory containing SQL scripts.
  - `create_tables.sql`: Script to create the necessary tables.
  - `insert_data.sql`: Script to insert sample data.
  - `sales_growth_analysis.sql`: PL/SQL block for calculating sales growth.

## Setup Instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/CRM-Sales-Analysis-Project.git
    cd CRM-Sales-Analysis-Project
    ```

2. Run the SQL scripts in your Oracle database:
    ```sh
    sqlplus your_username/your_password@your_database @sql/create_tables.sql
    sqlplus your_username/your_password@your_database @sql/insert_data.sql
    sqlplus your_username/your_password@your_database @sql/sales_growth_analysis.sql
    ```

## Usage

- **create_tables.sql**: Run this script to create the `Customers`, `Products`, and `Sales` tables.
- **insert_data.sql**: Run this script to insert sample data into the tables.
- **sales_growth_analysis.sql**: Run this script to calculate and output the sales growth.

## License

[MIT](LICENSE)
