# 📝 Node-Js-Blogs

A **dynamic and responsive blogging platform** built using **Node.js**.  
It allows users to create, edit, and manage blog posts easily with a clean user interface and powerful backend support.

---

## 🚀 Overview
**Node-Js-Blogs** is a full-stack web application that demonstrates CRUD operations (Create, Read, Update, Delete) using Node.js.  
The project focuses on building a scalable blog system where users can:
- Write new blog posts
- Edit or delete existing posts
- View all blogs with pagination or filtering
- Authenticate securely (login/signup)

---

## 🧠 Features
✅ Create and manage blog posts  
✅ Secure user authentication (JWT/session-based)  
✅ RESTful API endpoints  
✅ Responsive front-end design  
✅ Admin/user roles  
✅ CRUD operations with database integration  
✅ Simple and clean UI for content reading  
✅ Easy deployment ready for cloud hosting  

---

## 🛠️ Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Backend** | Node.js, Express.js |
| **Frontend** | HTML, CSS, JavaScript (EJS or any template engine) |
| **Database** | MongoDB (via Mongoose) |
| **Authentication** | JWT / Sessions |
| **Environment** | dotenv |
| **Version Control** | Git & GitHub |

---

## 📂 Folder Structure
Node-Js-blogs/
│
├── controllers/ # Request handlers
├── models/ # Database schemas
├── routes/ # Application routes
├── views/ # Frontend templates (EJS, Pug, etc.)
├── public/ # Static assets (CSS, JS, images)
├── app.js # Main entry point
├── package.json # Project dependencies
└── README.md # Documentation


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Ananya894-cell/Node-Js-blogs.git
cd Node-Js-blogs
#install dependencies
npm install

#Create a .env file and configure environment variables
PORT=3000
DB_URI=your_database_connection_string
JWT_SECRET=your_secret_key

4️⃣ Start the application
npm start


Then open 👉 http://localhost:3000
 in your browser.
