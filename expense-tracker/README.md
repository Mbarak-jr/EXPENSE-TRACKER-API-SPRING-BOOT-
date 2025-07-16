# 💰 Expense Tracker API - Spring Boot

This is a RESTful Expense Tracker API built with **Spring Boot**, designed to allow users to manage expense categories and expenses efficiently.

> ✅ Project submitted as part of the **Equity Group Foundation Backend Developer Intern - First-Level Assessment**  
> 🗓️ Deadline: **Monday, 21st July 2025 by 5:00 PM**

---

## 📌 Features

- Create, view, update, and delete **Expense Categories**
- Create, view, update, and delete **Expenses**
- Each expense is associated with a specific category
- Input validation using `jakarta.validation`
- API tested with Postman
- Maven build with `.gitignore`, clean structure, and layered architecture

---

## 🛠️ Tech Stack

- **Java 21**
- **Spring Boot 3**
- **Maven**
- **H2 Database (in-memory)**
- **JPA/Hibernate**
- **Postman (for API testing)**

---

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Mbarak-jr/EXPENSE-TRACKER-API-SPRING-BOOT-.git
cd EXPENSE-TRACKER-API-SPRING-BOOT-
2. Open in IntelliJ IDEA
File → Open → Select the expense-tracker folder

Ensure Maven dependencies are loaded

3. Run the Application
bash
Copy
Edit
./mvnw spring-boot:run
OR inside IntelliJ:

Right-click on ExpenseTrackerApplication.java → Run

📫 API Endpoints
Base URL: http://localhost:8080/api

🔸 Categories
Method	Endpoint	Description
GET	/categories	Get all categories
POST	/categories	Add new category
PUT	/categories/{id}	Update category by ID
DELETE	/categories/{id}	Delete category by ID

Sample POST Body:
json
Copy
Edit
{
  "name": "Food"
}
🔹 Expenses
Method	Endpoint	Description
GET	/expenses	Get all expenses
POST	/expenses	Add new expense
PUT	/expenses/{id}	Update expense by ID
DELETE	/expenses/{id}	Delete expense by ID

Sample POST Body:
json
Copy
Edit
{
  "description": "Lunch at Java",
  "amount": 450,
  "date": "2025-07-16",
  "categoryId": 1
}
🔍 API Testing
Import the attached Postman collection:

File: expense-tracker-api.postman_collection.json

All routes have been tested and verified using Postman.

📂 Project Structure
matlab
Copy
Edit
expense-tracker/
├── controller/
├── dto/
├── model/
├── repository/
├── resources/
│   └── application.properties
├── ExpenseTrackerApplication.java
🙋 Author
Mohammed Mbarak Hassan
Backend Developer | https://mohammed-mbarak-portfolio.onrender.com
📧 mohammedmbarak77@gmail.com
🔗 LinkedIn

📄 License
This project is submitted for academic/internship review and is not licensed for redistribution without permission from the author.