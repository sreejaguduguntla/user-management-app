# User Management Application

A full-stack User Management Application built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). The application provides a simple and efficient way to manage user records through a modern user interface and RESTful backend APIs.

## Project Overview

This application allows users to:

- Add new users
- View all users
- Update existing user information
- Delete users
- Store user data securely in MongoDB
- Interact with a responsive and user-friendly interface

The project demonstrates full-stack development concepts including frontend development, backend API creation, database integration, state management, and CRUD operations.

## Features

### Frontend

- Responsive UI
- User-friendly forms
- User listing page
- Edit user details
- Delete users
- API integration with backend
- Error and loading state handling

### Backend

- RESTful API architecture
- CRUD operations
- MongoDB database integration
- Express.js server
- Error handling middleware
- Environment variable configuration
- CORS support

## Tech Stack

### Frontend

- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Axios
- React Router DOM

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- CORS
- dotenv

## Project Structure

```text
User-Management-App/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── README.md
│
├── backend/
│   ├── API's/
│   ├── models/
│   ├── config/
│   ├── server.js
│   ├── package.json
│   └── README.md
│
├── screenshots/
│
├── .gitignore
├── README.md
└── package.json
```

## Application Workflow

1. User accesses the frontend application.
2. Frontend sends requests to backend APIs.
3. Backend processes requests using Express.js.
4. MongoDB stores and retrieves user data.
5. Backend returns responses to the frontend.
6. Frontend updates the UI accordingly.

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/user-management-app.git
```

### Move into Project Directory

```bash
cd user-management-app
```

## Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

Start Backend Server:

```bash
npm run dev
```

Backend runs on:

```text
http://localhost:5000
```

## Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
```

Create a `.env` file:

```env
REACT_APP_API_URL=http://localhost:5000/api
```

Start Frontend:

```bash
npm start
```

Frontend runs on:

```text
http://localhost:3000
```

## API Endpoints

| Method | Endpoint | Description |
|----------|-----------|-------------|
| GET | /api/users | Get all users |
| GET | /api/users/:id | Get user by ID |
| POST | /api/users | Create user |
| PUT | /api/users/:id | Update user |
| DELETE | /api/users/:id | Delete user |

## Screenshots

### Home Page

Add screenshot here.

### Add User Page

Add screenshot here.

### Edit User Page

Add screenshot here.

## Future Improvements

- User Authentication
- JWT Authorization
- Role-Based Access Control
- Search Functionality
- Pagination
- User Profile Images
- Dashboard Analytics
- Dark Mode
- Docker Deployment

## Learning Outcomes

This project helped in understanding:

- Full Stack Development
- React Component Architecture
- REST API Development
- MongoDB Database Management
- State Management
- API Integration
- Error Handling
- Project Structure and Deployment

## Author

**Sreeja Guduguntla**
