# store-rating-platform1
Full Stack assignment – Store Rating Platform with Admin, Store Owner, and User dashboards
🏬 Store Rating Platform

A full-stack web application that allows users to sign up, log in, search for stores, and submit ratings (1–5 stars). Admins can manage users and stores, while Store Owners can view ratings for their stores.

# 🚀 Features
👤 User Features
Sign up and log in securely
Search for stores by Name and Address
View all registered stores with:
1. Store Name
2. Address
3. Overall Rating
User’s Submitted Rating
Submit and modify ratings (1–5 stars)
Log out of the system

🛠 Admin Features
View dashboard stats (Users, Stores, Ratings)
Add new users (Normal User, Store Owner, Admin)
Add new stores and assign owners
View a list of stores with: Name, Email, Address, Rating
View a list of users with: Name, Email, Address, Role
Filter users by Name, Email, Address, Role
View detailed user info (including Store Owners’ ratings)

🏪 Store Owner Features
View their own stores and ratings submitted by users
See the average rating for each store

# 🛠 Tech Stack
Frontend: React (with Hooks, Axios)
Backend: Node.js, Express.js
Database: MySQL / PostgreSQL (via Sequelize ORM)
Authentication: JWT & bcrypt

# ⚙️ Installation

1.Clone the repository

git clone https://github.com/Sanika-1127/store-rating-platform1.git
cd store-rating-platform1

2.Install dependencies for backend

cd backend
npm install

3.Install dependencies for frontend

cd frontend
npm install


# Setup .env file in backend:

PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASS=yourpassword
DB_NAME=store_rating
JWT_SECRET=your_secret_key

# Run backend
cd backend
npm start

# Run frontend
cd frontend
npm start

