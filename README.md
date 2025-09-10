# Assignment5
### 📌 Project Overview

- This project implements CRUD functionality (specifically Add and Delete) for managing:
- Products (Name, Category, Price, Quantity, Description)
- Buyers (Name, Email, Phone Number, Address)
- The goal is to provide an intuitive interface for record management and ensure data is stored in a MySQL database.

### ⚙️ Requirements

- NetBeans IDE (latest version recommended)
- Java Development Kit (JDK 8 or higher)
- MySQL Server (XAMPP/WAMP or standalone)
- MySQL Connector/J (JDBC driver)

### 🚀 Features
## ➕ Adding Products/Buyers

- Input form for entering product or buyer details.
- Validation for required fields (e.g., numeric values for price/quantity, valid email format).
- Data stored in respective MySQL tables (products, buyers).
- Confirmation message displayed after successful entry.

## ❌ Deleting Products/Buyers

- Records displayed in a table/list format.
- Option to delete single or multiple records.
- Confirmation dialog before deletion to prevent accidental data loss.
- User notified of successful deletion or errors.

### 🛠️ Implementation Steps

## Design Forms:

- Product Form → Name, Category, Price, Quantity, Description.
- Buyer Form → Name, Email, Phone Number, Address.
- Validation: Check inputs before saving to database.
- Insert Queries: Store new records in the database.
- Display Records: Show products/buyers in a JTable or list.
- Delete Functionality: Add "Delete" button with confirmation dialog.
- Feedback & Refresh: Notify user and reload the list after deletion.
- Improve error handling & logging.
