# 🛒 Full Stack E-Commerce Application

A production-ready **Full Stack E-Commerce Application** built using **Spring Boot (Backend)** and **React (Frontend)**. The project is actively under development and follows real-world, scalable architecture used in modern e-commerce platforms. This project is designed with clean architecture, RESTful APIs, and scalability in mind.

---

## 🚀 Features Implemented

> ⚠️ **Note:** This is an evolving full-stack project. More features like **Orders, Payments, and React Frontend UI** are being actively added.

> 🔐 This application uses **Cookie-Based JWT Authentication** instead of localStorage/header-based tokens.

### 🔐 Authentication & Authorization

* Cookie-based JWT authentication (HTTP Only Cookies)
* Secure login & signup APIs
* JWT token stored in cookies
* Role-based access control (**USER / SELLER / ADMIN**)
* Password encryption using BCrypt

### 🏷️ Product Management

* Create, update, delete products
* Fetch all products
* Fetch product by ID
* Category-based product mapping

### 📂 Category Management

* Create and manage product categories
* Fetch all categories
* Category-wise product listing

### 🛍️ Cart Management

* Add product to cart
* Update product quantity in cart
* Remove product from cart
* Fetch user-specific cart

### 📍 Address Management

* Add new address
* Fetch all addresses for logged-in user
* Update address
* Delete address

---

## 🛠️ Tech Stack

### Backend

* Java 21
* Spring Boot
* Spring Security (JWT)
* Spring Data JPA
* Hibernate
* ModelMapper

### Database

* PostgreSQL (Primary Database)
* MySQL (Previously used / supported)

### Tools & Others

* Maven
* Git & GitHub
* Postman (API Testing)

---

## 📂 Project Structure

```
com.example.ecommerce
│
├── controller      # REST Controllers
├── service         # Business Logic
├── repository      # JPA Repositories
├── entity          # Database Entities
├── dto             # Data Transfer Objects
├── security        # JWT & Security Config
├── exception       # Global Exception Handling
└── config          # Application Configurations
```

---

## 🔑 API Authentication Flow

1. User registers using signup API
2. User logs in using credentials
3. JWT token is generated and stored in **HTTP-only cookie**
4. Cookie is automatically sent with each secured request


## 🧪 API Testing

* Use **Postman** or **Swagger**
* Ensure JWT token is passed for secured endpoints

---

## 🧑‍💼 Roles & Permissions

### USER

* Browse products
* Manage cart
* Manage addresses
* Place orders (upcoming)

### SELLER

* Add & manage own products
* Update product details
* View seller-specific products

### ADMIN (Planned)

* Manage users
* Manage categories
* Platform-level control

---

## 🛣️ Upcoming / In-Progress Features

* User Order Management
* Payment Gateway Integration (Razorpay / Stripe)
* React Frontend (User & Seller Dashboards)
* Checkout & Order History
* Admin Management Panel

---

## 🛣️ Long-Term Enhancements

* Order Management
* Payment Gateway Integration
* Wishlist
* Product Reviews & Ratings
* Admin Dashboard

---

## 👨‍💻 Developer

**Mohd Kaif**
Java Backend / Full Stack Developer

* Java | Spring Boot | React | MySQL | MongoDB
* JWT | REST APIs | Docker | Git

---

⭐ If you like this project, give it a star on GitHub!
