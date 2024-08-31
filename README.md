# Full Stack Food Ordering Website/App

This repository contains the source code for a full-stack food ordering website/app developed using `React JS`, `MongoDB`, `Express`, `Node JS`, and `Stripe` payment gateway. The project includes a responsive frontend website, an admin panel, and a backend server.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [License](#license)

## Project Overview

In this tutorial, you will learn to create a complete food ordering system that allows users to browse food items, add them to a cart, and place orders using online payment. The project covers user authentication, shopping cart functionality, order status updates, and more.

## Features

- **Responsive Frontend Website:** Built with `React JS` to provide a seamless user experience across devices.
- **User Authentication:** Allows users to create accounts and log in to the website.
- **Shopping Cart Functionality:** Users can add food items to their cart and place orders.
- **Stripe Payment Integration:** Secure online payment processing through `Stripe`.
- **Admin Panel:** Admins can manage food items, view orders, and update order statuses.
- **Backend Server:** Built with `Node JS` and `Express` to handle API requests and manage the database.
- **MongoDB Atlas Integration:** A cloud database setup for storing user data, food items, and orders.

## Project Structure

- **Frontend:** Developed using `React JS`, the frontend includes components for the homepage, cart, order page, and user authentication.
- **Backend:** Built with `Node JS` and `Express`, the backend handles API requests and interacts with `MongoDB`.
- **Admin Panel:** A `React JS`-based panel for administrators to manage the application.

# Installation Guide

## Installation Steps

### 1. Clone the Repository
Clone the repository to your local machine using the following command:

\```bash
git clone <repository-url>
cd food-del
\```

### 2. Install Dependencies for the Backend
Navigate to the `backend` directory and install the necessary dependencies:

\```bash
cd backend
npm install
\```

### 3. Install Dependencies for the Frontend
Next, navigate to the `frontend` directory and install the frontend dependencies:

\```bash
cd ../frontend
npm install
\```

### 4. Set Up Environment Variables
Create a `.env` file in the `backend` directory and add the following environment variables:

\```env
MONGO_URI=<your-mongodb-atlas-uri>
JWT_SECRET=<your-jwt-secret>
STRIPE_SECRET_KEY=<your-stripe-secret-key>
\```

### 5. Run the Backend Server
Start the backend server by running the following command in the `backend` directory:

\```bash
cd backend
npm start
\```

### 6. Run the Frontend Development Server
Finally, start the frontend development server by running the following command:

\```bash
cd ../frontend
npm start
\```



# Usage and Technologies

## Usage

### Frontend Website:

- Users can browse food items, add them to the cart, and place orders.
- User registration and login are required to place orders.

### Admin Panel:

- Admins can log in to manage food items and view/update orders.

### Order Processing:

- Orders are placed with `Stripe` for secure payment processing.
- Users can view their order status on the order page.

## Screenshots

_Add screenshots here to showcase the frontend, admin panel, and order process._

## Technologies Used

- **Frontend:** `React JS`, HTML, CSS, Bootstrap
- **Backend:** `Node JS`, `Express`
- **Database:** `MongoDB Atlas`
- **Authentication:** `JSON Web Tokens (JWT)`
- **Payment Gateway:** `Stripe`
