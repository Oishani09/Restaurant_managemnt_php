# 🍽️ Restaurant Order Management System

## 🚀 Overview
The **Restaurant Order Management System** is a full-stack web application designed to streamline the ordering and management process for restaurants. Developed using **PHP** and **MySQL**, this system efficiently handles customer orders, order tracking, and backend management, ensuring smooth restaurant operations.

This project follows **MVC (Model-View-Controller)** architecture, making it modular and scalable. The database design follows **normalization principles** to optimize queries, ensuring quick response times. With a **RESTful API-driven** backend, the system can easily be extended to mobile applications in the future.

## ✨ Features
- 🔐 **User Authentication**: Secure login & registration system
- 📜 **Menu Display**: Categorized menu with item details
- 🛒 **Cart & Checkout**: Intuitive cart system for easy ordering
- 📦 **Order Management**: Real-time order status updates (Pending, Processing, Completed)
- 🎛 **Admin Dashboard**: Menu & order management with analytics
- 💳 **Payment Integration** (if implemented)

## 🛠️ Technologies Used
- **Backend**: PHP (OOP, MVC Pattern)
- **Database**: MySQL (Optimized Queries, Indexing)
- **Server**: Apache (XAMPP Stack)
- **Frontend**: HTML5, CSS3, JavaScript (Bootstrap, jQuery, AJAX)
- **Security**: Password Hashing, CSRF Protection, SQL Injection Prevention

## ⚙️ Installation
### Prerequisites
Ensure you have the following installed on your system:
- ✅ [XAMPP](https://www.apachefriends.org/) (Apache & MySQL)
- ✅ A Modern Web Browser (Chrome, Firefox, Edge, etc.)

### Steps to Set Up
1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/yourusername/restaurant-order-management.git
   ```
   OR manually download and extract the zip file.

2. **Move the Project Folder**
   Copy the project folder to the `htdocs` directory of your XAMPP installation.
   ```bash
   C:\xampp\htdocs\restaurant-order-management
   ```

3. **Configure the Database**
   - Open XAMPP and start **Apache** & **MySQL**.
   - Open **phpMyAdmin** (http://localhost/phpmyadmin/).
   - Create a new database, e.g., `restaurant_db`.
   - Import the SQL file (`database.sql`) from the project folder.

4. **Update Database Connection**
   Edit the `config.php` file and update the database credentials if needed.
   ```php
   $host = 'localhost';
   $db   = 'restaurant_db';
   $user = 'root';
   $pass = '';
   ```

5. **Run the Application**
   Open your browser and visit:
   ```
   http://localhost/restaurant-order-management/
   ```

## 📌 Usage Guide
### 🎯 Customer
- Register/Login to access the platform.
- Browse the menu and add items to the cart.
- Place an order and track its status in real-time.

### 🎩 Admin
- Access the **admin dashboard**.
- Manage orders, update menu items, and monitor restaurant analytics.

## 📸 Screenshots
*(Insert UI screenshots to make it visually appealing.)*

## 🔥 Future Enhancements
- **📱 Mobile App Version** (React Native / Flutter)
- **💰 Online Payment Gateway Integration** (PayPal, Stripe, Razorpay)
- **⭐ User Review & Rating System**
- **🍽️ Table Reservation System**
- **📊 Advanced Data Analytics & Sales Reports**

## 📩 Contact
For any queries or contributions, reach out to:
- **📧 Email**: oishnaibanerjee09@gmail.com
