


Personal Expense Tracker with Data Visualization
A modern full-stack web application for managing personal expenses, monitoring monthly budgets, and analyzing spending habits through interactive data visualizations.

Features
Add, edit, and delete expenses

Search and filter expenses

Categories: Food, Travel, Shopping, Bills, Education, Health, Entertainment, Others

Payment methods: Cash, UPI, Card

Dashboard with total, monthly, daily, and average expenses

Monthly budget management with warning

Category-wise pie chart

Payment-method donut chart

Monthly expense bar chart

Daily expense line chart

CSV expense report download

Dark and Light mode

Responsive React frontend

Persistent SQLite database

Flask REST API

Sample data support

Technologies
Frontend
React.js

Vite

JavaScript

HTML5

CSS3

Recharts

Lucide React

Backend
Python

Flask

Flask-CORS

REST API

Database
SQLite

Project Structure
Expense_Tracker_Full_Stack/
│
├── README.md
│
├── backend/
│   ├── app.py
│   ├── database.py
│   ├── requirements.txt
│   └── expenses.db
│
└── frontend/
    ├── package.json
    ├── vite.config.js
    ├── index.html
    └── src/
        ├── App.jsx
        ├── main.jsx
        └── styles.css
System Architecture
USER
  │
  ▼
React Frontend
  │
  │ REST API
  ▼
Flask Backend
  │
  │ SQL
  ▼
SQLite Database
Expense Fields
Date

Category

Amount

Payment Method

Description

REST API
Method	Endpoint	Purpose
GET	/api/health	Check backend status
GET	/api/expenses	Get expenses
POST	/api/expenses	Add expense
PUT	/api/expenses/<id>	Update expense
DELETE	/api/expenses/<id>	Delete expense
GET	/api/budget	Get monthly budget
PUT	/api/budget	Save monthly budget
POST	/api/sample-data	Load sample data
Requirements
Windows 10/11

Python 3.10+

Node.js 18+

npm

VS Code

Installation
Backend
Open a terminal in the project folder:

cd backend
python -m venv venv
venv\Scripts\activate
python -m pip install -r requirements.txt
python database.py
python app.py
Backend:

http://127.0.0.1:5000
Keep this terminal running.

Frontend
Open a second terminal:

cd frontend
npm install
npm run dev
Frontend:

http://localhost:5173
Open the frontend address in your browser.

Quick Run
Terminal 1
cd backend
venv\Scripts\activate
python app.py
Terminal 2
cd frontend
npm run dev
Then open:

http://localhost:5173
Database
SQLite database:

backend/expenses.db
Main tables:

Expenses
id
date
category
amount
payment_method
description
Budgets
month
amount
Project Objectives
Develop a practical full-stack expense management system.

Store financial records permanently.

Implement CRUD operations.

Provide interactive data visualization.

Monitor monthly budgets.

Identify spending patterns.

Generate downloadable reports.

Demonstrate frontend, backend, API, and database integration.

Advantages
Easy to use

Professional dashboard

Responsive design

Persistent database

Interactive charts

Budget monitoring

CSV reporting

Dark/Light mode

Full-stack architecture

Future Scope
User registration and login

JWT authentication

Multiple user accounts

Income tracking

Savings goals

AI-based expense prediction

Automatic expense categorization

Email notifications

PDF reports

PostgreSQL/MySQL

Cloud deployment

Mobile application

Academic Information
Project Title: Personal Expense Tracker with Data Visualization

Project Type: Full Stack Web Application

Frontend: React.js

Backend: Python Flask

Database: SQLite

Visualization: Recharts

Conclusion
The Personal Expense Tracker with Data Visualization provides an efficient and user-friendly way to manage personal expenses. By combining React.js, Flask, SQLite, REST APIs, and interactive charts, the project demonstrates practical full-stack development skills and provides a useful real-world application.
