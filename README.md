# Customer Management System

## Description
This is a Customer Management System that provides CRUD (Create, Read, Update, Delete) functionality for managing customer information. The application is built with Node.js for the backend, React and Redux for the frontend, and MongoDB as the database.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## Features
- Add new customers
- View a list of customers
- Update customer details
- Delete customers
- Responsive UI design

## Technologies
- **Backend**: Node.js, Express.js
- **Frontend**: React, Redux
- **Database**: MongoDB
- **CSS**: Styled Components / CSS Modules

## Prerequisites
Make sure you have the following installed on your system:
- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB

## Usage
1. **Run the backend server:**
    ```bash
    cd cms
    cd backend
    npm start
    ```

2. **Run the frontend server:**
    ```bash
    cd cms
    cd ../frontend
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## API Endpoints
### Customers
- **GET /api/customers** - Get all customers
- **GET /api/customers/:id** - Get a customer by ID
- **POST /api/customers** - Add a new customer
- **PUT /api/customers/:id** - Update a customer by ID
- **DELETE /api/customers/:id** - Delete a customer by ID


