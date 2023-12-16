# Shop Management System

## Overview

This Shop Management System is a Java-based application developed for the university capstone project. It serves as a prototype for managing a shop's(Product Dealer) inventory, sales, customer information, and product analysis. The application utilizes Java Swing for the graphical user interface and NetBeans IDE for development. The backend is supported by a MySQL database named `shop_manage`, containing tables for product analysis (`analysis_product`), customers (`customer`), products (`product`), and users (`user`).
## Contributors
   1. jahidul hassan reshad-0242220005341197
   2. Rokibul islam -0242220005341167
   3. Fahim Sahriar -0242220005341019
## Features

1. User Registration and Login:
   - Users can register by providing personal information.
   - Authentication is implemented through a username and password.

2. Home Page:
   - Upon login, users are redirected to the home page.
   - The home page displays navigation buttons for Inventory, Sell Product, Customer Info, Analysis, and Logout.

3. Inventory:
   - Users can add, edit, and delete products.
   - Each product includes details such as name, brand, box quantity, price, and description.

4. Sell Product:
   - Users can sell products one at a time.
   - Billing and multi-product sales are features planned for future development.

5. Customer Info:
   - Users can add, delete, and edit customer information.
   - Customer details include name, shop name, address, and mobile number.

6. Analysis:
   - Users can view the best-selling products.
   - Product analysis is based on the `analysis_product` table.

7. Logout:
   - Users can safely log out from the system.

## Database Structure

The MySQL database `shop_manage` contains the following tables:
- `analysis_product`: Stores product analysis data.
- `customer`: Manages customer information.
- `product`: Holds details of shop products.
- `user`: Stores user registration information.

## How to Use

1. Clone the Repository:
   -First clone the repository .

2. Database Configuration:
   - Import the provided SQL script to set up the required tables and initial data. Scrippts are given in ,"MySQL_database" folder.

3. Open in NetBeans:
   - Open the project in NetBeans IDE.

4. Run the Application:
   - Build and run the application.

5. Login:
   - Use the provided user registration information to log in.
   - Username: 
   - Password: 

6. Explore and Test:
   - Navigate through different modules: Inventory, Sell Product, Customer Info, Analysis.
   - Test functionalities and provide feedback.

## Future Enhancements

- Implementing multi-product sales and final bill printing.
- Enhancing user interface and user experience.
- Bug fixes and optimizations.

Feel free to contribute to the project and provide suggestions for improvement.

Happy managing your shop with the Shop Management System!
