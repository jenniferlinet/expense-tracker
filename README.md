Expense Tracker – Full Stack Application

Java (Spring Boot) + React + MongoDB

A simple full-stack Expense Tracker that allows users to add, edit, delete, and view expenses with a clean UI and REST API backend.

🚀 Features

Add, edit, delete expenses

View expenses in a table

Total expense calculation

MongoDB database storage

React frontend + Spring Boot backend

REST API with Axios

Fully deployable

🧱 Project Structure
expense-tracker/
│
├── backend/                
│   ├── src/main/java/
│   ├── src/main/resources/
│   ├── pom.xml
│
└── frontend/               
    ├── src/
    ├── public/
    ├── package.json

🛠️ Tech Stack
Backend

Java 17

Spring Boot

Spring Web

Spring Data MongoDB

Maven

Frontend

React.js

Axios

HTML/CSS

Database

MongoDB (Local or Atlas)

⚙️ Backend Setup
cd backend
.\mvnw.cmd spring-boot:run


Backend runs at:

http://localhost:8081


Test API:

GET http://localhost:8081/api/expenses

💻 Frontend Setup
cd frontend
npm install
npm start


Frontend runs at:

http://localhost:3000

🌐 API Endpoints

Base URL: http://localhost:8081/api/expenses

Method	Endpoint	Description
GET	/api/expenses	Get all expenses
POST	/api/expenses	Create new expense
PUT	/api/expenses/{id}	Update an expense
DELETE	/api/expenses/{id}	Delete an expense
📊 Example JSON
{
  "title": "Groceries",
  "amount": 500,
  "category": "Food",
  "date": "2025-12-04",
  "note": "Vegetables & fruits"
}
