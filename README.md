# Online Shop Management System (Oracle APEX)

An open-source, full-featured Online Shop Management System built with Oracle APEX. This project provides a robust foundation for building and managing e-commerce websites, complete with multi-role access, inventory management, and order processing.

## 📝 Description

This Online Shop Management System is a comprehensive web application designed for small to medium-sized businesses. It leverages the power of Oracle APEX to deliver a rich, interactive user experience with minimal coding. The system is divided into two main user roles: **Admins**, who manage the entire store, and **Customers**, who browse products and place orders. The backend is powered by a well-structured Oracle database schema (PL/SQL), ensuring data integrity and scalability. This project is ideal for developers looking to build a powerful e-commerce platform on the Oracle stack, for students learning about database-driven applications, or for businesses seeking a customizable online store solution.

## ✨ Features

* **User Authentication & Roles**: Secure login for both Admins and Customers.
* **Product & Inventory Management**: Admins can easily add, update, and delete products, categories, and brands. Inventory levels are automatically updated with each purchase.
* **Shopping Cart & Checkout**: A seamless shopping experience for customers to add items to their cart and proceed to checkout.
* **Order Tracking**: Customers can view their order history and track the status of their current orders.
* **Payment Record Handling**: Simple system to log payments against orders.
* **Admin Dashboard**: A comprehensive dashboard for admins featuring:
    * Sales charts (e.g., revenue over time).
    * Key performance indicators (KPIs).
    * Low stock alerts.
    * Top-selling products report.

## 🚀 Setup Instructions

Follow these steps to get the application running in your own Oracle APEX environment.

### Prerequisites

* **Oracle Database**: 19c or later.
* **Oracle APEX**: Version 21.2 or later.
* A configured Oracle APEX workspace.
* SQL*Plus or any other SQL client to connect to your Oracle Database.

### 1. Setup the Database Schema

First, you need to create the database objects.

1.  Connect to your Oracle Database schema/user using a tool like SQL*Plus or SQL Developer.
2.  Run the script located at `database/schema.sql`. This will create all the necessary tables, sequences, and sample data.

### 2. Import the APEX Application

Next, import the main application into your APEX workspace.

1.  Log in to your Oracle APEX workspace.
2.  Click on **App Builder** > **Import**.
3.  Choose the `apex-export/online-shop-app.sql` file from this repository.
4.  Follow the on-screen prompts to complete the installation. APEX will guide you through the process of mapping the imported application to the database schema you just created.
5.  Run the application!

## 🏛️ Architecture & ERD

The application follows a standard Oracle APEX architecture, with the APEX engine rendering pages based on metadata stored in the database. The business logic is encapsulated within the database schema using PL/SQL.

**Entity-Relationship Diagram (ERD):**

<img src="https://github.com/Thoyyibhans/Online-Shop-Management-System-Oracle-APEX-/blob/main/osm_erd.png?raw=true" width="400"/>

## 📸 Sample Screenshots

**Login Page:**  
<img src="https://github.com/Thoyyibhans/Online-Shop-Management-System-Oracle-APEX-/blob/main/osm_login.png?raw=true" width="300"/>

**Admin Dashboard:**  
<img src="https://github.com/Thoyyibhans/Online-Shop-Management-System-Oracle-APEX-/blob/main/osm_dashboard.png?raw=true" width="700"/>

**Product Page:**  
<img src="https://github.com/Thoyyibhans/Online-Shop-Management-System-Oracle-APEX-/blob/main/osm_products.png?raw=true" width="700"/>


## 🤝 Contribution Guidelines

Contributions are welcome! Please feel free to fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Credits

This project was created and is maintained by Thoyyibhans.
