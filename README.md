# Real Estate Web Application

This project is a full-stack **Real Estate Web Application** built using the **MERN** stack (MongoDB, Express.js, React, and Node.js). It allows users to browse property listings, search for specific properties, register as users, and manage their property listings. The platform provides a modern, intuitive interface for users to find, save, and submit real estate properties.

## Features

- **User Authentication**
  - Sign up, log in, and log out functionality.
  - Role-based access control for buyers, sellers, and admins.

- **Property Listings**
  - Browse property listings with detailed information including location, price, size, and photos.
  - Filter and search properties by price, type, location, etc.

- **Property Submission**
  - Sellers can submit new property listings.
  - Edit or delete listings based on user roles.

- **Favorites & Wishlist**
  - Users can add properties to their wishlist for easy access later.

## Technologies Used

- **MongoDB**: NoSQL database for storing user data and property listings.
- **Express.js**: Backend framework for building REST APIs.
- **React**: Frontend framework for building an interactive user interface.
- **Node.js**: JavaScript runtime for building server-side applications.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-estate-app.git
2. Install dependencies for both the client and server:

   ```bash
   npm install
   cd client
   npm install

Set up your environment variables:

Create a .env file in the root directory for the backend configuration.
Add MongoDB connection string and any necessary API keys.
Start the development servers:
     ```bash

    # Start backend server
     cd server
     npm run start

    # Start frontend server
     cd client
     npm run dev
Usage
Visit the homepage to browse all properties.
Use the search functionality to find properties based on your preferences.
Register and log in to manage your favorite listings or add new properties (if you are a seller).
Admins can manage all property listings.
