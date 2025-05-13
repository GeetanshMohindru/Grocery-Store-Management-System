# 🛒 Grocery Store Management System

## 📌 Overview

The **Grocery Store Management System** is a full-stack web application designed to streamline the daily operations of a grocery store. It enables store owners and employees to manage inventory, sales, user roles, and reporting efficiently — all from a centralized dashboard.

Built with **Node.js**, **Express.js**, and **MySQL**, the system provides a reliable and responsive interface, ensuring a smooth user experience on desktops, tablets, and smartphones.

---

## 🚀 Features

- 🔐 **User Management**
  - Role-based access (Admin, Cashier)
  - CRUD operations on user accounts

- 📦 **Inventory Management**
  - Add, update, delete products
  - Real-time stock tracking

- 💰 **Sales Processing**
  - Handle purchases and transactions
  - Auto-generate receipts
  - Manage multiple payment methods

- 📊 **Reporting Dashboard**
  - View sales statistics
  - Monitor low-stock items
  - Track user activities

- 📱 **Responsive UI**
  - Mobile-friendly design
  - Clean and intuitive interface

---

## 🧰 Tech Stack

| Category        | Technology          |
|----------------|---------------------|
| Frontend       | HTML, CSS, JavaScript |
| Backend        | Node.js, Express.js |
| Database       | MySQL               |
| DB Management  | PHPMyAdmin          |
| Package Manager| npm                 |
| Version Control| Git & GitHub        |

---

## ⚙️ Installation Guide

Follow these steps to set up the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/GeetanshMohindru/Grocery-Store-Management-System.git
   cd Grocery-Store-Management-System
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up the MySQL database**
   - Open **PHPMyAdmin**.
   - Create a new database (e.g., `grocery_db`).
   - Import the SQL file located in the `dbms project` directory.

4. **Configure environment variables**
   - Create a `.env` file in the root directory:
     ```
     DB_HOST=localhost
     DB_USER=your_mysql_username
     DB_PASSWORD=your_mysql_password
     DB_NAME=grocery_db
     ```

5. **Start the application**
   ```bash
   npm start
   ```

6. **Access the web app**
   - Open your browser and navigate to:  
     `http://localhost:3000`

---

## 🧪 Usage

- 🔑 **Login**: Use the provided credentials or create a new user.
- 📁 **Inventory**: Add, update, and delete grocery products.
- 🧾 **Sales**: Record transactions and view receipts.
- 📉 **Reports**: Monitor key business metrics.

---

## 📂 Folder Structure

```
Grocery-Store-Management-System/
│
├── public/                # Frontend assets (CSS, JS)
├── routes/                # Route handlers
├── views/                 # HTML views (EJS or similar templating)
├── dbms project/          # SQL dump and sample data
├── .env                   # Environment config
├── app.js                 # Main server file
└── README.md              # Project documentation
```

---

## 👨‍💻 Author

**Geetansh Mohindru**  
📫 [Email](mailto:geetanshmohindru@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/geetansh-mohindru/) 

---


## 💡 Future Enhancements

- 📦 Barcode scanner integration
- 🛍️ Customer loyalty points system
- 📱 PWA support for offline access
- 🔔 Low-stock alert notifications

---

If you like this project, feel free to ⭐ the repository!
