# 🚗 Car Rental System – Java Console Application

This is a simple **Car Rental Management System** built using Java. It allows users to rent cars, and admins to manage the car inventory. The application runs entirely in the console and is designed to simulate basic functionalities of a real-world car rental service.

---

## 📋 Features

### 👤 Admin Functionalities

* **Admin Login** (User ID: `admin@123`, Password: `1234`)
* View list of available cars
* Add a new car to the inventory
* Delete a car record
* Search for cars by:

  * Make
  * Model
  * Year
  * Colour
* View rented cars
* Modify the rental price of a car

### 🙋‍♂️ Customer Functionalities

* Filter available cars by:

  * Make
  * Model
  * Year
  * Colour
* Rent a car:

  * Enter personal details
  * Select rental duration
  * Discount on rentals over 8 days
  * GST is applied at 18%
* Payment options:

  * Credit/Debit Card
  * UPI

---

## 🔧 How It Works

* The system uses **object-oriented programming** principles.
* The `Car` class encapsulates the details and actions related to each car.
* The main class `CarRentalSystem` handles admin/customer interaction and menu navigation.
* Rental details are handled dynamically and the car’s availability is updated upon successful rental.

---

## ✅ Requirements

* Java JDK 8 or above
* Any IDE (e.g., IntelliJ, Eclipse) or compile via terminal

---

---

## 📦 Future Enhancements

* Persistent storage using file handling or databases
* GUI integration (Swing/JavaFX)
* Enhanced user authentication
* Email/SMS confirmation for rentals

---
