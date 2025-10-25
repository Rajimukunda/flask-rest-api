# Flask REST API Project

## 📘 Overview
This project is a simple **Flask-based REST API** that manages user data.  
It supports basic CRUD operations — Create, Read, Update, and Delete.

---

## 🚀 Features
- GET all users
- GET a single user by ID
- POST a new user
- PUT (update) an existing user
- DELETE a user

---

## 🧠 Tech Stack
- **Language:** Python
- **Framework:** Flask
- **Tools:** Postman / Curl for testing

---

## ⚙️ How to Run the Project

### 1️⃣ Clone this repository
```bash
git clone https://github.com/<your-username>/flask-rest-api.git
2️⃣ Navigate into the folder
cd flask-rest-api
3️⃣ Set up a virtual environment
python -m venv venv

4️⃣ Activate the environment

Windows:  venv\Scripts\activate
5️⃣ Install dependencies
pip install flask

6️⃣ Run the Flask server
python app.py


Server runs at → http://127.0.0.1:5000
🧪 API Endpoints
Method	Endpoint	Description
GET	/users	Get all users
GET	/users/<id>	Get a user by ID
POST	/users	Create a new user
PUT	/users/<id>	Update a user
DELETE	/users/<id>	Delete a user
Example Request (POST)
{
  "name": "Charlie",
  "email": "charlie@example.com"
}

---

### 💾 Step 5: Add and Commit Files

Run these commands:

```bash
git add .
git commit -m "Initial commit - Flask REST API project"

