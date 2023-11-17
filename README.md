# Routine-Task-App--MERN-STACK

This is a simple Todo application with a full-stack implementation using Node.js, Express.js, MongoDB for the backend, and React.js for the frontend.

## Features

- User authentication with JWT
- Create, edit, and delete Todos
- Dashboard to view all Todos

![Screenshot (54)](https://github.com/sonu7524/Routine-Task-App--MERN-STACK/assets/100096513/fac3e70d-5611-4d41-9aaf-55a37d553d7b)
![Screenshot (55)](https://github.com/sonu7524/Routine-Task-App--MERN-STACK/assets/100096513/9bd092ac-efe7-43fd-bf76-d042aa99929c)
![Screenshot (56)](https://github.com/sonu7524/Routine-Task-App--MERN-STACK/assets/100096513/f05fa934-8477-4980-95e7-4ea663bca8a0)
![Screenshot (57)](https://github.com/sonu7524/Routine-Task-App--MERN-STACK/assets/100096513/4e51a071-523a-41da-bc71-75ba377e5ec5)

## Prerequisites

Make sure you have the following installed before running the application:

- Node.js
- MongoDB

## Getting Started

### Backend

1. Navigate to the `backend` directory.

```bash
cd server
```

2. Install node dependencies
```
npm install
```
3. Create a .env file in the backend directory and configure your MongoDB connection and JWT secret.
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```
4. Run the server.
```
npm run dev
```
### Frontend
5. Navigate to the frontend directory.
```
cd client
```
7. Install dependencies.
```
npm install
```
8. start the frontend server
```
npm start
```

The app will be accessible at http://localhost:3000.

## Usage
1. Open the app in your browser.

2. Register or log in.

3. Create, edit, and delete Todos.

4. View all Todos on the dashboard.

## Contributing
Feel free to contribute to the project. Fork the repository, make changes, and submit a pull request.

## important!
Make sure to replace placeholders like `your_mongodb_connection_string` and `your_jwt_secret` with your actual MongoDB connection string and a secure JWT secret.

Additionally, ensure that you have proper error handling, input validation, and security measures in place, especially when dealing with authentication and database operations.

