# BeautyBliss-Online Cosmetic Shopping Website
BeautyBliss is an online cosmetic shopping website developed with the intention of trying to build a fully functional website with an integrated database. The purpose of this repository is to provide an overview of the project, its functionalities, and instructions on how to set it up locally.

## Project Overview
BeautyBliss is an e-commerce website designed to provide a seamless shopping experience for cosmetic enthusiasts. It allows users to browse a wide range of cosmetic products, choose variants, and easily place orders. The project also includes an administrative panel for managing inventory, brands, sales reports, and order statuses.

## Key Features
### 1. User Registration and Authentication:

+ Users can create new accounts or log in with existing ones.
+ Passwords are securely stored using encryption techniques.
+ User authentication ensures secure access to user-specific data.
  
### 2. Product Catalog:

+ Extensive collection of cosmetic products with various categories.
+ Users can conveniently browse, filter, and search for products.
+ Detailed product pages provide comprehensive information, including descriptions, images, and customer reviews.
  
### 3.Shopping Cart and Checkout:

+ Users can add products to their shopping cart and manage quantities.
+ The shopping cart is persisted across sessions for a seamless shopping experience.
+ Secure checkout process with multiple payment options.
  
### 4.Admin Panel:

+ Administrative access for managing inventory, brands, and order statuses.
+ Sales reports provide insights into revenue and popular products.
+ Efficient order management system to track delivery statuses.

## Local Setup
To run the BeautyBliss project locally, follow these steps:

### Install XAMPP:

+ Download and install XAMPP, a web development environment that includes Apache, MySQL, and PHP.
+ Visit the official XAMPP website (https://www.apachefriends.org) and follow the installation instructions for your operating system.
Clone the Repository:

+ Clone this repository to your local machine using Git or download the ZIP file and extract it.
```
git clone https://github.com/khushi0706/BeautyBliss-ShoppingWebsite
```
### Start XAMPP:

+ Launch XAMPP and start the Apache and MySQL services.
### Import the Database:

+ Open phpMyAdmin in your web browser by visiting http://localhost/phpmyadmin.
+ Create a new database named "cbpos_db".
+ Import the database dump file provided in the repository (cbpos_db.sql) into the newly created database.
### Run the Application:

+ Place the repository files in the appropriate directory of your local web server (in XAMPP's htdocs folder).
+ Open your web browser and visit `http://localhost/cbpos` to access the application.
### Admin Access:

+ To access the admin panel, use the following credentials:
+ `Username: admin` `Password: admin123`

## Screenshots 

### CLIENT'S SIDE PORTAL
![pic1](https://github.com/khushi0706/BeautyBliss-ShoppingWebsite/assets/96778933/200d1457-2a5f-4e39-9409-67300766b5e6)
![pic2](https://github.com/khushi0706/BeautyBliss-ShoppingWebsite/assets/96778933/dbac33c5-e8ca-402c-a91f-082221150472)
### ADMIN'S SIDE PORTAL
![pic3_adminPg](https://github.com/khushi0706/BeautyBliss-ShoppingWebsite/assets/96778933/d818954f-7d99-409e-9ce1-c13ff535436b)
![pic4](https://github.com/khushi0706/BeautyBliss-ShoppingWebsite/assets/96778933/eae5d03e-a393-41d6-a86d-f9de4c6843f9)


**Thank You for Visiting this repository, feel free to issue a pull request!!**
