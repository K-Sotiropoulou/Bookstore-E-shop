# 📚 Peri Gnoseos - Online Bookstore

A comprehensive B2C e-commerce platform developed with **PHP** and **MySQL**, focusing on secure transactions, robust business logic, and automated tax calculations.
---

## Project Demo
*A complete walkthrough: From product selection to the final checkout success page with automated VAT calculations.*
---

## Key Features

### Cart & Checkout System
* **Dynamic Cart Management:** Add, remove, and update item quantities in real-time.
* **Multi-Format Support:** Distinct pricing logic for Physical books, E-books (-40%), and Audiobooks (+25%).
* **Automated VAT Calculation:** Precise calculation of Net Value and VAT (standard 6% rate) throughout the ordering process.

### Security & Reliability
* **Database Transactions:** Implementation of PDO Transactions to ensure data integrity during order placement and stock deduction.
* **Security Layers:** * Full protection against **CSRF** (Cross-Site Request Forgery) using secure tokens.
    * Prevention of **SQL Injection** via Prepared Statements.
    * **PCI Compliance:** Sensitive card data is never stored; only the last 4 digits are kept for user reference.

### Inventory Management
* Intelligent stock deduction logic that only affects physical products, while digital formats (ebook/audio) remain perpetually available.

---

## Business Logic
The application supports the issuance of both **Retail Receipts** and **Commercial Invoices**, dynamically collecting necessary tax information (VAT ID, Tax Office, Business Activity) based on user selection.

---

## Tech Stack
* **Backend:** PHP 8.x
* **Database:** MySQL (MariaDB)
* **Frontend:** HTML5, CSS3, Bootstrap 5, FontAwesome
* **Security:** CSRF Protection, Password Hashing, PDO Security

---

## 🔒 Source Code
The source code for this project is **private** for security and intellectual property reasons. 
However, I am happy to perform a live technical walkthrough or discuss the architecture (PHP/PDO/SQL) during an interview.

---
