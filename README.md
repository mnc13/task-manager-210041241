# task-manager-210041241

Task Manager - MERN Stack Application

A full-featured Task Management application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that helps teams collaborate and manage tasks efficiently.

# Features

1. User Management

Secure authentication with JWT

User profile management

Role-based access control

2. Task Management
   
🗂️ Create, read, update, and delete tasks

📅 Set due dates and priorities

🔄 Automated status updates based on checklist completion

👥 Assign tasks to multiple team members

📊 Priority and progress tracking

📎 File attachments support

# Dashboard & Reporting

📊 Visual task progress tracking

📥 Export task reports in multiple formats

🔍 Filter and search tasks

# UI/UX

📱 Fully responsive design

🧭 Intuitive navigation with sidebar menu

🎨 Clean, modern interface

# Technologies Used

- Frontend:

React.js

Redux (for state management)

Axios (for API calls)

React Router (for navigation)

Tailwind CSS (for styling)

React Icons (for icons)

- Backend:

Node.js

Express.js

MongoDB (with Mongoose ODM)

JSON Web Tokens (for authentication)

Multer (for file uploads)

Moment.js (for date handling)

Development Tools:

Vite (frontend build tool)

Nodemon (server auto-reload)

Postman (API testing)

# Prerequisites

Before running the application, ensure you have the following installed:

Node.js (v16 or higher)

npm (v8 or higher) or yarn

MongoDB (either locally or MongoDB Atlas connection string)

# Install dependencies

Run these commands in separate terminal windows/tabs:

1. For the server:

cd server

npm install

2. For the client:

cd client

npm install

# Running the Application

1. Start the MongoDB server
   
Ensure MongoDB is running locally or have your MongoDB Atlas connection string ready in the .env file.

2. Start the backend server
   
In the server directory:

npm run dev

This will start the server with nodemon for automatic reloading.

3. Start the frontend development server
   
In the client directory:

npm run dev

This will launch the React application in development mode.
