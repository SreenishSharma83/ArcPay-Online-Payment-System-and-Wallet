# ArcPay-Online-Payment-System-and-Wallet

The BreadcrumbsArcPay-Online-Payment-System-and-Wallet Application is a full-stack web application built using the **MERN** stack (MongoDB, Express.js, React.js, Node.js) that allows users send money, request money, add balance, accept payment, accept payment requets. It provides a user-friendly interface for organizing transactions and gaining insights into spending habits.

## Technologies Used

**Front-end:** The user interface is developed using React.js initialized using vite, a popular JavaScript library for building dynamic web applications.
for front end data management **redux-toolkit** is also used.

**Back-end:** The server-side of the application is built with **Node.js and Express.js**, providing a scalable and robust foundation.

**Database:** **MongoDB** is utilized as the NoSQL database to store and retrieve financial data efficiently.

**API Integration:** used **cloudinary** service is also used to manage user media's

## Installation and Usage

To install and run the Wallet Application locally, follow these steps:

### Step 1: Clone the repository

```
git clone <repositoru url>
```

### Step 2: Install dependencies

Navigate to the project root and install the necessary dependencies for the project

```
npm install 

cd frontend
npm install

cd backend
npm install
```

after installation navigate to root and run:

```
npm run dev
```

### Step 3: Configure the environment variables

 - create `.env` in root and add following variables

```
MONGO_URI=<your-mongo-uri>
JWT_SECRET=<jwt-secret>
STRIPE_SECRET_KEY=your_stripe_secret_key
```

## Features
 - user login
 - user register
 - user logout
 - user dashboard
 - profile update
 - send money
 - receive money
 - money request
 - view send transactions
 - view received transactions
 - view money requests send from other users
 - accept money request and pay amount
 - add balance to our account
 - verify user after registration (ADMIN)
