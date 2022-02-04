# MySQL
This repository contains MySQL file which solves some questions related to the dataset.

Datasets:
### 1. HR Database
HR that manages the HR data of the small businesses.
![image](https://user-images.githubusercontent.com/70515377/152560588-5242b21e-325f-4703-85d9-b0aea7981f3b.png)

The HR sample database has seven tables:
1. The employees table stores the data of employees.
2. The jobs table stores the job data including job title and salary range.
3. The departments table stores department data.
4. The dependents table stores the employee’s dependents.
5. The locations table stores the location of the departments of the company.
6. The countries table stores the data of countries where the company is doing business.
7. The regions table stores the data of regions such as Asia, Europe, America, and the Middle East and Africa. The countries are grouped into regions.


### 1. Superstores Database
The databse is all about sales transactions of a superstore. It has five tables maintaing records respectively. 
The tables are as follows :
	1. cust_dimen: Details of all the customers
			Customer_Name (TEXT): Name of the customer
			Province (TEXT): Province of the customer
			Region (TEXT): Region of the customer
			Customer_Segment (TEXT): Segment of the customer
			Cust_id (TEXT): Unique Customer ID
	
    2. market_fact: Details of every order item sold
        Ord_id (TEXT): Order ID
        Prod_id (TEXT): Prod ID
        Ship_id (TEXT): Shipment ID
        Cust_id (TEXT): Customer ID
        Sales (DOUBLE): Sales from the Item sold
        Discount (DOUBLE): Discount on the Item sold
        Order_Quantity (INT): Order Quantity of the Item sold
        Profit (DOUBLE): Profit from the Item sold
        Shipping_Cost (DOUBLE): Shipping Cost of the Item sold
        Product_Base_Margin (DOUBLE): Product Base Margin on the Item sold
        
    3. orders_dimen: Details of every order placed
			Order_ID (INT): Order ID
			Order_Date (TEXT): Order Date
			Order_Priority (TEXT): Priority of the Order
			Ord_id (TEXT): Unique Order ID
	
    4. prod_dimen: Details of product category and sub category
			Product_Category (TEXT): Product Category
			Product_Sub_Category (TEXT): Product Sub Category
			Prod_id (TEXT): Unique Product ID
	
    5. shipping_dimen: Details of shipping of orders
			Order_ID (INT): Order ID
			Ship_Mode (TEXT): Shipping Mode
			Ship_Date (TEXT): Shipping Date
			Ship_id (TEXT): Unique Shipment ID
