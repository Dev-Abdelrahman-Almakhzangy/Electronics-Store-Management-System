# Electronics Store Management System

This project is a database-driven application built using **Microsoft Access** for managing the operations of an electronics store. It includes modules for handling customers, deliveries, payments, repairs, invoices, suppliers, employees, inventory, and more.

---

## 🎞️ Features

* Customer registration and order management
* Employee and branch management
* Product and equipment inventory tracking
* Supplier, distributor, and delivery tracking
* Repair requests and return handling
* Invoice generation and payment methods
* Support for multiple relationships via linking tables

---

## 🗓️ Database Tables Overview

Here are the main tables and their purposes:

| Table                             | Description                                     |
| --------------------------------- | ----------------------------------------------- |
| `Customer`                        | Holds customer info including contact and DOB   |
| `Employee`                        | Stores employee details including salary        |
| `Branch`                          | Represents store locations                      |
| `Product`                         | All available products with brand, price, type  |
| `Inventory`                       | Product stock levels by section and location    |
| `Delivery`                        | Details of product shipments to customers       |
| `Invoice`                         | Transactional records linked to products        |
| `Supplier`                        | External providers of products or equipment     |
| `Distributor`                     | Entities reselling products to customers        |
| `Repair`                          | Tracks service and repair requests              |
| `Payment Method`                  | Various ways customers can pay                  |
| `Equipment`                       | Store assets, possibly linked to suppliers      |
| `Supply`, `Distribute`, `Provide` | Relationship (junction) tables between entities |

---

## 🛠️ ER Relationships Summary

* A customer can have many:

  * Deliveries
  * Repairs
  * Invoices
  * Payment methods
* A product can:

  * Be in one invoice
  * Be in one inventory
  * Be supplied by multiple suppliers
  * Be distributed by multiple distributors
* A branch has many employees
* Equipment is linked to suppliers via the `Provide` table

---

## 📁 Project Files

* `Electronics_store_management_system.accdb` – The main Microsoft Access database file (you should include this)
* `Electronics_store_management_system.docx` – Project report with detailed tables, relationships, and attributes

---

## 🧑‍💼 Team Members

| Name                    | BUE ID |
| ----------------------- | ------ |
| Abdelrahman Almakhzangy | 235576 |
| Yara Amr Mohamed        | 233110 |
| Passant Gamil Ayad      | 234791 |
| Habiba Amr Alaa         | 235133 |
| Ahmed Haitham Mohamed   | 233459 |

---

## 📬 Contact

If you have any questions or feedback, feel free to reach out to us through our BUE emails provided in the project report.

---

## ✅ How to Use

> Open the `.accdb` file using Microsoft Access 2016 or later. You can navigate the tables, forms, and relationships via the built-in Access UI.

---

## 📄 License

This project was developed for educational purposes at the British University in Egypt as part of the Introduction to Information Systems course.
