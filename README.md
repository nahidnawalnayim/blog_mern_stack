# Project Name: NAYIM'S BLOG

## Overview

Welcome to the repository! This project is a full-stack blog application built using the MERN stack (MongoDB, Express.js, React, and Node.js). The application allows users to create, edit, and delete blog posts, as well as view posts from other users. The project demonstrates the use of CRUD operations, authentication, and a responsive UI.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)

## Features

- User authentication (sign up, login, logout)
- Create, read, update, and delete (CRUD) blog posts
- Responsive design
- Rich text editor for creating and editing posts
- View posts from other users
- Comment on posts
- Like and share posts

## Technologies Used

- **Frontend**: React, Redux, CSS, Tailwind css
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Other Tools**: Axios, Mongoose, Bcrypt, Firebase

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Steps

1. **Clone the repository**
   ```sh
   git clone https://github.com/nahidnawalnayim/blog_mern_stack.git
   cd your-blog-project
   ```

2. **Install server dependencies** 
   ```sh
   cd api
   npm install
   ```

3. **Install client dependencies**
   ```sh
   cd ../client
   npm install
   ```

4. **Set up environment variables**

   Create a `.env` file in the `server` directory and add the following:
   ```plaintext
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the server**
   ```sh
   cd api
   npm run dev
   ```

6. **Run the client**
   ```sh
   cd ../client
   npm start
   ```

## Usage

1. Open your browser and go to `http://localhost:5173`
2. Sign up for a new account or log in with an existing account
3. Start creating, editing, and deleting blog posts
4. View and interact with posts from other users

## Folder Structure

```
your-blog-project/
│
├── client/              # React frontend
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── redux/
│       ├── App.js
│       ├── index.js
│       └── ...
│
├── server/              # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── index.js
│   └── ...
│
├── README.md
└── package.json
```


---

Thank you for visiting the repository! Happy coding!
