Stock Wizard is a simple, user-friendly desktop application designed to streamline inventory and order management for small to medium-scale businesses. Built with C# WinForms on the .NET Framework, and backed by SQL Server, it provides essential tools to manage categories, products, customers, users, and orders efficiently.

🚀 Features

🔐 Secure Login: Username and password authentication with a “Forgot Password” option.
🗃️ Category Management: Manage product categories with unique IDs and names.
👥 Customer Management: Store customer details including names and phone numbers.
📦 Product Inventory: Track quantity, pricing, and category-wise organization of products.
🧾 Order Processing: Record orders with real-time calculation of total price and product usage.
👤 User Roles: Manage application users with full name and contact info.
🧰 Tech Stack

Language: C#
Framework: .NET (WinForms)
Database: Microsoft SQL Server
Architecture: Windows Forms Application with ADO.NET for data access

🗂️ Database Schema

Table	Columns

Category	category_id, category_name
Customer	id, name, phone_number
Product	id, name, qty, price, description, category
Order	order_id, product_id, customer_id, order_date, quantity, price, total
User	username, password, fullname, phone_no
