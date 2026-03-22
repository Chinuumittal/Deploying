# MERN Stack Restaurant Reservation App

A full-stack restaurant reservation system built using the MERN stack (MongoDB, Express, React, Node.js). 
This application provides an elegant user interface for customers to explore the restaurant's offerings and make reservations online.

## Features

- **Landing Page Details**: Beautiful hero section, "About Us", "Qualities", "Who Are We", and "Team" sections to showcase the restaurant's brand identity.
- **Menu Display**: Interactive menu component showcasing the restaurant's food items.
- **Online Reservation System**: Real-time table booking form with client-side and server-side validation.
- **Success Page**: Dedicated routing to a success page upon successful reservation.
- **Responsive UI**: Built with modern frontend paradigms guaranteeing an optimal viewing experience across all devices.
- **Toast Notifications**: Seamless feedback interactions provided by `react-hot-toast`.

## Tech Stack

**Frontend**
- **React.js** (Bootstrapped with Vite)
- **React Router DOM**
- **Axios**
- **React Hot Toast**, **React Icons**, **React Scroll**

**Backend**
- **Node.js** & **Express**
- **MongoDB** & **Mongoose**
- **Cors**, **Dotenv**, **Validator**

## Folder Structure

```plaintext
MERN_STACK_RESTAURANT_RESERVATION/
├── backend/                  # Server-side Application
│   ├── app.js                # Express app setup and middleware
│   ├── controller/           # Route handler logic 
│   ├── database/             # MongoDB connection utilities
│   ├── middlewares/          # Custom middlewares (e.g., error handling)
│   ├── models/               # Mongoose data schemas
│   ├── routes/               # API endpoint configurations
│   └── server.js             # Main server entry file
└── frontend/                 # Client-side Application
    ├── public/
    ├── src/
    │   ├── App.jsx           # Main routing map setup
    │   ├── components/       # Reusable UI React components
    │   └── Pages/            # Page-view components (Home, Success, NotFound)
    └── package.json
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
- MongoDB Cluster or Local Instance

### Installation

1. **Clone the repository and enter the project folder**
   ```bash
   cd DEPLOYING
   ```

2. **Backend Setup**
   ```bash
   cd backend
   npm install
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   ```

### Environment Configuration

Configure the required environment configurations. In the backend, make folder  `backend/config/` and create `config.env`:

```env
PORT=4000
FRONTEND_URL=http://localhost:5173
MONGO_URI=your_mongodb_connection_uri_here
```

### Running the Application

1. **Start the Express Backend Server** (from the `backend` folder):
   ```bash
   npm start
   ```
2. **Start the Vite Frontend Development Server** (from the `frontend` folder):
   ```bash
   npm run dev
   ```

Access the application in your browser at `http://localhost:5173`.
