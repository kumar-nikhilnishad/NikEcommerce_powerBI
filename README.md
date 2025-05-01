![Retail_store_sales_dashboard](https://github.com/user-attachments/assets/9f277896-8f44-489b-9723-8e973ce28456)

## Sales & Customer Order Analysis System

### 1. Objective
To analyze customer orders, sales, profit trends, and product performance across different states and payment modes, enabling the business to make informed decisions and drive revenue growth.
________________________________________
### 2. Tools and Technologies Used
•	Database: PostgreSQL 

•	Data Visualization: Power BI

•	Languages: SQL
________________________________________
### 3. Data Sources
•	Orders.csv (Order ID, Order Date, Customer Name, State, City)

•	Details.csv (Order ID, Amount, Profit, Quantity, Category, Sub-Category, Payment Mode)
________________________________________
## 4. Project Approach
✅ Step 1: Data Modeling

•	Designed relational schema with two tables (Orders, Details)

•	Set up Primary Key (OrderID) and Foreign Key 
(OrderID)

✅ Step 2: Data Cleaning

•	Standardized column names and formats

•	Checked for duplicate OrderIDs and removed them

✅ Step 3: SQL Query Building

•	Built KPIs:

o	Total Sales

o	Total Profit

o	Total Orders

o	Top Customers

o	Sales by State

o	Payment Mode Popularity

o	Monthly Sales Trends

✅ Step 4: Dashboard Creation in Power BI

•	Connected SQL data to Power BI

•	Designed a professional dashboard layout:

o	Cards for KPIs

o	Stacked bar chart for Sales by States and Monthly Profit

o	Pie chart for payment modes

o	Line chart for monthly trends

o	Bar charts for customer and category analysis

•	Added slicers for State, Year, and Category to 
make the dashboard interactive

✅ Step 5: Insights Generation

•	Identified top-performing states and cities

•	Found that COD and UPI were the most popular payment modes

•	Determined the most profitable categories

•	Observed seasonal trends in customer purchasing behavior
________________________________________
## 5. Key SQL Queries Used
•	Total Sales and Profit

•	Sales by State

•	Top Customers

•	Payment Mode Usage

•	Monthly Sales Trend
________________________________________
## 6. Challenges Faced
•	Handling missing values in City and State data.

•	Ensuring data type consistency for date fields during database import.
________________________________________
## 7. Business Impact
•	Helped stakeholders understand key customer segments.

•	Provided clear visibility into product performance by category.

•	Improved decision-making on marketing and product strategy based on real data.
________________________________________
## 8. Conclusion
The Sales & Customer Order Analysis System successfully provided critical insights into sales, profitability, and customer behavior.
The interactive dashboard allowed business users to filter data by state, year, and category for more detailed analysis.


💬 Always happy to connect with fellow data enthusiasts and professionals!

