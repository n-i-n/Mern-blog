
# MERN Blog

This project is a full-stack blogging platform built using the MERN stack (MongoDB, Express.js, React, and Node.js). The blog allows users to create, read, update, and delete blog posts. It also includes user authentication and authorization.

## Live Demo

Check out the live demo: [MERN Blog](https://mern-blog-9y88.onrender.com/)

## Features

- User authentication (sign up, login, and logout)
- Create, read, update, and delete (CRUD) blog posts
- User-specific blog management
- Protected routes and authorization
- Interactive UI built with React
- RESTful API using Express.js
- MongoDB for data storage

## Technologies Used

### Frontend
- **React.js**
- **Axios** for HTTP requests
- **React Router** for routing

### Backend
- **Node.js** with **Express.js**
- **MongoDB** with **Mongoose** for database management
- **JSON Web Token (JWT)** for authentication
- **Bcrypt** for password hashing

### Other Tools
- **Render** for hosting the live demo
- **GitHub** for version control

## Setup and Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/n-i-n/Mern-blog.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Mern-blog
   ```

3. **Install backend dependencies:**
   ```bash
   cd backend
   npm install
   ```

4. **Install frontend dependencies:**
   ```bash
   cd ../frontend
   npm install
   ```

5. **Set up environment variables:**
   Create a `.env` file in the `backend` directory with the following content:
   ```bash
   MONGO_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret>
   ```

6. **Run the backend server:**
   ```bash
   npm run server
   ```

7. **Run the frontend server:**
   ```bash
   npm start
   ```

The app should now be running at `http://localhost:3000`.

## API Endpoints

- `POST /api/auth/signup` - User signup
- `POST /api/auth/login` - User login
- `GET /api/posts` - Fetch all posts
- `POST /api/posts` - Create a new post (authenticated users only)
- `PUT /api/posts/:id` - Update a post (authenticated users only)
- `DELETE /api/posts/:id` - Delete a post (authenticated users only)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions, feel free to reach out via the GitHub repository:  
[GitHub Repository](https://github.com/n-i-n/Mern-blog)
