# MERN Blog

A full-stack blog web application built using the MERN (MongoDB, Express, React, Node.js) stack.

## Live Demo

Check out the live demo here: [MERN Blog](https://mern-blog-9y88.onrender.com/)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a simple blogging platform where users can:
- Create, read, update, and delete blog posts.
- View all posts on the home page.
- Manage authentication for registered users.

It uses MongoDB for database storage, Express and Node.js for the backend, React for the frontend, and JSON Web Tokens (JWT) for user authentication.

## Features

- **Authentication**: User registration and login with secure JWT.
- **CRUD Operations**: Create, read, update, and delete blog posts.
- **Responsive Design**: Fully responsive, ensuring a seamless experience on all devices.
- **RESTful API**: Backend API for handling blog posts and users.

## Technologies Used

- **Frontend**: React.js, HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **Deployment**: Render

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/mern-blog.git
    ```

2. Navigate to the project directory:
    ```bash
    cd mern-blog
    ```

3. Install dependencies for both the backend and frontend:
    ```bash
    npm install
    cd client
    npm install
    cd ..
    ```

4. Set up environment variables. Create a `.env` file in the root directory and add the following:
    ```bash
    DB_USERNAME=
    DB_PASSWORD=
    ACCESS_SECRET_KEY=
    REFRESH_SECRET_KEY=
    DB=
    ```

5. Run the application:

    - Start the backend server:
      ```bash
      npm run dev
      ```

    - Start the frontend (React) development server:
      ```bash
      cd client
      npm start
      ```

## Usage

1. Register a new user or log in with existing credentials.
2. After logging in, you can create, edit, and delete blog posts.
3. Browse the homepage to see all the posts created by users.

## API Endpoints

### Authentication
- **POST /api/auth/register**: Register a new user.
- **POST /api/auth/login**: Log in a user.

### Posts
- **POST /api/posts**: Create a new blog post (Authenticated).
- **GET /api/posts**: Retrieve all blog posts.
- **GET /api/posts/:id**: Retrieve a specific blog post by ID.
- **PUT /api/posts/:id**: Update a specific blog post by ID (Authenticated).
- **DELETE /api/posts/:id**: Delete a specific blog post by ID (Authenticated).

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
