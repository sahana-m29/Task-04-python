Here is your **README.md content**, ready to copy into a file named **README.md**:

---

# User Management API (Flask)

This project is a simple REST API built using **Flask** that performs CRUD operations (Create, Read, Update, Delete) on user data stored in memory.

---

## 🚀 Features

* GET all users
* GET a specific user by ID
* POST to create a new user
* PUT to update user details
* DELETE to remove a user
* In-memory storage (no database needed)

---

## 📁 Project Structure

```
app.py
README.md
```

---

## ▶️ How to Run the Application

### 1. Install dependencies

```bash
pip install flask
```

### 2. Run the server

```bash
python app.py
```

### 3. Server will start at:

```
http://127.0.0.1:5000/
```

---

## 🧪 API Endpoints

### **GET /users**

Get all users.

### **GET /users/<id>**

Get a single user by ID.
Returns 404 if not found.

---

### **POST /users**

Create a new user.

#### Example Request Body:

```json
{
  "name": "Bob",
  "email": "bob@example.com"
}
```

---

### **PUT /users/<id>**

Update user information.

#### Example Request Body:

```json
{
  "name": "Alice Updated",
  "email": "alice.new@example.com"
}
```

---

### **DELETE /users/<id>**

Delete a user by ID.

---

## 📌 Notes

* This API uses **in-memory data**, so user information resets every time the server restarts.
* Perfect for beginners learning REST API development with Flask.

---

