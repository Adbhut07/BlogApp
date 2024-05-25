
# PostHive

PostHive is a blogging application built using the MERN stack (MongoDB, Express.js, React, Node.js).

## Features

- User authentication (register, login, logout)
- Create, read, update, and delete blog posts
- Comment on blog posts
- Responsive design

## Prerequisites

- Node.js (v14 or higher)
- MongoDB

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Adbhut07/BlogApp.git
    cd BlogApp
    ```

2. **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    ```

3. **Install frontend dependencies:**
    ```bash
    cd ../client
    npm install
    ```

## Configuration

1. **Backend:**
   - Create a `.env` file in the `backend` directory.
   - Add the following environment variables:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

2. **Frontend:**
   - Create a `.env` file in the `client` directory.
   - Add the following environment variables:
     ```
     REACT_APP_API_URL=http://localhost:5000
     ```

## Running the Application

1. **Start the backend server:**
    ```bash
    cd backend
    npm start
    ```

2. **Start the frontend server:**
    ```bash
    cd ../client
    npm start
    ```

3. The application should now be running. Open your browser and navigate to `http://localhost:3000`.

## Folder Structure

```
BlogApp/
├── backend/        # Node.js backend code
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── ...
├── client/         # React frontend code
│   ├── public/
│   ├── src/
│   ├── .env
│   └── ...
├── .gitignore
├── package.json
└── README.md
```

## Future Goals
Implemetation of Payment gateway to make application commercial

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.


