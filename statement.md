# Shop Inventory Management System(SIMS)

## Problem Statement

Small retail shops often manage their inventory using handwritten registers which makes it hard to know the exact stock level of each product at any given time. This manual process is time‑consuming, error‑prone, and does not scale well as the number of products and daily transactions increases. The lack of a centralized, user‑friendly system leads to issues like stockouts, overstocking, incorrect billing, and difficulty in generating basic reports (such as daily sales or current stock status). The Shop Inventory Management System aims to replace these manual methods with a simple desktop application that automates inventory tracking and basic sales operations.

## Scope of the Project

The project focuses on building a standalone desktop application for managing a single shop’s inventory and simple sales/billing tasks. It will allow the user to maintain a product catalog, record stock levels, and update quantities after purchases and sales. The system will provide a graphical user interface (GUI) for daily operations such as adding a new product, editing an existing product, recording a sale, and viewing current stock. Data will be stored locally (for example, in a file or a lightweight database), and the initial scope will not cover multi‑branch operations, advanced analytics, or online access. However, the design will be kept modular so that features like reporting, alerts, or user roles can be added later if required.

## Target Users

- Small shop owners who need a simple way to keep track of their products and stock levels.
- Store managers or staff responsible for updating inventory and handling billing at the counter.
- Students or beginners learning software development who want a practical example of a CRUD‑based desktop application with a GUI.
- Micro and small businesses that do not have the budget or need for complex enterprise resource planning (ERP) systems but still want to reduce errors and save time.

## High-Level Features

- Product Management  
  - Add new products with details such as name, category, price, and initial quantity.  
  - Edit or delete existing products when information changes or items are discontinued.

- Inventory Tracking  
  - View a list of all products with current stock levels.  
  - Automatically update stock when items are sold or restocked.  
  - Search and filter products by name, category, or ID.

- Sales and Billing (Optional but Recommended)  
  - Create simple bills by selecting products and quantities.  
  - Calculate totals and optionally include basic discounts or taxes.  
  - Update inventory quantities after each confirmed sale.

- Data Storage and Basic Validation  
  - Store product and transaction data in a local storage mechanism (e.g., CSV, JSON, or SQLite).  
  - Perform basic input validation (e.g., prevent negative quantities, ensure required fields are filled).

- Usability and User Interface  
  - Provide a Tkinter‑based GUI with clear buttons and forms for common tasks.  
  - Display messages or dialogs for success, errors, and confirmations (e.g., before deleting a product).

- Extensibility (Future Enhancements)  
  - Support for low‑stock alerts and simple inventory reports (e.g., daily sales, top‑selling items).  
  - User authentication (e.g., admin and staff roles).  
  - Export data to CSV/Excel for backup or external analysis.

