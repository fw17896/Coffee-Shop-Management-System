# Coffee-Shop-Management-System
A Java-based Coffee Shop Management System featuring a Graphical User Interface (GUI), robust file handling, and modular object-oriented design. This project efficiently manages customers, staff, inventory, products, and delivery operations—making it a full-featured desktop retail management solution.

### Key Features
- Staff Management
    - Add, view, update, and delete staff with authentication (ID/password). Data is persisted using serialization.

- Inventory Management
    - Add new products, modify quantities, prevent duplication, and view inventory. Supports size and quantity validation.

- Product Management
    - Products are defined by name, size, price, and quantity. Easily extendable and serialized for persistent storage.

- Customer Interface
    - Customers can view products, add items to cart, provide delivery details, and checkout with validation.

- Delivery Management
    - Collects recipient name, address, city, and phone number with validation and formatted display.

- File Handling
    - All data (customers, staff, products, inventory) is saved and loaded via serialization, ensuring persistence across sessions.

- Robust Exception Handling
    - Handles all common runtime issues like invalid inputs, missing files, and null pointers.

- Java Swing GUI
    Clean and interactive graphical interface for staff and customer operations using Java Swing.
