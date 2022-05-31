# Shoe-Shop-Application-OOP-SQL-Database-
A application for an online shoe retailer. The application uses object oriented programming in python and sqlite package. 
## Usage
To use this application, a customer/user has to create an account to the store using the create account function.

This creates an account for the user as an object of either the Customer or PremiumCustomer class. 

Once a user has an account, they must login using the login class instance method before they are able to use any of the other applications features. A user may log out at any time using the logout class instance method. 

Once a user is logged in they may search for, buy or return shoes using the search, buy_shoes and return_product methods. 

Users can then see all their previous orders or returns using the view_all_orders or view_returned_orders method respectively. 

Each shoe is set up as an object of class Shoes. The stock of a shoe may be checked using the class instance method check_stock. Stock is automatically updated when orders/returns are processed. New stock can be added using the new_stock method.  

## Database

A database named shoe_shop.db contains all the information regarding customers, stock levels and orders and returns.

This information is contained within three tables (Customers, Stock and Orders). The database is automatically updated as the information changes so should always be up to date. 
