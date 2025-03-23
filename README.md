# Bighorn POS System

A comprehensive Point of Sale (POS) system for restaurant management.

## Features

- Table Management (Add, Merge, Split, Assign Orders)
- Menu Management (Add, Edit, Delete Dishes)
- Order Management with Status Control
- Bill Generation and Payment Flow
- Tax and Category Management
- Search and Filter Functionality
- Secure User Authentication (Admin & Staff Roles)

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express.js
- MySQL
- JWT Authentication

## Project Structure

```
/bighorn-pos
├── /client          # Frontend React application
└── /server          # Backend Node.js application
```

## Setup Instructions

### Frontend Setup
1. Navigate to the client directory
2. Install dependencies: `npm install`
3. Start development server: `npm start`

### Backend Setup
1. Navigate to the server directory
2. Install dependencies: `npm install`
3. Create a .env file with required environment variables
4. Start the server: `npm run dev`

## Environment Variables

Create a `.env` file in the server directory with the following variables:
```
DB_HOST=your_database_host
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_NAME=bighorn_pos
JWT_SECRET=your_jwt_secret
PORT=5000
```

## License

MIT 