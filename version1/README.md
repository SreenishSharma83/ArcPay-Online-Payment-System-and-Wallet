# ArcPay - MERN Online Payment & Wallet System

ArcPay is a secure, real-time online payment and wallet system built with the MERN stack. Designed for seamless experiences for both users and admins, ArcPay provides a robust solution for transaction management, fund deposits, and comprehensive security via JWT authentication.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)

## Features
- **User Registration and Authentication**: Secure login and signup with JWT and password encryption.
- **Separate Interfaces**: User and Admin dashboards designed with Ant Design and Tailwind CSS.
- **Transaction Management**: Users can transfer funds and request amounts from other users.
- **Deposit Funds**: Integrated with Stripe for seamless deposits.
- **Real-Time Updates**: Reflects CRUD operations instantly for both users and admins.
- **Admin Controls**: Admins can approve or reject account access requests and manage user accounts.
- **Data Integrity and Security**: Uses MongoDB session handling for safe transactions.

## Technologies Used
*Frontend*:  
- React.js (with Vite for fast bundling)
- Tailwind CSS
- Ant Design for UI components
- Redux Toolkit for state management

*Backend*:  
- Node.js
- Express.js
- MongoDB Atlas with Mongoose
- JWT for authentication
- Stripe for payment processing

*Other Tools*:  
- GitHub for version control
- Deployment-ready

## Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB Atlas account
- Stripe API keys

### Steps to Run

#### 1. Clone the Repository
bash
git clone https://github.com/sreenishsharma83/ArcPay-Online-Payment-System-and-Wallet.git
cd version1
2. Backend Setup
Navigate to the backend directory:
bash
cd backend
Install dependencies:
bash
npm install
Create a .env file with the following configuration:
bash
JWT_SECRET=your_jwt_secret
MONGODB_URI=your_mongodb_uri
STRIPE_SECRET_KEY=your_stripe_secret_key
Start the backend server:
bash
npm start
3. Frontend Setup
Navigate to the frontend directory:
bash
cd ../frontend
Install dependencies:
bash
npm install
Start the frontend server:
bash
npm run dev
