# Forever-Full-Stack-E-Commerce 
## Overview  
This is a full-stack e-commerce application built using the MERN stack (MongoDB, Express, React, and Node.js). It includes three main components:  
1. **Frontend**: User-facing e-commerce website for browsing products, managing a cart, and making purchases.  
2. **Backend**: Server-side logic for handling API requests, user authentication, and database operations.  
3. **Admin Panel**: Interface for administrators to manage products, orders, and users.  

---

## Features  
### Frontend:  
- User-friendly interface for product browsing.  
- Search and filter functionality for products.  
- Cart management and secure checkout.  
- User authentication (login, signup).  
- Order history for users.  

### Backend:  
- RESTful API for handling frontend requests.  
- Secure user authentication using JWT.  
- CRUD operations for products and orders.  
- Integration with a payment gateway (e.g., Stripe/PayPal).  
- Middleware for error handling and request validation.  

### Admin Panel:  
- Dashboard for monitoring sales and orders.  
- Manage products: Add, update, delete, and view.  
- Manage users: View user list and block/unblock users.  
- View and manage orders.  

---

## Tech Stack  
### Frontend:  
- **React.js**  
- **Redux** (State management)  
- **Tailwind CSS** or **Material-UI** (Styling)  
- **Axios** (API calls)  

### Backend:  
- **Node.js**  
- **Express.js**  
- **MongoDB** (Database)  
- **Mongoose** (ODM)  
- **JWT** (Authentication)  
- **Bcrypt.js** (Password encryption)  

### Admin Panel:  
- **React.js**  
- **Redux**  
- **Tailwind CSS** or **Material-UI**  

---

## Folder Structure  
```plaintext
|-- backend/          # Server-side code  
|   |-- models/       # Mongoose models  
|   |-- routes/       # API routes  
|   |-- controllers/  # Logic for API endpoints  
|   |-- config/       # Configuration (e.g., database, JWT secret)  
|   |-- server.js     # Entry point for the server  
|-- frontend/         # User-facing application  
|   |-- src/          # React application code  
|   |-- public/       # Static assets  
|-- admin/            # Admin panel application  
|   |-- src/          # React application code  
|   |-- public/       # Static assets

## How to Setup & Run this Project
Install Node.js (Ignore if already installed)
Visit the official Node.js website: https://nodejs.org/en/download/.
Download the Node.js installer for your operating system.
Run the installer.
Follow the prompts in the installer to complete the installation.
Setup Steps
1. Run Backend First, Then Frontend and Admin
Steps to Setup the Backend of the Project
Open the project folder in VS Code or your preferred code editor.
Navigate to the backend folder:
Right-click on the backend folder and select "Open in Integrated Terminal".
Run the following commands in the terminal:
Install dependencies:
bash
Copy code
npm install  
Wait for the installation to complete (requires an active internet connection).
Create a .env file in the backend folder with the following content:
plaintext
Copy code
PORT=5000  
MONGO_URI=your-mongodb-uri  
JWT_SECRET=your-secret-key  
Start the backend server:
bash
Copy code
npm start  
The backend server will run on http://localhost:5000.
Steps to Setup the Frontend of the Project
Navigate to the frontend folder:
Right-click on the frontend folder and select "Open in Integrated Terminal".
Run the following commands in the terminal:
Install dependencies:
bash
Copy code
npm install  
Wait for the installation to complete.
Start the frontend development server:
bash
Copy code
npm start  
The frontend will run on http://localhost:3000.
Steps to Setup the Admin Panel
Navigate to the admin folder:
Right-click on the admin folder and select "Open in Integrated Terminal".
Run the following commands in the terminal:
Install dependencies:

bash
Copy code
npm install  
Wait for the installation to complete.
Start the admin panel development server:
bash
Copy code
npm start  
The admin panel will run on http://localhost:3001.
Access the Project
Frontend (User-facing website): http://localhost:3000.
Admin Panel (Admin dashboard): http://localhost:3001.
Backend API: http://localhost:5000.
