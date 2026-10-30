# Inventory Management System

A backend-focused inventory management application built to manage products, track stock levels, and handle inventory operations with role-based access control.

## Features

- User authentication and authorization using JWT
- Admin and Employee roles
- Password hashing using bcrypt
- Create, read, update, and delete products
- Search products
- Filter products by category and price
- Sort products
- Pagination for product listings
- View individual product details
- Low-stock product endpoint
- Prevent deletion of products while stock is available

## Tech Stack

- **Runtime:** Node.js
- **Backend:** Express.js
- **Database:** MongoDB
- **ODM:** Mongoose
- **Authentication:** JWT
- **Password Security:** bcrypt

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Radhika089/inventory-management.git
cd inventory-management
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the project root:

```env
PORT=your_port
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Use the actual variable names from your project if they differ.

### 4. Run the application

```bash
npm run dev
```

If your project uses a different start script, use the command defined in `package.json`.

## API Overview

The application provides RESTful API endpoints for:

- Authentication
- Product management
- Product search and filtering
- Stock monitoring
- Role-based access control

## Author

**Radhika Bansal**

[GitHub Profile](https://github.com/Radhika089)
