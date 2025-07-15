## 📦 Import & Export System

### 📄 Overview

The **Import & Export System** is a Java-based desktop application that simplifies the management of international trade operations. It includes features like user role management, product tracking, transaction logging, logistics, and warehouse coordination.

---

### 📂 Features

#### 👥 User Management

* Role-based users: Administrator, Exporter, Importer, Customer
* Secure login & user verification
* Admin privileges to manage permissions and generate reports

#### 🚚 Import/Export Operations

* Importers and Exporters can register, update profiles, and manage products
* License management for importing/exporting
* View shipping info and account balances

#### 📦 Product Management

* Create, update, and remove products
* Manage product attributes: size, color, stock, availability
* Link products with suppliers and warehouses

#### 🏢 Warehouse Management

* Store product stock by location
* Add/remove items from stock
* Provide location info for logistics

#### 💰 Financial Management

* Record and process transactions
* Finance team handles invoice management

#### 🌐 Sales & Orders

* Customers can place orders and track shipment status
* System records sales with full price calculation

#### 🚗 Logistics

* Manage transport fleet and vehicles
* Track shipment status

---

### 📅 Classes Breakdown

#### ✉️ Core System

* `ImportExportSystem`: Main controller managing users, products, companies, invoices, and sales

#### 👤 User Types

* `User`: Base class for all users
* `Administrator`: Permission and license approval
* `Exporter`: Handles exporting and licenses
* `Importer`: Handles importing and licenses

#### 📈 Commerce & Inventory

* `Product`: Manages all product details
* `Warehouse`: Stores inventory stock by location
* `Suppliers`: Manages supplier contact and supplied products

#### 👜 Customer & Transactions

* `Customer`: Places and tracks orders
* `Transaction`: Records transaction logs and parties involved
* `Sale`: Manages sales and total price calculations

#### 📆 Teams

* `FinanceTeam`: Processes invoices
* `ITeam`: Maintains and updates the database

#### 🚚 Logistics

* `Logistics`: Handles shipment status
* `Vehicle`: Represents transport vehicles used

---

### 🌐 Relationships

* One-to-many and many-to-many associations between:

  * Users and roles
  * Products and suppliers/warehouses
  * Exporters/Importers and products
  * Customers and orders
  * Sales and products
  * Vehicles and shipments

---

### 📚 Technologies Used

* **Java (OOP)** - Application logic
* **UML** - System design via Class and Object Diagrams
* **MySQL (Assumed)** - Persistent storage (suggested)

---

### ⚖️ How to Use

1. Clone the repository
2. Launch application and login with a user role
3. Add products, suppliers, and warehouse stock
4. Process sales, place orders, or manage licenses based on user type
5. Track shipments and generate reports

---

### 📁 Project Files

* `Class Diagram.png` - UML class relationships
* `Object Diagram.png` - Sample runtime structure (load pending)
* `README.md` - Documentation

---

### ✨ Future Improvements

* GUI Interface for better UX
* API integration with ERP systems
* Dashboard for analytics & reporting

---

### 💼 License

MIT License. See `LICENSE` file for more info.

---

