🍽️ Restaurant Management System

A full-stack Restaurant Management System built with secure authentication using JWT and database integration. This application allows users to manage menu items, orders, and user accounts efficiently.

🚀 Features

🔐 User Registration & Login

🔑 JWT-based Authentication & Authorization

🔒 Secure password hashing (bcrypt)

📋 CRUD operations for Menu

🛒 Order Management System

💾 Database integration

⚡ RESTful API architecture

🛠️ Tech Stack

Frontend:

HTML, CSS, JavaScript (or React if used)

Backend:

Node.js

Express.js

Database:

MongoDB (or MySQL)

Authentication:

JSON Web Token (JWT)

Bcrypt

📂 Folder Structure
restaurant-system/
│── models/        # Database schemas
│── routes/        # API routes
│── controllers/   # Business logic
│── middleware/    # Authentication (JWT)
│── config/        # Database configuration
│── server.js      # Main server file
🔐 Authentication Workflow

User signs up with credentials

Password is hashed using bcrypt

User logs in → JWT token is generated

Token is sent in headers for protected routes

Middleware verifies token before access

⚙️ Installation & Setup
# Clone repository
git clone https://github.com/your-username/restaurant-system.git

# Move into folder
cd restaurant-system

# Install dependencies
npm install

# Start the server
npm start
🔑 Environment Variables

Create a .env file in the root directory:

PORT=5000
MONGO_URI=your_database_url
JWT_SECRET=your_secret_key
📌 API Endpoints
🔹 Auth Routes

POST /api/auth/register

POST /api/auth/login

🔹 Menu Routes

GET /api/menu

POST /api/menu

PUT /api/menu/:id

DELETE /api/menu/:id

🔹 Order Routes

POST /api/orders

GET /api/orders


Add screenshots of your UI here (recommended)

🚧 user dashboard

📊 Admin dashboard


