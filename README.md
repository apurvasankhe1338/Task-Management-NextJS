# Task Management Application

This is a task management application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to perform CRUD operations on tasks, register accounts, log in, and exclusively manage their own tasks. Pagination and input validation are implemented to enhance user experience and security.

## Features

- User authentication with JWT
- CRUD operations for tasks
- Authorization to manage only user-specific tasks
- Pagination for task listing
- Input validation using Validator

## Technologies Used

- Frontend:

  - React.js with Vite
  - Formik for form handling
  - React Router for routing
  - Axios for HTTP requests
  - Tailwind for UI components
  - bycrypt for password hashing

- Backend:
  - Express.js for server
  - MongoDB for database
  - bcrypt for password security
  - JWT for authentication

## Installation

1. Clone the repository:
   `git clone https://github.com/apurvasankhe1338/Task-Management-NextJS.git`
2. Navigate to the project directory:
   `cd client`
3. Install dependencies:
   `npm install`
4. Start the development server:
   `npm run dev`


## Deployment

The application is deployed on Vercel. You can access it [here](https://task-management-next-js-zeta.vercel.app/).
