# online-food-delivery-system-java

## Overview
The **Online Food Delivery System** is a Java console-based application that allows customers to browse restaurants, add food items to their cart, place orders, and track their delivery status. Admins can manage restaurants, food items, and delivery personnel, while customers can register, view menus, and order food.  
This project showcases Object-Oriented Programming (OOP) principles — **inheritance, polymorphism, and collections** — in action.

---
## Tech Stack Used

<p align="left">
  <img src="https://img.shields.io/badge/Java_(Core_Java)-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java (Core Java)" />
  <img src="https://img.shields.io/badge/Object_Oriented_Programming-008C76?style=for-the-badge&logo=databricks&logoColor=white" alt="Object-Oriented Programming" />
  <img src="https://img.shields.io/badge/Data_Structures_List_&_Map-4479A1?style=for-the-badge&logo=gnu&logoColor=white" alt="Data Structures" />
  <img src="https://img.shields.io/badge/Eclipse_IDE-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white" alt="Eclipse IDE" />
</p>

---

## Features
### Admin Module
- Add and manage **restaurants**
- Add or remove **food items** from restaurant menus
- Add **delivery persons**
- Assign delivery persons to orders
- View all **restaurants, menus, and orders**

### Customer Module
- Register as a new customer
- Browse available restaurants and menus
- Add food items to cart
- View and update cart items
- Place and track orders

---

## Classes & Relationships
| Class | Description |
|-------|--------------|
| 🍔 **FoodItem** | Represents individual food items with ID, name, and price. |
| 👤 **User (Base Class)** | Parent class for `Customer` and `Admin`, holds user details. |
| 🛒 **Customer** | Inherits from `User`, includes a `Cart` for ordering. |
| 🧺 **Cart** | Manages selected food items and quantities. |
| 🍽️ **Restaurant** | Contains menu items and manages food availability. |
| 🚴 **DeliveryPerson** | Handles delivery assignments for orders. |
| 📦 **Order** | Tracks order details, items, customer info, and delivery status. |


---

## Concepts Used
- **Encapsulation**: All class fields are private and accessed through getters/setters.
- **Inheritance**: `Customer` extends `User`.
- **Polymorphism**: Overridden `toString()` methods.
- **Collections Framework**: Utilizes `Map`, `List`, and `Set` for data management.

---

## How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/OnlineFoodDeliverySystem-Java.git
2. Open the project in your preferred Java IDE.

3. Compile and run the main file (menu driver program).

4. Choose between Admin or Customer modules from the menu.

---

*Created and maintained by **Padmapriya** as part of the **TNSIF training program**.*
