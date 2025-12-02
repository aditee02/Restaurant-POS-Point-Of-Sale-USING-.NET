

# 🍽️ Restaurant POS (Point of Sale) System using .NET

A robust and user-friendly **Restaurant POS System** built using **.NET**, designed to streamline billing operations inside restaurants.
The application provides fast order handling, automatic bill generation, and database-backed record management.

---

## ⭐ Features

### 🧾 **Billing & Order Management**

* Create new orders quickly
* Add multiple items to a bill
* Auto-calculate totals, taxes, and final amount
* Generate printable bills

### 🍛 **Menu Management**

* Add / update / delete food items
* Manage categories and prices
* Real-time menu updates in billing screen

### 👤 **User Access**

* Login system for staff (Admin/Employee)
* Secure authentication workflow
* Track which employee generated each bill

---

## 🧰 Tech Stack

| Component          | Technology                                                      |
| ------------------ | --------------------------------------------------------------- |
| **Frontend**       | .NET / MVC / Razor Pages / WinForms / WPF (as per your project) |
| **Backend**        | .NET 6 / .NET Core                                              |
| **Database**       | Microsoft SQL Server (SSMS)                                     |
| **Authentication** | Built-in Authentication / Token-based (optional)                |

---

## 🏗️ System Overview

* **Order Screen** – Add items, quantity, calculate total
* **Billing System** – Generate and store bills
* **Menu Panel** – Manage food items and inventory


## 📦 Features in Detail

### **Billing Module**

* Add multiple items to an order
* Auto-calculate subtotal, GST/tax, service fees
* Generate final invoice
* Print or download bill

### **Menu Module**

* Add/edit/delete menu items
* Manage pricing and categories
* Display live menu in POS screen


---

## ▶️ Getting Started

### **1. Clone the Repository**

```bash
git clone https://github.com/aditee02/restaurant-pos-system.git
```

### **2. Setup SQL Server**

* Create a new database in **SSMS**

### **3. Configure Connection String**

Update in `appsettings.json`:

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=RestaurantPOS;Trusted_Connection=True;"
}
```

### **4. Run the Project**

```bash
dotnet run
```

---

## 📄 Future Enhancements

* GST/tax configuration from admin panel
* Inventory/stock management
* Integration with barcode/QR scanners
* Kitchen display system (KDS)
* Mobile/tablet-friendly UI

---

## 🤝 Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request.

---
