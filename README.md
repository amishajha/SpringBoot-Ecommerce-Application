🛒A full-fledged E-commerce REST API built using Spring Boot 3, Spring Data JPA, and Spring Security 6 with JWT Authentication.
This application provides secure user registration, product management, cart handling, order processing, and payment simulation features.
It follows clean architecture principles and is designed for scalability, security, and cloud deployment on AWS.


Features
👤 User Management

Register, login, and manage profiles securely

JWT-based authentication and authorization

Role-based access control (USER, ADMIN)

🛍️ Product Management

Add, update, delete, and view products (Admin)

Search and filter products by name, category, or price

Upload product images (local / AWS S3 support)

🛒 Cart & Orders

Add or remove products from cart

Place orders from cart

View order history and details

Order status tracking (PENDING, SHIPPED, DELIVERED)

💳 Payment Simulation

Mock payment gateway integration

Auto-generates payment receipts

🔐 Security

JWT token-based authentication

Stateless session management

Password hashing with BCrypt

Role-based method and endpoint protection

📊 Admin Capabilities

Manage users and products

View all orders
