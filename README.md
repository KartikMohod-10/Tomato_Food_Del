🍅 Tomato - Food Delivery Web App
Tomato is a full-stack MERN-based Food Delivery Web Application that provides users with a seamless food ordering experience. It includes a powerful Admin Dashboard to manage food items, users, and orders, along with secure Stripe payment integration for online transactions.

🚀 Features
👨‍🍳 User Side
Browse food items by category
Add items to cart
Manage cart and place orders
Secure online payments using Stripe
Authentication for login/signup
View order history

🛠 Admin Dashboard
Add, edit, or delete food items
Manage customer orders and track statuses
View total revenue and analytics

🧠 Tech Stack (MERN)
MongoDB – Database for storing users, orders, and products
Express.js – Backend server and RESTful API
React.js – Frontend UI with dynamic components
Node.js – Server environment

💳 Payment Integration
Stripe payment gateway for secure and fast online payments

📁 Project Structure
bash
Copy
Edit
tomato-food-delivery/
├── admin/           # Admin Dashboard (React)
├── backend/         # Express.js Server + MongoDB + Stripe Integration
├── frontend/        # User-facing website (React)
└── README.md

🔧 Setup Instructions
Prerequisites
Node.js and npm
MongoDB Atlas or local MongoDB
Stripe account for payment API keys

1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/tomato-food-delivery.git
cd tomato-food-delivery

2. Backend Setup
bash
Copy
Edit
cd backend
npm install

3.🔐 Create .env in backend folder:
ini
Copy
Edit
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
bash
Copy
Edit
npm run server

4. Frontend Setup (User Website)
bash
Copy
Edit
cd ../frontend
npm install
npm start

5. Admin Panel Setup
bash
Copy
Edit
cd ../admin
npm install
npm start

6.🔐 Stripe Integration
Stripe is integrated in the backend using the Stripe Node.js SDK.
Users can securely make payments during checkout.
Use test card details from Stripe Docs for testing in development.

📸 Screenshots
 HOME PAGE :-![image](https://github.com/user-attachments/assets/277dfd8f-480d-442d-99a2-1664bad7df09)
 MENU PAGE :- ![image](https://github.com/user-attachments/assets/ac4f8a05-b7a5-463e-af90-a72839d12c34)
 MOBILE APP :-![image](https://github.com/user-attachments/assets/0b023c05-53d0-4ee2-94eb-22b797221474)
 CONTACT US :- ![image](https://github.com/user-attachments/assets/16582d68-2122-4b8c-9f53-645531c3e8b9)
 ADMIN PAGE :-![image](https://github.com/user-attachments/assets/e2bf922d-4e7d-421c-a905-27808013ae3a)
 
🖼️ Demo
 LIVE DEMO :-  FRONTEND :- https://tomato-food-del-admin-8g6k.onrender.com
               ADMIN :- https://tomato-food-del-admin-8g6k.onrender.com

📦 Deployment
You can deploy this project using:
Frontend/Admin: Vercel / Netlify
Backend: Render / Railway / Cyclic
Database: MongoDB Atlas
