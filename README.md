# RESTful E-Commerce Backend API

A scalable and production-ready REST API built using **Node.js**, **Express**, and **MongoDB**.  
This project focuses on backend engineering fundamentals such as authentication, authorization, data modeling, filtering, pagination, and secure API design.

---

## 🚀 Features

### User Features
- User registration and authentication (JWT-based)
- Email verification and password reset flow
- Browse products and view detailed information
- Search, filter, sort, and paginate products
- Add products to cart and place orders

### Admin Features
- Admin authentication and authorization
- Create, update, and delete products
- Manage users and roles
- Product inventory control

---

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT, bcrypt  
- **Tools:** Git, GitHub, Postman  
- **Deployment:** Heroku (earlier), Local / Cloud-ready

---
src/
├── controllers/
├── models/
├── routes/
├── middlewares/
├── config/
└── server.js

---

## 🔗 API Capabilities
- CRUD operations on products and users
- Filtering, sorting, pagination, and full-text search
- Secure role-based access using middleware
- Centralized error handling and validation

---

## ⚙️ Environment Variables
Create a `.env` file with the following:
MONGODB_CONNECTION_STRING=
ACCESS_TOKEN_SECRET_KEY=
REFRESH_TOKEN_SECRET_KEY=
JWT_EXPIRE_TIME=
NODE_ENV=development

---

## ▶️ Run Locally

### Clone the repository
```bash
git clone https://github.com/slietian/Node.js-Express-E-Commerce-Backend-REST-API-
cd your-repo-name
Install dependencies
npm install

Start the server
npm run dev
# or
node server.js


Server runs at:

http://localhost:8080


## 📂 Project Structure
