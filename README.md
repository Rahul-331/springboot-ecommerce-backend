# 🛒 Spring Boot E-Commerce Backend

A RESTful backend application for an E-Commerce platform built using **Spring Boot**. This project provides APIs for managing products, including CRUD operations, and demonstrates the use of Spring Boot, Spring Data JPA, Hibernate, and H2 Database.

## 🚀 Features

- RESTful API architecture
- Product CRUD operations
- Spring Boot 3.x
- Spring Data JPA & Hibernate
- H2 Database integration
- Lombok for boilerplate reduction
- Maven build management
- Layered architecture (Controller → Service → Repository)
- Exception handling and validation ready

---

## 🛠️ Tech Stack

| Technology | Version |
|------------|----------|
| Java | 21+ |
| Spring Boot | 3.5.x |
| Spring Data JPA | Latest |
| Hibernate | ORM |
| H2 Database | In-Memory |
| Maven | Build Tool |
| Lombok | Latest |

---

## 📁 Project Structure

```
src
├── main
│   ├── java
│   │   └── com.camper.ecom_project
│   │       ├── controller
│   │       ├── service
│   │       ├── repository
│   │       ├── model
│   │       └── EcomProjectApplication.java
│   └── resources
│       └── application.properties
└── test
```

---

## 📌 REST API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/products` | Retrieve all products |
| GET | `/products/{id}` | Retrieve a product by ID |
| POST | `/products` | Add a new product |
| PUT | `/products/{id}` | Update an existing product |
| DELETE | `/products/{id}` | Delete a product |

---

## ⚙️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/Rahul-331/springboot-ecommerce-backend.git
cd springboot-ecommerce-backend
```

### Run the Application

```bash
./mvnw spring-boot:run
```

or on Windows

```bash
mvnw.cmd spring-boot:run
```

The backend will start on:

```
http://localhost:8080
```

---

## 🗄️ Database

This project currently uses the **H2 In-Memory Database** for development.

H2 Console:

```
http://localhost:8080/h2-console
```

Example Configuration:

```
JDBC URL : jdbc:h2:mem:test
Username : sa
Password :
```

---

## 🧪 Sample Product JSON

```json
{
  "name": "Royal Enfield Classic 350",
  "desc": "Retro styled cruiser motorcycle",
  "brand": "Royal Enfield",
  "price": 193500,
  "category": "Bike",
  "releaseDate": "2024-01-15",
  "available": true,
  "quantity": 15
}
```

---

## 🔮 Future Enhancements

- PostgreSQL/MySQL Support
- User Authentication & Authorization
- Spring Security + JWT
- Shopping Cart
- Orders & Payments
- Product Search & Filtering
- Pagination & Sorting
- Docker Deployment
- Cloud Deployment (Render/AWS)

---

## 👨‍💻 Author

**Rahul Dandu**

- GitHub: https://github.com/Rahul-331
- LinkedIn: https://www.linkedin.com/in/dandu-rahul-a11691345/

---

## ⭐ If you found this project useful, consider giving it a star!
