# E-Commerce Application

This is a full-stack E-Commerce application built with React (frontend), Node.js/Express (backend), and an admin panel.

## Project Structure

- **admin/**: Admin panel for managing products, orders, etc.
- **backend/**: Server-side API with MongoDB, Cloudinary integration.
- **frontend/**: Customer-facing website.

## Prerequisites

- Node.js (v16 or higher)
- MongoDB
- Cloudinary account (for image uploads)

## Setup Instructions

### Backend
1. Navigate to `backend/` directory.
2. Run `npm install` to install dependencies.
3. Set up environment variables in a `.env` file (see `config/mongodb.js` and `config/cloudinary.js` for required keys).
4. Run `npm start` to start the server.

### Frontend
1. Navigate to `frontend/` directory.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.

### Admin
1. Navigate to `admin/` directory.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.

## Usage

- Access the frontend at `http://localhost:5173` (default Vite port).
- Access the admin panel at `http://localhost:5174` (adjust if needed).
- Backend runs on `http://localhost:4000` (default).

## Features

- User authentication and authorization
- Product management
- Shopping cart and checkout
- Order tracking
- Admin dashboard

## Troubleshooting

- Ensure MongoDB is running locally or provide a connection string.
- Check console for errors; common issues include missing environment variables or port conflicts.
- For frontend issues, clear browser cache or reinstall dependencies.

## Contributing

Feel free to submit issues or pull requests.