# Expense Tracker API (Spring Boot + MySQL)

## 📌 Description
A simple RESTful API for managing expenses and categories built with Spring Boot and Maven.

## ✅ Features
- Create, update, delete, and view expenses
- Categorize expenses
- Swagger API Documentation
- Tested with Postman

## 🚀 Getting Started

### Prerequisites
- Java 21+
- Maven 3.9+
- MySQL (running locally)

### Run Locally
```bash
mvn spring-boot:run

Swagger Docs
Open in browser:

bash
Copy
Edit
http://localhost:8080/swagger-ui/index.html

📮 API Endpoints
Method	Endpoint	Description
GET	/api/categories	List all categories
POST	/api/categories	Add a new category
PUT	/api/categories/{id}	Update a category
DELETE	/api/categories/{id}	Delete a category
GET	/api/expenses	List all expenses
POST	/api/expenses	Add a new expense
PUT	/api/expenses/{id}	Update an expense
DELETE	/api/expenses/{id}	Delete an expense

🧪 Postman Collection
Import expense-tracker-collection.json in Postman to test all endpoints.

🗃️ Author
Mohammed Mbarak Hassan
https://mohammed-mbarak-portfolio.onrender.com | LinkedIn

