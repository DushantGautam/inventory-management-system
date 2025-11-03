# Inventory Management System (PHP & MySQL) 

[![Built with PHP](https://img.shields.io/badge/Built%20with-PHP-777BB4?logo=php&logoColor=white)](https://www.php.net/)
[![Database](https://img.shields.io/badge/Database-MySQL-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Frontend](https://img.shields.io/badge/Frontend-HTML%2C%20CSS%2C%20JS-orange)](https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer)
[![Backend](https://img.shields.io/badge/Backend-PHP-blue)](https://www.php.net/)
[![Deployed with XAMPP](https://img.shields.io/badge/Deployed%20with-XAMPP-brightgreen)](https://www.apachefriends.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)



A web-based **Inventory Management System** built using **PHP, MySQL, HTML, CSS, and JavaScript**.  
This system enables efficient management of products, stock, categories, and sales with role-based access for Admin, Special User, and Employee.

---

## 🧩 Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP (v5.6.3 recommended)  
- **Database:** MySQL  
- **Server Environment:** XAMPP  

---

## 🎯 Project Objective
To provide a simple and efficient platform for small and medium businesses to **manage inventory, track sales, and control user access** through a secure web interface.

---

## ⚙️ Features

### 🔐 Authentication & Roles
- **Admin:** Full control of the system (manage users, groups, products, sales, and reports).  
- **Special User:** Can manage products, categories, and sales but **cannot manage users or groups**.  
- **User (Employee):** Can view inventory and record sales only.  

### 📦 Inventory Management
- Add, edit, and delete **products**, **categories**, and **groups**.  
- Upload and manage product images.  
- View available stock and recent additions.

### 💰 Sales Management
- Record daily and monthly sales.  
- Generate detailed **sales reports**.  
- Automatic stock quantity updates after each sale.

### 👥 User Management (Admin Only)
- Add and manage system users.  
- Assign roles (Admin, Special, or User).  
- Secure login and password management.

### 📊 Reports & Dashboard
- Overview of total products, categories, and daily/monthly sales.  
- Sales report generation by date range.  
- Easy-to-use and responsive admin dashboard.

---

## 🧠 Role-Based Access Summary

| Role          | Access Permissions                                                                 |
|----------------|------------------------------------------------------------------------------------|
| **Admin**      | Full system access including user & group management, inventory, and sales reports |
| **Special User** | Manage products, categories, sales, and reports (no user/group management)        |
| **User**       | View stock and record sales only                                                   |

---

## 🗂️ Project Structure

```

inventory-system-php/
│
├── database/                     # Contains inventory_system.sql
├── includes/                     # PHP includes and core logic
├── layouts/                      # Common HTML layouts and templates
├── libs/                         # Libraries and helper scripts
├── uploads/                      # Product image uploads
│
├── add_product.php               # Add new product
├── add_sale.php                  # Add sales entries
├── daily_sales.php               # Daily sales record
├── monthly_sales.php             # Monthly sales record
├── manage_user.php               # User management (Admin)
├── edit_product.php              # Edit product details
├── index.php                     # Login page
├── home.php                      # Dashboard
├── profile.php                   # User profile
├── sales_report.php              # Sales report generator
├── 01_login_details_and_project_info.txt
├── license.txt
└── README.md

```

---

## 🧰 Installation & Setup

1. **Install XAMPP** on your local machine.  
2. Move the project folder to:
```

C:\xampp\htdocs\inventory-system-php

```
3. Start **Apache** and **MySQL** from the XAMPP control panel.  
4. Import the database:
- Open [phpMyAdmin](http://localhost/phpmyadmin)
- Create a new database named `inventory_system`
- Import `inventory_db.sql` from the `database/` folder
5. Open your browser and run:
```

[http://localhost/inventory-system-php](http://localhost/inventory-system-php)

```

---

## 🔑 Login Credentials

| Role          | Username | Password |
|----------------|-----------|-----------|
| **Admin**      | admin     | admin     |
| **Special User** | special   | special   |
| **User (Employee)** | user     | user      |

---

## 🗄️ Database Overview

**Database Name:** `inventory_system`

**Main Tables:**
- `categories` – Stores all product categories  
- `products` – Product details, stock, and pricing  
- `sales` – Records daily and monthly sales  
- `users` – Stores user login and profile information  
- `user_groups` – Defines roles and permission levels  
- `media` – Product images and files

---

## 🎥 Live Demo
Watch the full demo video on YouTube:  
[👉 Click Here to Watch the Project Demo](https://www.youtube.com/your-video-link)


---


## 📜 License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE.txt)  
This project is licensed under the MIT License — see the [LICENSE file](./LICENSE.txt) for details.

Copyright (c) 2015 **Siamon Hasan**




---

## 👤 Developer
**Developed & Modified by:** Dushant Gautam  
📍 Mathura, Uttar Pradesh, India  
📧 [dushantgautam05@gmail.com](mailto:dushantgautam05@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/dus123)

---

