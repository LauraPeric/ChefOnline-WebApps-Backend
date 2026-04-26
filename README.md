# 🍽️ ChefOnline - Web Apps Backend

Backend application for the **ChefOnline** project, built with Node.js and Express.js. The system enables user management, recipe handling, and forum functionality, along with authentication and file uploads.

---

## 🚀 Technologies

- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT authentication (jsonwebtoken)
- bcryptjs (password hashing)
- multer (file uploads)
- cors
- body-parser

---

## 📦 Installation

### Clone the repository:
```bash
git clone https://github.com/LauraPeric/ChefOnline-WebApps-Backend.git
```

### Navigate to the project:
```bash
cd ChefOnline-WebApps-Backend
```

### Install dependencies:
```bash
npm install
```

---

## ▶️ Running the server

### Development (with nodemon):
```bash
npm start
```

### Production:
```bash
node index.js
```

---

## 🌐 Features

👤 User registration and login  
🔐 JWT authentication and protected routes  
🍲 Recipe management (CRUD operations)  
💬 Forum (create and read posts)  
🖼 Image upload using Multer  
🗄 Data storage in MongoDB database  

---

## 📁 Project structure

```
api/
config/
index.js
routes/
models/
package.json
```

---

## 🔐 Authentication

This project uses JWT (JSON Web Token) for user authentication.  
Passwords are hashed using bcryptjs before being stored in the database.

---

## 📌 Note

The frontend application (Vue.js) communicates with this backend via a REST API.
