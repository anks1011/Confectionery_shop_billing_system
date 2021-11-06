# Confectionery_shop_billing_system
DBMS
Confectionery Shop Billing System
By: Ankit Singh and Atifa Naaz
 
Introduction
The Confectionary Shop Billing System is a simple PHP/MySQLi project that can help certain shops to manage their customer's bills and receipts. This system stores the list of menus or products that the shop serves with their price and the product list are organized by category. The Shop will take the orders of their customer then the cashier or the order encoder can choose customers who will pay as they order. To track the order of the customers the shop will provide a bill number per order same as the common process of some shops, fast food, restaurants, or cafes. The Confectionary Shop Billing System generates also a monthly sales report. The system has a simple calculator for payout transactions which means the user will only input the amount tendered of the customer then the system will calculate the change of the customer.
Features:
●	Login Page
○	The page where the system admin or user submits their system credential to access the data and functionalities of the Confectionery Shop billing system.
●	Home Page
○	The page where the system users will be redirected by default when logging into the system.
●	Categories Page
○	The page where the admin manages the list of menu or product categories.
●	Make Bill Page
○	The page where the cashier, admin, or user will make bills for the customers.
●	Bill Page
○	The page where the list of bills is listed and managed.
●	Sales Report Page
○	The page where the monthly sales report is shown and ready to print.
●	Users Page
○	The page where the system admin manages the list of cafe billing system users.
The Cafe Billing System was developed using HTML, PHP/MySQLi, CSS, JavaScript (jQuery/Ajax), and Bootstrap5.0 for the design.
How to Run
●	Open the web-server database and create a new database named cafe_billing_db.
●	Import the SQL file located in the database folder of the source code.
●	Copy and paste the source code to the location where your local web server accessing your local projects. Example for XAMPP('C:\mampp\htdocs')
●	Open a web browser and browse the project. E.g [ http://localhost:8888/confectionery-shop-billing-system ]





 Tables             
                           Database Name: cs_billing_system
 users                              
   id
  name
 username
password
  type

    billed-items
id
bill-id
product-id
qty
price
amount


 system-setting                              
  id
 name
 email
contact


      products
id
category-id
 name
qty
price
amount


	categories
id
name
description
         







               bills
id
ref_no
total_amount
amount_tenderd
bill_number
date_created





Entity Relationship Diagram    
 
User
•	User is of two types:
o	Admin
o	Staff
      Admin: -
	Admin can login and logout.
	Admin can add or remove staff.
	Admin manages product and categories.
	Admin can generate and update bills.
	Admin can access sells report.
     Staff: -
	Staff can login and logout.
	Staff can generate and update bills.
	Staff can access sells report.

![image](https://user-images.githubusercontent.com/76167572/140610091-771a24bd-c460-482a-9e3c-f112639896b6.png)
